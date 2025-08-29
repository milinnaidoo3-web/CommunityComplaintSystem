# Community Complaint Logging System

## 📌 Overview

The **Community Complaint Logging System** is a web-based platform that allows residents to submit, track, and manage complaints about issues in their community — such as potholes, water outages, broken streetlights, waste management, noise complaints, and more.

The system also provides administrators (such as municipal workers or community leaders) with a dashboard to view, update, and resolve these complaints in a structured and efficient manner.

---

## ✅ Features

- 📝 Submit new complaints with description, category, image, and location.
- 📍 Pinpoint the location of the issue using an interactive map.
- 📸 Upload an image as evidence or reference.
- ✏️ Edit or delete complaints before they are resolved.
- 🔁 Track the status of complaints (Submitted, In Progress, Resolved, Closed).
- 👨‍💼 Admin dashboard to manage and update complaints.
- 🔔 Real-time updates and status notifications (optional).
- 🗃️ Store complaint data securely using a database.

---

## 🛠️ Technologies Used

- **Frontend:** Razor Pages, Bootstrap, jQuery
- **Backend:** ASP.NET Core (.NET 6+)
- **Database:** Entity Framework Core with SQL Server / SQLite
- **Maps:** Google Maps API for location selection
- **Image Uploads:** File storage via local directory or cloud (e.g., Azure/AWS)
- **Authentication:** ASP.NET Core Identity (optional)

---

## 📂 Project Structure

```plaintext
CommunityConnect/
│
├── Data/
│   └── AppDbContext.cs
│
├── Models/
│   └── Complaint.cs
│
├── Pages/
│   ├── Submit.cshtml
│   ├── Edit.cshtml
│   ├── Update.cshtml
│   ├── Profile.cshtml
│   └── Shared/
│
├── Services/
│   └── ComplaintService.cs
│
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── uploads/
│
├── Program.cs
├── appsettings.json
└── README.md
