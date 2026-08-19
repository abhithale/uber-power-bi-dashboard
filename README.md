# 🚕 Uber Trip Analytics Dashboard — Power BI Project

An interactive **Power BI dashboard** built on Uber ride-booking data to analyze bookings, revenue, vehicle-wise performance, and customer ratings — with a dynamic vehicle-type filter applied across every page.

## 📌 Overview

Uber's operations generate huge volumes of trip-level data — bookings, cancellations, revenue, distance, ratings — spread across vehicle types. This project consolidates that data into a **4-page Power BI report** so operations and finance teams can track performance at a glance instead of digging through raw data.

**Report Pages:**
| Page | Description |
|------|-------------|
| 🏠 Home | Landing page with navigation into the report |
| 📊 Overview | Core KPIs, booking status split, monthly/quarterly trend, ratings |
| 🚗 Overview of Vehicles | Vehicle-wise comparison table (bookings, revenue, customers) |
| 💰 Revenue | Revenue trend, revenue by payment method, revenue by vehicle type |

---

## 🖼️ Dashboard Preview

### Overview Page

KPI cards (Completed, Lost Booking, Revenue, Total Distance, Average Distance), a Completed/Cancelled/Incomplete booking split, a Month/Quarter trend toggle, monthly revenue chart, revenue by vehicle type, top pickup location, and average driver/customer ratings.

### Overview of Vehicles Page

A single detail table comparing every vehicle type — **Uber XL, Premier Sedan, Go Sedan, Go Mini, Bike, Auto** — on completed bookings, lost bookings, customer count, revenue, and a monthly revenue sparkline, with a Total row for reconciliation.

### Revenue Page


Revenue trend by month, revenue split by payment method (UPI, Cash, Uber Wallet, Credit Card, Debit Card), and revenue ranked by vehicle type.

---

## 🎯 Key KPIs Tracked

- ✅ Completed Bookings
- ❌ Lost Bookings (Cancelled / Incomplete)
- 💰 Revenue
- 📏 Total Distance & Average Distance
- ⭐ Average Driver Rating & Average Customer Rating
- 📍 Top Pickup Location by booking count

---

## ⚙️ Features

- 🔄 **Cross-page vehicle filter** — a synced slicer (Auto, Bike, Go Mini, Go Sedan, Premier Sedan, Uber XL) drives every visual across all pages
- 📅 **Month / Quarter toggle** on the trend chart for flexible time analysis
- 📈 Vehicle-wise **contribution and comparison table** with monthly trend sparklines
- 💳 **Payment method breakdown** for revenue analysis
- ⭐ Driver and customer satisfaction tracking via average ratings

---

## 🛠️ Tech Stack

- **Power BI Desktop** — report design & visualization
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures (Completed/Lost Bookings, Revenue, Avg Distance, Avg Ratings, etc.)
- **Data Modeling** — relationships between Bookings, Vehicle, Customer, and Payment tables

---

## 🚀 How to Use

1. Clone this repository
2. Open `Uber_Dashboard.pbix` in **Power BI Desktop**
3. Click any vehicle icon in the left filter panel to slice the entire report
4. Use the Month/Quarter toggle on the Overview page to switch trend granularity

---

## 📬 Contact

Feel free to connect if you'd like to discuss this project or collaborate on data analytics work.

⭐ If you found this project useful, consider giving the repo a star!
