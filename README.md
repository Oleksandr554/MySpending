#  MySpending

A modern and elegant personal finance web application that helps you track income, expenses, savings and investments — all in one beautiful interface.

---

##  About

**MySpending** is a clean and intuitive web app for managing your personal finances.  
Create an account, add transactions with categories and payment methods, and get real-time insights into your financial health.

All data is stored locally in the browser using `localStorage` (per user).

---

##  Features

### Authentication
- Login / Sign Up system
- User data isolated by email
- Persistent sessions via `localStorage`

### Dashboard
- Overview cards: **Income**, **Spending**, **Saving**, **Investments**
- Monthly spending bar chart (Jan–Dec)
- Transaction history with delete functionality
- Quick “Add Transaction” form with:
  - Amount & Note
  - Category selector (with icons)
  - Payment method (Check / Card / Cash)
  - Date picker

### Analytics
- Weekly spending line chart
- “My Pocket” donut chart (Income / Spent / Investments / Saving)
- Key stats:
  - Most expensive day
  - Favorite category
  - Total spending
  - Most profitable month
  - Most spending month
- Average Income (per year) & Average Outcome (per month)
- Smart financial tips
- Financial Health indicator

### Categories
- Beautiful grid of 19+ categories
- Click any category to see detailed transaction list and total

### Profile
- Upload / delete profile avatar
- Edit name, email, password and bio
- Changes are saved instantly

---

##  Design

Soft pastel color palette with modern UI:

| Card            | Color     |
|-----------------|-----------|
| Income          | `#B5C9D5` |
| Spending        | `#E3E1C5` |
| Saving          | `#D6BDD9` |
| Investments     | `#B5DBC5` |

Font: **Poppins**

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3** (custom styling)
- **Vanilla JavaScript**
- **localStorage** for data persistence
- **Canvas API** for donut chart
- **SVG** for weekly analytics chart

---
## Mock up

https://www.figma.com/design/jtvCmyZROOeYQb3YIfyd3p/Untitled?node-id=0-1&t=RZ7O85DJ65MMkX20-1
