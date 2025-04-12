# Uber-Analysis-Proj
Learning and Implementing Power Bi to create a Dashboard.

# 🚗 Uber Bookings Analysis Dashboard

This is an interactive Power BI dashboard that visualizes Uber bookings data to uncover trends, highlight key performance indicators (KPIs), and allow users to drill down into trip details across time, location, and vehicle type.

---

## 📌 What This Dashboard Does

This dashboard tells the story of Uber’s bookings through data. It helps answer questions like:
- How are bookings performing over time?
- Which vehicle categories bring in the most revenue?
- What are the peak booking hours?
- How do payment methods and pickup points affect performance?

It's designed to be:
- Visually clean
- Easy to interact with
- Insightful at both high and detailed levels

---

## 🧠 Key Features & Structure

### 1. 🌐 Overview Page
This is the **main summary page**. It displays:
- **KPI Cards**: Total Bookings, Total Revenue, and Total Distance
- **Booking Trends** over time (line chart)
- **Revenue by Vehicle Category** (bar chart)
- **Top Pickup Points** (map or stacked bar)

This page gives a quick glance at overall performance.

---

### 2. ⏱️ Time Breakdown Page
Focuses on **when** bookings happen. It includes:
- **Hourly Booking Patterns**
- **Bookings by Day of the Week**
- **Monthly Revenue Trends**
- Drill-down capabilities to zoom into specific timeframes

Great for understanding *when* people are booking rides.

---

### 3. 🧾 Details Page
Dives deeper into trip details:
- **Payment Method Analysis**
- **Distance Bins (Short, Medium, Long trips)**
- **Trip Type Comparison** (Shared vs. Solo rides)
- **Filters**: Location, time, vehicle, payment

This page helps stakeholders filter and find exact patterns that matter to them.

---

## 🔁 How Everything is Connected

- **Slicers & Filters** sync across pages, so when you select a date range or vehicle type on one page, it reflects across all views.
- **Drill-through Buttons** let users click on a summary item (e.g., a bar showing "UberX") and jump to a detailed page that breaks that segment down further.
- **Dynamic Measures** using DAX allow switching between metrics (Revenue, Distance, Bookings) in charts using a dropdown — all built with a custom *Measure Selector*.

---

## 🛠️ Technologies Used
- **Power BI**: For data visualization and interactivity
- **DAX (Data Analysis Expressions)**: For dynamic metrics and calculated fields
- **Excel**: Cleaned and structured the Uber dataset before import

---

## 📸 Screenshots

### 📊 Overview Page
![overview](https://github.com/user-attachments/assets/e7232547-7b7f-4aa1-ade0-665d9021cb29)


### ⏱️ Time Analysis Page
![time](https://github.com/user-attachments/assets/10295289-14b2-423d-b45c-c85b15eca1ff)


### 📋 Details Page
![details](https://github.com/user-attachments/assets/9220f8ad-6274-44bd-874a-0151c9b35766)


---

## 💬 Why I Built This

I wanted to create a dashboard that’s not only visually engaging but also useful to someone making business decisions at Uber. Every visual tells a story. It’s easy to use, dynamic, and designed to handle multiple user perspectives — whether you’re a manager, analyst, or investor.

---

## 🤖 Future Ideas
- Add predictive trends using ML models
- Connect live data via an API
- Build a web version with Power BI Embedded

---

Thanks for checking it out!
