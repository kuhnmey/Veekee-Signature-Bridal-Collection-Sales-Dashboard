# Veekee Signature Bridal Collection — Sales Dashboard

An Excel dashboard analyzing sales performance for **Veekee Signature**, a simulated bridal wear line inspired by the Nigerian fashion brand Veekee James. The project explores order volume, revenue, turnaround time, and client satisfaction across bridal gown styles, states, and sales channels.

## 📌 Project Overview

Veekee Signature offers made-to-measure and ready-to-wear (adjusted) bridal gowns across five silhouettes: A-Line, Ball Gown, Mermaid, Sheath, and Trumpet. This dashboard was built to help the business understand:

- Which silhouettes and fabrics drive the most revenue
- How orders are distributed across Nigerian states
- Which sales/order channels perform best
- How long orders take from order date to delivery (turnaround)
- How deposit structure (installment vs. full payment) relates to order value
- Client satisfaction (ratings) by consultant and style

## 📸 Dashboard Preview

### Silhouette Views

<h2 align="center">MERMAID</h2>
 <img width="1077" height="584" alt="mermaid" src="https://github.com/user-attachments/assets/7e6f813b-5254-40c3-bfc3-cb4cc8059479" /> 
<h2 align="center">A-LINE</h2>
 <img width="1082" height="602" alt="a line" src="https://github.com/user-attachments/assets/653b1942-40a7-44ef-9147-d10725f3758a" /> 
<h2 align="center">BALL GOWN</h2>
<img width="1082" height="599" alt="ball gown" src="https://github.com/user-attachments/assets/2be21041-8bab-4a4b-b101-eb511c1d9b3b" /> 
<h2 align="center">SHEATH</h2>
<img width="1076" height="610" alt="sheath" src="https://github.com/user-attachments/assets/e872ac21-ff63-4a14-93f2-37457b373717" /> 
<h2 align="center">TRUMPET</h2>
<img width="1079" height="605" alt="trumpet" src="https://github.com/user-attachments/assets/b2dcb7ad-96e9-4b55-8703-ac1e660a1ee1" /> 

## 🗂️ File Structure

| Sheet | Description |
|---|---|
| `veekee_signature_bridal_dataset` | Raw dataset — 215 bridal orders with 22 fields (client, state, style, fabric, pricing, payment plan, order channel, fittings, status, delivery date, consultant, rating, and calculated fields) |
| `Pivot A line`, `Pivot ball gown`, `Pivot mermaid`, `Pivot sheath`, `Pivot trumpet` | Pivot tables breaking down revenue and order count by state, fabric, order channel, and order status — one set per silhouette |
| `Mermaid`, `A Line`, `Ball Gown`, `Sheath`, `Trumpet` | Dashboard views — visual, silhouette-filtered summaries built from the pivot tables |

## 📊 Dataset Fields

| Field | Description |
|---|---|
| Order ID | Unique order identifier |
| Client Name | Customer name |
| State | Nigerian state of the client |
| Order Date / Delivery Date | Order placement and delivery dates |
| Style Name | Named gown design |
| Silhouette | A-Line, Ball Gown, Mermaid, Sheath, or Trumpet |
| Fabric | e.g. French Lace, Duchess Satin, Chantilly Lace, Tulle |
| Embellishment | e.g. Hand-beaded, Hand-embroidered, Pearl-encrusted |
| Customization | Made-to-Measure or Ready-to-Wear (Adjusted) |
| Price / Deposit Paid / Balance (NGN) | Order value and payment breakdown |
| Payment Plan | Full Payment or Installment |
| Order Channel | Walk-in, Instagram, Referral, Website, Bridal Fair |
| Fittings Completed | Number of fittings held |
| Order Status | e.g. Completed, Fitting Stage |
| Sales Consultant | Staff member handling the order |
| Client Rating | Post-delivery satisfaction score (1–5) |
| Turnaround Days | Days between order and delivery |

## 🛠️ Tools & Skills Used

- **Excel** — data cleaning, PivotTables, calculated fields (deposit-to-price ratio, turnaround days, completion rate), and dashboard design
- Manual data cleaning of a realistic, intentionally messy simulated dataset (missing values, inconsistent statuses, etc.)

## 🎨 Design

The dashboard follows Veekee James's real brand identity — a black-and-white base with a champagne gold accent — styled to resemble an authentic brand reporting tool rather than a generic template.

## 📈 Key Questions Explored

- Which silhouette generates the highest average order value?
- Which states and channels bring in the most revenue?
- How does payment plan choice affect deposit percentage?
- Where are the bottlenecks in order turnaround time?

## 📁 Data Note

This dataset is fully **synthetic** — created for portfolio purposes and not representative of Veekee James's actual sales data.

## 👤 Author

Built by Debby as part of a data analytics portfolio focused on SQL and Power BI/Excel dashboard projects.
