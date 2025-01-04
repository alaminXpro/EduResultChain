# EduResultChain  

<p align="center">
    <a href="https://github.com/alaminXpro/EduResultChain/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/alaminXpro/EduResultChain/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/alaminXpro/EduResultChain" />
    </a>
    <a href="https://github.com/alaminXpro/EduResultChain/graphs/traffic">
      <img alt="Repo View" src="https://komarev.com/ghpvc/?username=alaminxpro&label=Profile%20views&color=0e75b6&style=flat" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/alaminXpro/EduResultChain?color=0088ff" />
    </a>
    <a href="https://github.com/alaminXpro/EduResultChain/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/alaminXpro/EduResultChain?color=0088ff" />
    </a>
</p>

![EduResultChain](https://repository-images.githubusercontent.com/911555839/abf47f4d-b8e1-4c6d-83ac-feda7e09d407)  

EduResultChain is an innovative blockchain-based Result and Education Management System (BREMS) designed to securely manage, store, and verify academic results, certificates, and mark sheets. This web application leverages modern web technologies and Ethereum blockchain to ensure transparency, scalability, and data integrity for educational institutions and students.

---

## Table of Contents

- [👥 Team Members](#team-members)
- [📄 Project Overview](#project-overview)
- [🛠️ Tech Stack](#tech-stack)
- [🎨 UI Design](#ui-design)
- [🚀 Project Features](#project-features)
- [🔗 API Endpoints](#api-endpoints)
- [📅 Milestones](#milestones)
- [🌐 Demo](#demo)
- [🤝 Contributing](#contributing)
- [📜 License](#license)
- [📞 Contact](#contact)

---

## **👥 Team Members**  

| Name                     | Roll Number   | Email                  | Role                                       |
|---------------------------|---------------|------------------------|--------------------------------------------|
| MD. AL AMIN              | 20220104154   | alamin.cse.20220104154@aust.edu     | Lead, Blockchain, Full-stack Developer     |
| Harique Rahman Jaif      | 20220104153   | harique.cse.20220104153@aust.edu    | Project Manager                            |
| Jamil Jim                | 20220104139   | ashadullah.cse.20220104139@aust.edu      | Front-end Developer                        |

---

## **📄 Project Overview**  

### **Project Title**  
**EduResultChain**  

### **Objective**  
To create a secure and efficient platform for managing academic records, where blockchain technology guarantees authenticity, immutability, and trust in the verification process.  

### **Target Audience**  
Educational institutions, students, and regulatory bodies requiring secure academic record management and verification.  

### **Key Features and Benefits**  
- **🔒 Security**: Blockchain ensures data integrity and prevents tampering.
- **🔍 Transparency**: All transactions are recorded on the blockchain, providing a transparent audit trail.
- **📈 Scalability**: Designed to handle large volumes of academic records.
- **🖥️ User-Friendly**: Intuitive interface for students, institutions, and administrators.

---

## **🛠️ Tech Stack**  

| Component       | Technology              |
|------------------|--------------------------|
| **Backend**     | Laravel   |
| **Frontend**    | Next.js                 |
| **Database**    | MySQL                   |
| **Blockchain**  | Ethereum (Smart Contracts) |
| **Rendering**   | Server-Side Rendering (SSR) |

---

## **🎨 UI Design**  

We are currently designing the user interface using Figma. You can view our mock UI [here](https://www.canva.com/design/DAGbN0-R5Mk/X8LfC9UECSmnzG8pXztfpw/view?mode=prototype).  

---

## **🚀 Project Features**  

### **Landing Page**  
- Home Page  
- About Us  
- Contact Us  
- Privacy Policy  
- Terms & Conditions  
- Result Page  
- Result Verification  
- Notice Board  
- Frequently Asked Questions  
- Apply for Result Revalidation  
- Basic Result Statistics  

### **Dashboard Features**  

#### **Student**  
- View Result & Download web version marksheet  
- Download Certificate (Grade Sheet)  
- Download Marksheet  
- Apply for Result Revalidation (Payment Needed)  
- Check Result Status on Blockchain  

#### **Institution**  
- Data Entry of Students  
- Add, Update, Delete Student and Result Entries  
- Upload Results to Blockchain  
- Handle Result Revalidation Requests from Students  
- Access Institution-specific Result Statistics  

#### **Admin**  
- Approve or Reject Institution Verification Requests  
- Manage Institution Records  
- Schedule Result Publications  
- Blockchain Integration for Result Verification  

---

## **🔗 API Endpoints**  

| Method | Endpoint                     | Description                            |
|--------|-------------------------------|----------------------------------------|
| GET    | `/api/v1/results/:id`         | Fetch a specific result by ID          |
| GET    | `/api/v1/results`             | Fetch all results                      |
| POST   | `/api/v1/institution/student` | Add a new student                      |
| PUT    | `/api/v1/institution/student/:id` | Update an existing student entry       |
| DELETE | `/api/v1/institution/student/:id` | Remove a student                       |
| POST   | `/api/v1/institution/result`  | Add a new result                       |
| PUT    | `/api/v1/institution/result/:id` | Update an existing result entry        |
| DELETE | `/api/v1/institution/result/:id` | Remove a result                        |
| POST   | `/api/v1/auth/register`       | Register a new user                    |
| POST   | `/api/v1/auth/login`          | User login                             |
| GET    | `/api/v1/auth/logout`         | User logout                            |
| GET    | `/api/v1/auth/profile`        | Fetch user profile                     |
| POST   | `/api/v1/revalidation/apply`  | Apply for result revalidation          |
| GET    | `/api/v1/revalidation/status/:id` | Check revalidation status by ID       |

---

## **📅 Milestones**  

### **Milestone 1**  
- Set up the project environment and initialize the tech stack.  
- Design mock UI for landing pages and dashboard using Figma.  
- Create database schemas for students, results, and institutions.  

### **Milestone 2**  
- Implement user authentication (registration & login).  
- Develop CRUD operations for student and result management.  
- Integrate Ethereum blockchain for certificate and result verification.  

### **Milestone 3**  
- Complete result statistics and analysis features.  
- Finalize UI/UX with responsive design.  
- Deploy the web application and conduct testing for scalability and security.  

---

## **🌐 Demo**  
Check out our live demo: [eduresultchain.vercel.app](https://eduresultchain.vercel.app/)

Experience the features and functionalities of our blockchain-based result management system firsthand.

---

## **🤝 Contributing**  
We welcome contributions from developers and researchers! Please fork the repository and submit a pull request for review.  
<a href="https://github.com/alaminXpro/EduResultChain/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=alaminXpro/EduResultChain-client" />
</a>

---

## **📜 License**  
This project is licensed under the [GPL License](LICENSE).  

---

## **📞 Contact**  

For further inquiries or feedback, please contact:  
- **Lead Developer:** [MD. AL AMIN](https://www.linkedin.com/in/alaminxpro/)  
- **Project Manager:** [Harique Rahman Jaif](mailto:harique.cse.20220104153@aust.edu)  
- **Front-end Developer:** [Jamil Jim](mailto:ashadullah.cse.20220104139@aust.edu)
