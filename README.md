# ⚽ Football Tournament Registration System

## 📌 Overview
This project is an automated registration system built using Airtable and Make (Integromat). It validates users before allowing registration and provides real-time tracking via a dashboard.

## 🚀 Features

- ✅ Validates users against Members database
- ❌ Blocks non-members from registering
- 🔁 Prevents duplicate registrations
- 📊 Dashboard with real-time insights
- 📩 Automated email notifications

## 🧠 Workflow

1. User submits registration form
2. Webhook receives data
3. System checks:
   - If user exists in Members table
4. Router logic:
   - ✅ Valid → Register user
   - ❌ Invalid → Reject user
5. Email is sent based on result
6. Data stored in Airtable
7. Dashboard updates automatically

## 🛠 Tools Used

- Airtable (Database + Dashboard)
- Make (Automation)
- Gmail (Email notifications)

## 📊 Dashboard Features

- Total Attempts
- Valid Registrations
- Invalid Attempts
- Status Distribution Chart
- Detailed Records Table

## 💡 Key Learnings

- Handling webhook array data (fields[])
- Using label-based extraction instead of index
- Building no-code automation workflows
- Designing user-friendly dashboards

## 📎 Author

Shamsiya Begum
