# 🏫 MuniSGS – Student Grievance System

**MuniSGS** (Muni Student Grievance System) is a web-based application designed to streamline the process of grievance reporting, tracking, and resolution for students at **Muni University**. It addresses the limitations of the traditional manual system by offering a more secure, anonymous, and accessible platform where students can raise their concerns and receive timely responses from university authorities.

> 🎓 *A Final Year Project by an IT student at Muni University, Arua District – "Design and Development of a Student Grievance System (MuniSGS)"*


## 📌 Problem Statement

Currently, students at Muni University report grievances by physically visiting the counselor's office or making direct calls. These traditional methods present several challenges:

* **Lack of anonymity**, discouraging students from reporting sensitive issues.
* **Limited accessibility**, especially for students who are remote or shy.
* **Inefficient tracking** and delayed resolution of grievances.
* **Underreporting** due to fear of retaliation or stigma.


## 🎯 Project Objectives

* To design and develop a user-friendly, secure, and anonymous web-based system for reporting student grievances.
* To ensure timely response and proper tracking of reported issues.
* To improve student welfare, safety, and satisfaction.
* To generate reports and analytics to help management make informed decisions.



## ✨ Key Features

* ✅ **Anonymous Grievance Submission**
* 🗂️ **Attach Supporting Documents**
* 🔒 **Secure Login for Students and Admins**
* 🧑‍💼 **Admin Dashboard for Managing Grievances**
* 🧠 **AI-Powered Assistant** to suggest responses and categorize grievances
* 🕓 **Grievance Tracking and Status Updates**
* 📊 **Reports & Analytics Dashboard**
* 📱 **Mobile-Responsive UI**
* 📨 **Email Notifications** *(optional/disabled by default for privacy)*


## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Backend:** PHP (Laravel Framework)
* **Database:** MySQL
* **AI/Chatbot:** Rule-based support system for now, expandable to integrate GPT-based models.
* **Hosting:** Designed for deployment on Apache/Nginx environments


## 📷 Screenshots

![Screenshot (217)](https://github.com/user-attachments/assets/57c3c365-5461-47da-b434-788da5a55f6f)




## 🚀 Installation Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/MuniSGS.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd MuniSGS
   ```

3. **Set up the database:**

   * Create a MySQL database (e.g., `munisgs_db`)
   * Import the SQL dump file from `/database/munisgs.sql` (if provided)

4. **Configure environment variables:**

   * Copy `.env.example` to `.env`
   * Update database credentials and settings

5. **Install dependencies (Laravel):**

   ```bash
   composer install
   php artisan key:generate
   php artisan migrate
   ```

6. **Run the application locally:**

   ```bash
   php artisan serve
   ```


## 👥 User Roles

* **Student**

  * Register/Login
  * Submit grievances anonymously or with identity
  * Attach files
  * Track grievance status

* **Admin/Counselor**

  * View and respond to grievances
  * Assign status (Pending, In Progress, Resolved)
  * Generate reports
  * View trends in grievances



## 🤖 AI Assistant Module (Planned/Prototype Stage)

* **For Students:** Offers basic support, resources, and counseling tips.
* **For Admins:** Suggests response templates or classifications using predefined rules or NLP in future versions.



## 🧪 Project Status

✅ Core Modules Implemented: Submission, Authentication, Grievance Management
⚙️ AI Assistant: Partially implemented
🚧 Email Notification: Optional
📲 UI/UX Enhancements: In Progress



## 📚 Academic Relevance

This project is part of the final year coursework for the **Bachelor of Science in Information Technology (ITM 3132: Project Proposal Development)** at **Muni University**. It showcases practical implementation of system development skills with a focus on solving real-world problems affecting student welfare.



## 🤝 Contributions

Contributions are welcome! If you'd like to contribute:

1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request


## 📄 License

This project is licensed under the MIT License.



## 📬 Contact

**Onya\_I.TGuy**
Email: onyabukoisaac@gmail.com 
GitHub: Onyabuko (https://github.com/onyabuko)

