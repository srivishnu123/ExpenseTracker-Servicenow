# 🏠 Family Expenses Management System (ServiceNow)

## 📘 Project Overview

**Family Expenses Management** is a ServiceNow-based project that automates the process of recording, tracking, and calculating household expenditures.
The system enables family members to efficiently log daily expenses, which are then automatically aggregated into a main **Family Expenses** table. This provides a **centralized, transparent, and organized way to monitor financial activity** within the household.

The solution leverages **ServiceNow’s table relationships, business rules, and form configurations** to ensure smooth data integration and automation.

---

## 🎯 Objectives

* Simplify household expense tracking.
* Automate calculation and aggregation of daily expenses.
* Enable dynamic linking between **Family Expenses** and **Daily Expenses** tables.
* Maintain an organized digital record of all expenses using ServiceNow’s features.

---

## ⚙️ Key Features

### 🧾 1. Table Creation

* **Family Expenses Table** — Stores aggregated family expense data.

  * Columns: Number, Date, Amount, Expense Details
  * Number field configured with **Auto-numbering**
* **Daily Expenses Table** — Stores each family member’s daily expenditure.

  * Columns: Number, Date, Expense, Family Member Name, Comments

### 🔄 2. Automated Relationships

* A **relationship** is established between *Family Expenses* and *Daily Expenses* tables.
* Enables synchronized updates — any change in Daily Expenses reflects automatically in Family Expenses.

### 🧠 3. Business Rule Automation

* Business Rules ensure real-time updates of total family expenses whenever a daily expense is added or updated.

### 🧩 4. Form Configuration

* **Family Expenses Form**:

  * *Number* field is **Read-Only**.
  * *Date* and *Amount* fields are **Mandatory**.
* **Daily Expenses Form**:

  * *Number* field is **Read-Only**.
  * *Date* and *Family Member Name* fields are **Mandatory**.
  * Drag-and-drop UI customization enabled for user-friendly layouts.

### 🔗 5. Related List Configuration

* Added *Daily Expenses* as a **Related List** under *Family Expenses* to provide a quick overview of all linked daily records.

---

## 🧰 Tools & Technologies

* **Platform:** ServiceNow
* **Scripting:** GlideRecord (JavaScript)
* **Modules Used:**

  * Tables
  * Forms
  * Relationships
  * Business Rules
  * Number Maintenance
  * Form Designer

---

## 🧪 Implementation Workflow

1. Create a Local Update Set → *Family Expenses*
2. Create Tables → *Family Expenses* & *Daily Expenses*
3. Define Columns/Fields with appropriate types
4. Enable Auto-Numbering for both tables
5. Configure Forms (Read-only & mandatory fields)
6. Set Relationship between tables
7. Add Business Rules for automatic expense updates
8. Configure Related List to display linked records
9. Test the functionality by adding and modifying expense entries

---

## 📈 Benefits

* Eliminates manual expense tracking.
* Centralized management of all family expenditures.
* Ensures data accuracy through automation.
* Provides transparency and accountability within the household.
* Scalable — can be extended for monthly or yearly reporting.

---

## 🧾 Conclusion

The **Family Expenses Management System** built on **ServiceNow** offers a streamlined, automated, and reliable approach to tracking and managing household finances.
By combining relational tables, automation scripts, and user-friendly forms, it demonstrates the power of ServiceNow as a platform for custom business process applications.


