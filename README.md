# Transport Issue Report

A web-based system that enables **passengers** and **drivers** of public buses and taxis to **report transportation-related issues** — such as unfair pricing, poor service, or accidents — in real-time. The system intelligently routes these reports to the relevant **Traffic Police**, **Bus Stations**, and **Transportation Office** for timely action.

---

## Key Features

**Report Issues**: Public users (no login required) can report:

- Overpriced fares
- Poor or unjust transportation services
- Gas station-related problems
- Traffic accidents

**Smart Alerts**: The system sends real-time alerts to:

- The nearest **Traffic Police**
- Associated **Bus Stations**
- The central **Transportation Office**

**Admin Dashboard**: A role-based dashboard for Transportation Office officials provides:

- Visual analytics of reported issues
- Filtering by issue type, location, and time
- Status tracking for resolved vs pending reports

**Role-Based Access**:

- **No Login**: Passengers and drivers can report anonymously
- **Login Required**: For Traffic Police, Bus Station Managers, and Transportation Office Staff

**Location Integration**:

- Optional location sharing to help pinpoint the issue origin
- Map view for admins to visualize reports geographically

**Notification Services**:

- Integrated with **SMS** and **Gmail**
- Automatic notifications to relevant officials or departments

---

## 🛠️ Tech Stack

        -------------------------------------------
        |    Layer     |      Technology          |
        |--------------|--------------------------|
        | Frontend     | React + Tailwind CSS     |
        | Backend      | Node.js + Express.js     |
        | Database     | MongoDB                  |
        | Third-Party  | Map APIs, Gmail, SMS API |
        -------------------------------------------

---

## User Roles

| Role                  | Authentication | Permissions                              |
| --------------------- | -------------- | ---------------------------------------- |
| Passengers & Drivers  | No Login       | Submit reports                           |
| Traffic Police        | Login          | View and manage assigned alerts          |
| Bus Station Managers  | Login          | Track reports for their location         |
| Transportation Office | Login          | Full dashboard access and analytics view |

---
