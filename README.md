<div align="center">

# 🎬 MOVIE TICKET BOOKING

### 🍿 A Smart Movie Ticket Booking Workflow Built with Pega

<p>
  <img src="https://img.shields.io/badge/PEGA-Platform-0073B7?style=for-the-badge&logo=pega&logoColor=white">
  <img src="https://img.shields.io/badge/CSE-AI%20%26%20ML-6C63FF?style=for-the-badge">
  <img src="https://img.shields.io/badge/PROJECT-NIP-E63946?style=for-the-badge">
  <img src="https://img.shields.io/badge/STATUS-Completed-2A9D8F?style=for-the-badge">
</p>

### 🎟️ Book Your Movie • 💺 Select Seats • 💰 Calculate Cost • ✅ Confirm

<br>

**👨‍💻 Developed by DILON P G**

**🏫 VSB College of Engineering**

</div>

---

## 🎞️ Project Preview

> 🎬 **Movie Ticket Booking** is a Pega-based case management application designed to automate the complete movie ticket booking process.

The application manages a booking request from **initial submission → seat availability → cost calculation → customer confirmation → ticket processing → notification → resolution**.

---

# 🌟 What Makes This Project Special?

<table>
<tr>
<td align="center">🎬<br><b>Movie Selection</b><br><sub>Select movie & show</sub></td>
<td align="center">💺<br><b>Seat Availability</b><br><sub>Check available seats</sub></td>
<td align="center">💰<br><b>Cost Calculation</b><br><sub>Automatic calculation</sub></td>
</tr>
<tr>
<td align="center">✅<br><b>Confirmation</b><br><sub>Customer approval</sub></td>
<td align="center">🎫<br><b>Ticket Processing</b><br><sub>Generate booking</sub></td>
<td align="center">📩<br><b>Notification</b><br><sub>Booking confirmation</sub></td>
</tr>
</table>

---

# 📋 Project Information

| 🔖 Details          | 📌 Information                              |
| ------------------- | -------------------------------------------  |
| 🎬 **Project**      | Movie Ticket Booking                        |
| ⚙️ **Platform**     | Pega                                        |
| 📂 **Application**  | `NIP-MovieTicket-DILONPG`                   |
| 📝 **Case Type**    | `Ticketing Management`                      |
| 👨‍💻 **Developer**    | DILON P G                                   |
| 🎓 **Course**       | CSE (AI & ML)                               |
| 🏫 **College**      | VSB College of Engineering                  |
| 📍 **State**        | Tamil Nadu                                  |
| 👤 **Operator**     | DILON P G                                   |
| 🆔 **Operator ID**  | `DilonPG@uplus`                             |

---

# 🔄 Application Workflow

```text
        🎬 MOVIE TICKET BOOKING
                  │
                  ▼
        ┌──────────────────┐
        │ 📝 Request       │
        │    Booking       │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ ⚙️ Booking       │
        │    Processing    │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ ✅ Confirmation  │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ 🏁 Resolved      │
        └──────────────────┘
```

### 🟦 Stage 1 — Request Booking

Customer enters:

* 🎬 Movie Name
* 📅 Show Date
* 🕐 Show Time
* 🎟️ Number of Tickets

### 🟨 Stage 2 — Booking Processing

System performs:

* 💺 Seat availability check
* 💰 Total cost calculation
* 🎫 Ticket processing
* 🚦 Show-type routing

### 🟩 Stage 3 — Confirmation

Customer reviews the booking and:

> ✅ Confirms
> ❌ Cancels

### 🟥 Stage 4 — Resolved

The completed booking is resolved and confirmation details are provided.

---

# 🎟️ User Stories

<details>
<summary>📝 <b>US-001 — Submit Movie Ticket Request</b></summary>

<br>

Customer provides:

* Movie Name
* Show Date
* Show Time
* Number of Tickets

✅ Required-field validation is applied.

</details>

<details>
<summary>💺 <b>US-002 — Check Show Availability</b></summary>

<br>

The system checks:

* Seat Availability Status
* Available Seats Count

🟢 Booking continues when seats are available.

🔴 Booking cannot proceed when seats are unavailable.

</details>

<details>
<summary>💰 <b>US-003 — Calculate Booking Cost</b></summary>

<br>

### Automatic Calculation

```text
Total Cost
     =
Ticket Price × Number of Tickets
```

### Example

```text
🎟️ Ticket Price     = ₹200
🎫 Number of Tickets = 3
────────────────────────
💰 Total Cost        = ₹600
```

</details>

<details>
<summary>✅ <b>US-004 — Confirm Booking Request</b></summary>

<br>

Customer can review the booking and:

* ✅ Confirm
* ❌ Cancel
* 📌 Update Booking Status

</details>

<details>
<summary>🎬 <b>US-005 — Maintain Movie and Show Data</b></summary>

<br>

### Movie / Show Information

| Property         | Description            |
| ---------------- | ---------------------- |
| 🎬 Movie Name    | Selected movie         |
| 🎭 Genre         | Movie category         |
| 📅 Show Date     | Date of show           |
| 🕐 Show Time     | Time of show           |
| 💺 Seat Capacity | Total seating capacity |

</details>

<details>
<summary>🔎 <b>US-006 — Review Booking Details</b></summary>

<br>

Confirmation screen displays:

* 🎬 Movie Name
* 🕐 Show Timing
* 🎟️ Number of Tickets
* 💰 Total Cost

</details>

<details>
<summary>🎫 <b>US-007 — Process Ticket Booking</b></summary>

<br>

Captures:

* 💺 Seat Numbers
* 🆔 Ticket ID
* ✅ Booking Confirmation Status

</details>

<details>
<summary>📩 <b>US-008 — Notify Booking Confirmation</b></summary>

<br>

Booking confirmation contains:

* 🎬 Movie / Show details
* 💺 Seat information
* 💰 Cost details
* 🎟️ Ticket information

</details>

<details>
<summary>⏱️ <b>US-009 — Define Booking SLA</b></summary>

<br>

| SLA Configuration | Value              |
| ----------------- | ------------------ |
| 🎯 Goal           | **1 Day**          |
| 🚨 Deadline       | **2 Days**         |
| 📈 Breach Action  | Priority increases |

</details>

<details>
<summary>🚦 <b>US-010 — Route by Show Type</b></summary>

<br>

| Show Type   | Work Queue          |
| ----------- | ------------------- |
| 🟣 Premium  | `PremiumShowQueue`  |
| 🔵 Standard | `StandardShowQueue` |

</details>

---

# 💰 Smart Cost Calculation

<div align="center">

### 🎟️ Ticket Price

⬇️

### ✖️

⬇️

### 🎫 Number of Tickets

⬇️

### 🟢 TOTAL COST

</div>

```text
Total Cost = Ticket Price × Number of Tickets
```

---

# 💺 Seat Availability

```text
             💺 CHECK SEATS
                   │
          ┌────────┴────────┐
          │                 │
          ▼                 ▼
      🟢 AVAILABLE      🔴 UNAVAILABLE
          │                 │
          ▼                 ▼
    Continue Booking     Stop Booking
```

---

# 🚦 Intelligent Queue Routing

```text
                    🎭 SHOW TYPE
                        │
              ┌─────────┴─────────┐
              │                   │
              ▼                   ▼
        🟣 PREMIUM             🔵 STANDARD
              │                   │
              ▼                   ▼
    PremiumShowQueue      StandardShowQueue
```

---

# ⏱️ SLA Management

<div align="center">

|  🎯 Goal  | 🚨 Deadline |    📈 Breach   |
| :-------: | :---------: | :------------: |
| **1 Day** |  **2 Days** | **Priority ↑** |

</div>

The SLA ensures that booking requests are handled within the expected processing time.

---

# 🧩 Data Model

### 🎬 Movie / Show

```text
Movie Name
Genre
Show Date
Show Time
Seat Capacity
```

### 🎟️ Booking

```text
Number of Tickets
Ticket Price
Total Cost
Seat Numbers
Ticket ID
Booking Status
Booking Confirmation Status
Show Type
```

---

# ⚙️ Pega Concepts Used

| 🧠 Pega Concept   | 🔧 Implementation                              |
| ----------------- | ---------------------------------------------- |
| 📂 Case Type      | Ticketing Management                           |
| 🔄 Stages         | Request → Processing → Confirmation → Resolved |
| 📦 Data Objects   | Movie / Show, Booking                          |
| 📝 Fields         | Movie, Show & Booking properties               |
| 💰 Business Logic | Total Cost calculation                         |
| 💺 Availability   | Seat availability check                        |
| 🚦 Routing        | Premium / Standard queues                      |
| 👤 Persona        | Customer                                       |
| 📥 Work Queues    | PremiumShowQueue / StandardShowQueue           |
| ⏱️ SLA            | 1-day goal / 2-day deadline                    |
| 📩 Correspondence | Booking confirmation                           |
| ✅ Approval        | Customer confirmation                          |
| 🧪 Validation     | Required-field validation                      |

---

# 🧪 Testing

### 🟢 Successful Booking

```text
🎬 Select Movie
      ↓
📅 Select Show
      ↓
🎟️ Enter Tickets
      ↓
💺 Check Availability
      ↓
💰 Calculate Cost
      ↓
🔎 Review Details
      ↓
✅ Confirm
      ↓
🎫 Process Ticket
      ↓
📩 Send Confirmation
      ↓
🏁 RESOLVED
```

### 🔴 Invalid Booking

```text
❌ Missing Required Information
             ↓
       🧪 Validation
             ↓
       ⚠️ Show Error
             ↓
      ✏️ Correct Details
```

### 💺 No Seats Available

```text
💺 Seat Check
     ↓
🔴 No Seats
     ↓
❌ Booking Cannot Proceed
```

---

# 📸 Project Screenshots

> 📌 Add your actual Pega screenshots inside a `screenshots` folder.

|  #  | User Story | Screenshot           |
| :-: | ---------- | -------------------- |
|  01 | US-001     | 📝 Booking Request   |
|  02 | US-002     | 💺 Seat Availability |
|  03 | US-003     | 💰 Cost Calculation  |
|  04 | US-004     | ✅ Confirmation       |
|  05 | US-005     | 🎬 Movie / Show Data |
|  06 | US-006     | 🔎 Review Details    |
|  07 | US-007     | 🎫 Ticket Processing |
|  08 | US-008     | 📩 Notification      |
|  09 | US-009     | ⏱️ SLA               |
|  10 | US-010     | 🚦 Queue Routing     |

---

# 📁 Repository Structure

```text
🎬 Movie-Ticket-Booking/
│
├── 📄 README.md
│
├── 📸 screenshots/
│   ├── 🖼️ US-001.png
│   ├── 🖼️ US-002.png
│   ├── 🖼️ US-003.png
│   ├── 🖼️ US-004.png
│   ├── 🖼️ US-005.png
│   ├── 🖼️ US-006.png
│   ├── 🖼️ US-007.png
│   ├── 🖼️ US-008.png
│   ├── 🖼️ US-009.png
│   └── 🖼️ US-010.png
│
└── 📚 documentation/
    └── 📄 MovieTicket_DILON_P_G.docx
```

---

# 🚀 How to Demonstrate

```text
1️⃣ Login to Pega
        ↓
2️⃣ Open Ticketing Management
        ↓
3️⃣ Create Booking Case
        ↓
4️⃣ Enter Movie Details
        ↓
5️⃣ Check Availability
        ↓
6️⃣ Calculate Total Cost
        ↓
7️⃣ Review Booking
        ↓
8️⃣ Confirm Booking
        ↓
9️⃣ Process Ticket
        ↓
🔟 Resolve Case
```

---

# 🌐 Pega Application

<div align="center">

### 🔗 Access Pega Application

**https://xnq1lhls.pegacea.net/prweb**

🔐 *Valid Pega credentials and permissions may be required.*

</div>

---

# 🌱 Future Enhancements

🚀 Planned improvements could include:

* 💳 Online payment integration
* 💺 Interactive seat selection
* 📱 Mobile-friendly interface
* 🎟️ QR-code ticket generation
* 📧 Email & SMS notifications
* ⭐ Movie ratings and reviews
* 🔍 Movie search & filtering
* 📊 Booking analytics dashboard
* 🏢 Multiple theatre support
* 👤 Customer account management

---

# 🎓 Learning Outcomes

Through this project, the following Pega concepts were practiced:

```text
📂 Case Management
      ↓
🔄 Stages & Workflow
      ↓
📦 Data Modeling
      ↓
🧠 Business Rules
      ↓
💰 Calculations
      ↓
🚦 Routing
      ↓
📥 Work Queues
      ↓
⏱️ SLA
      ↓
📩 Correspondence
      ↓
✅ Approval
      ↓
🧪 Validation
```

---

# 👨‍💻 Developer

<div align="center">

## 🎬 DILON P G

### CSE (AI & ML)

🏫 **VSB College of Engineering**

📍 **Tamil Nadu, India**

</div>

---

# ⭐ Support the Project

If you find this project useful:

⭐ **Star the repository**

🍴 **Fork the repository**

📢 **Share the project**

---

<div align="center">

# 🍿 THANK YOU FOR VISITING! 🍿

### 🎬 Movie Ticket Booking

**Built with ❤️ using Pega**

<br>

🎟️ **BOOK YOUR MOVIE • ENJOY THE SHOW!** 🎟️

</div>

---

## ⚠️ Academic Verification

Before submitting this repository, verify that the following match your actual Pega application:

* ✅ Exact rule names
* ✅ Rule types
* ✅ Personas
* ✅ Work queues
* ✅ Routing conditions
* ✅ SLA configuration
* ✅ Screenshots
* ✅ Application configuration

Only publish information and screenshots that are actually present in your Pega project.
