# Oryx Masvingo — Delivery & Car Rental Portal

A streamlined management dashboard designed for localized delivery and vehicle rental operations in Masvingo. Built for speed, mobile responsiveness, and ease of use in low-bandwidth environments.

---

## 🚀 Status: UNDER MAINTENANCE
**Current State:** The portal is currently in maintenance mode to perform database upgrades and security audits.

* **Kill-Switch Status:** `ACTIVE`
* **Redirect:** All traffic is currently routed to `maintenance.html`.

---

## 🛠 Features
* **Real-time Dashboard:** High-level overview of net profit, revenue, and operating costs.
* **Inventory Management:** Track stock levels for retail and rental assets.
* **Transaction Logging:** Simple interface for recording sales and "Stock-In" events.
* **Expense Tracking:** Dedicated module for logging fixed costs (Rent, Starlink, Salaries) and variables (Ice, Sundries).
* **Cloud-Ready:** Integrated with Supabase (PostgreSQL) for permanent data persistence.

---

## 🏗 Tech Stack
* **Frontend:** HTML5, CSS3 (Custom Variables), Vanilla JavaScript.
* **Backend/Database:** [Supabase](https://supabase.com) (PostgreSQL).
* **Hosting:** [Vercel](https://vercel.com).
* **Deployment:** Continuous Integration (CI/CD) via GitHub.

---

## ⚙️ Configuration & Environment Variables
The app requires the following environment variables set in the Vercel dashboard to communicate with the database:

| Variable | Description |
| :--- | :--- |
| `SUPABASE_URL` | Your project's unique Supabase API URL. |
| `SUPABASE_ANON_KEY` | The public 'anon' key for client-side authentication. |

---

## 🚧 Development & Maintenance
To toggle the system online/offline:
1. Open `oryx-portal.html`.
2. Locate the `MAINTENANCE_MODE` constant in the `<head>`.
3. Set `true` to pause or `false` to resume.
4. Commit and push to `main` branch.

---

## 👤 Author
**Teererai Kagura**
*Lead Developer & Systems Architect*
