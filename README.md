
![GitHub Stars](https://img.shields.io/github/stars/egandavidpatrick-del/saubon-synogen?style=social)
![GitHub Issues](https://img.shields.io/github/issues/egandavidpatrick-del/saubon-synogen)
![License](https://img.shields.io/github/license/egandavidpatrick-del/saubon-synogen)
![Last Commit](https://img.shields.io/github/last-commit/egandavidpatrick-del/saubon-synogen)

#  Auto Document Issue Register Updater (Test Case)

<b>On-premises Auto Document Issue Register Updater for AEC organisations</b>

Auto Document Issue Register Updater has been designed to make completing a document issue easier and paractical.

Built with <b>as a Winforms C#,</b> application.

**Repository note**

The production application source code is private because Auto Document Issue Register Updater was developed as a test case. This repository intentionally contains the public technical documentation, screenshots and video demonstration rather than the proprietary application source.

## At a Glance

✔ Full-stack enterprise Winforms application
✔ Comprehensive documentation

# The problem

Completing a Document Issue register typically is a time consuming, tedious and error intensive task completed manually. This manual approach is how most organisations complete a Document Issue Register even today.

# 🧭 Auto Document Issue Register Updater
<h3>Complete a Document Issue Register in Seconds</h3> 

---


<i>Auto Document Issue Register Updater allows the user to complete a Document Issue Register the quick and easy way.</i>
<p align="left">
<img src="/images/image1.png" width=100%" alt="Auto Document Issue Updater Main User Interface">
</p>
💡 **Tip:** Click the hero image to view the full-size version.

---
<a id="enterprise-project"></a>

## 📑 Table of Contents

| 📖 Overview | 🛠️ Technical | 📚 Resources | 📈 About |
|:-----------:|:------------:|:------------:|:----------:|
| 🌐 [Platform Overview](#platform-overview) | ✨ [Key Features](#key-features) | 📦 [Contents](#repository-contents) | 📊 [Results](#results) |
 🛠️ [Tech Stack](#tech-stack) | 📚 [Documentation](#documentation) | 🚦 [Project Status](#project-status) |
| 💡 [Solution](#solution) |🏗️ [Enola Architecture](#enola-architecture) | 🖼️ [Screenshots](#screenshots-project-navigator--enola) | 👤 [Author](#author) |
| 👥 [Who Is It For](#who-is-it-for) | ⚙️ [Infrastructure](#operational-infrastructure) | 🔴 [Live Demo](#live-demo) | |
| 🚀 [Why It's Better](#why-is-it-better-than-traditional-workflows) | | | |


---
[Back to top](#enterprise-project)
<a id="platform-overview"></a>
## 🌐 Platform Overview
The Auto Document Issue Register Updater was originally developed for the AEC (Architecture, Engineering & Construction) industry, where organisations commonly update and maintain document issue registers.

[Back to top](#enterprise-project)
<a id="repository-contents"></a>
## 📦 Repository Contents

```text

/guide/user-guide
  Auto Document Issue Register Updater User Guide Version 1.0.(PDF)

/images/
  Auto Document Issue Register Updater screenshots

```

---
[Back to top](#enterprise-project)
<a id="documentation"></a>
## 📚 Documentation

This repository includes:

* User Guide
* Application Screenshots
---
[Back to top](#enterprise-project)
<a id="key-features"></a>
## ✨Key Features

- Auto-detects PDF drawings in selected directory - shows [ 10 Drawing(s) ] count in title bar
- Browse and link to Document Issue Register Excel file - Document Issue Register.xls
- Sets Document Issue Register Directory - P:\2019 Projects\...\_Standards\
- Sets Mechanical / Electrical Drawings Directory containing PDFs
- Auto-generates Document Issue Register PDF File Name - Document Issue Register 02-09-26.pdf
- Sets Document Issue Register Output PDF Directory
- Manages Recipients List - Client, Architect, Project Manager, Quantity Surveyor, Main Contractor, Mechanical Contractor, Electrical Contractor, Structural Engineer with Initials + Name fields
- Issue Date picker - 02-09-26
- Clear controls - Clear Recipients List, Clear Issue Register Fields, Clear Drawing Fields, Clear All Revisions Fields
- Open in Excel / Open Drawing Directory / Open Register Directory / View Register PDF
- Optional Contract Specification Documents with Revision - Electrical Contract Specification, Electrical Pricing Document, Mechanical Contract Specification, Mechanical Pricing Document
- Optional Additional Supporting Documentation with Revision - Design Risk Assessment, Preliminary Inspection Plan, BCAR M&E Submittal Schedule
- Issued For - Mandatory - Preliminary, Tender, Information, Scheme, Planning, Construction
- Document Delivery - Mandatory - Prints, Shared Folder, WeTransfer, Email
- PDF Output Sheet Size - A4 / A3
- One-click <b>Update Register</b> - updates Excel and generates PDF register

---
[Back to top](#enterprise-project)
<a id="tech-stack"></a>
## 🛠 Tech Stack

| Component          | Technology                        | Responsibility                                     |
| ------------------ | --------------------------------- | -------------------------------------------------- |
| Operator client    | C# WinForms                       | Auto Document Issue Register Client application    |


<h4>Integrated Development Environment</h4>

- Microsoft Visual Studio 2022
  
<h4>Packager-Deployment</h4>

- Microsoft Visual Studio 2022 Installer Projects
--- 
## Does your workflow fit the Project Navigator way of working?

If your company’s directory structure aligns with the sample directory structures defined above, the Project Navigator web application can be adapted and used to manage and coordinate the project directory workflow throughout your organisation.

--- 

[Back to top](#enterprise-project)
<a id="screenshots-project-navigator--enola"></a>
## 🖼️ Screenshots Auto Document Issue Register

<h3>Auto Document Issue Register - File Menu & Help Menu Options</h3>

<p align="left">
  <img src="./images/image2.png" width="49%" alt="alt="Auto Document Issue Register  - File Menu Options">
  <img src="./images/image3.png" width="49%" alt="Auto Document Issue Register - Help Menu Options">
</p>
<h3>About Box</h3>
<p align="left">
<img src="/images/image4.png" width="99%" alt="alt="Auto Document Issue Register - About Box">
</p>

💡 **Tip:** Click the image for the full-size version.

---

<a id="solution"></a>
[Back to top](#enterprise-project)
## 💡 Solution

The application solves the manual, time-consuming and error-prone process of completing a Document Issue Register for AEC projects.

How it works:

1. User selects the master Excel register - Document Issue Register.xls and its project directory
2. User points to a folder containing Mechanical or Electrical PDF drawings - app auto-detects [ 10 Drawing(s) ]
3. User confirms Recipients List - Client, Architect, PM, QS, Contractors with initials
4. User selects optional contract docs - Electrical / Mechanical Spec & Pricing with revision, plus supporting docs - Design Risk Assessment, Inspection Plan, BCAR Schedule
4. User sets mandatory issue data - Issue Date, Issued For - Information, Delivery Method - WeTransfer, Sheet Size - A4
6. Clicks <b>Update Register</b> - app automatically populates the Excel register with drawing names, revisions, recipients and generates the dated PDF Document Issue Register 02-09-26.pdf in the output directory

Replaces manual copying of drawing names, dates and recipient details with an automated WinForms C# workflow that ensures consistency, accuracy and auditability across document issues.

---
[Back to top](#enterprise-project)
<a id="who-is-it-for"></a>
## 👥 Who Is It For?

Completing a Document Issue Register can be done by the following people:

* Architects
* Engineers
* BIM Coordinators
* BIM Technicians
* CAD Technicians
* Document Controllers

---
[Back to top](#enterprise-project)
<a id="why-is-it-better-than-traditional-workflows"></a>
## 🚀 Why Is It Better Than Traditional Workflows?

Instead of relying on disconnected directories, emails, spreadsheets, and local copies, the platform provides a centralised network-accessible project catalogue where all users operate from the same shared directory structure and project data.

This reduces time spent searching for project directories, improves coordination across teams, and ensures construction information remains:

- Accessible
- Structured
- Consistently available
- Shared across all users

---
[Back to top](#enterprise-project)
<a id="operational-infrastructure"></a>
## ⚙️ Operational Infrastructure

**Development and Test Environment**

- Developed and tested on Windows 11 Pro box.

**Software Requirements**
- Microsoft Office 365 Installed on the users computer.

---
[Back to top](#enterprise-project)
<a id="live-demo"></a>
## 🔴 Live Demo

[Auto Document Issue Register Updater Demo](https://youtu.be/Vg66_TL9fbM)

---
[Back to top](#enterprise-project)
<a id="results"></a>
## 📊 Results

- Completes Document Issue Register in seconds vs hours manually
- Eliminates manual data entry for 10+ drawings - auto-detected from drawings directory
- Eliminates file naming errors - auto-generates Document Issue Register 02-09-26.pdf
- Eliminates directory navigation errors - fixed input/output paths to P:\2019 Projects\...01_Standards\
- Ensures consistent recipient information across all issues
- Ensures consistent revision control for contract specs - T1, X tracking
- Ensures mandatory fields are completed - Issued For, Document Delivery, Sheet Size
- Generates both Excel Document Issue Register.xls and PDF output simultaneously
- Provides one-click access to register, drawing folder, and PDF via Open buttons
- Standardises document issue workflow across AEC projects


[Back to top](#enterprise-project)
<a id="project-status"></a>
## 🚦 Project Status

✅ Completed Project  

---
[Back to top](#enterprise-project)
<a id="author"></a>
## 👤 Author

David Egan

Sole Software Developer, Systems Designer, and Solutions Architect for the Auto Document Issue Register Updater Application

<a href="https://www.linkedin.com/in/davidpatrickegan">LinkedIn</a> 
