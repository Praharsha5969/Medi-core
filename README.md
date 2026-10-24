🏥 Medi-Core — Smart Healthcare Platform

**Helping doctors access patient medical history faster for more informed healthcare decisions.**

🌐 **Live Demo:** [Try Medi-Core](https://remix-medi-hospital-personal-healthcare-plat-r6bz-708162273988.asia-south1.run.app/)

💻 **GitHub Repository:** [Praharsha5969/Medi-core](https://github.com/Praharsha5969/Medi-core)

---

📌 About Medi-Core

Medi-Core is a smart healthcare platform designed to help doctors access a patient's previous health problems, medical history, prescriptions, and vital health information in one place.

The idea behind this project came from a real-world challenge in healthcare: doctors may have limited time to understand a patient's medical background, especially when previous medical records are scattered across different hospitals, documents, or systems.

Medi-Core aims to make relevant patient information easier to access and organize, helping healthcare professionals understand a patient's history before evaluating their current health concerns.

The platform also provides dedicated interfaces for patients, doctors, hospital administrators, and emergency response staff.

❗ Problem Statement

Doctors often face challenges when treating patients whose previous medical history is unavailable, incomplete, or difficult to access. Understanding a patient's past illnesses, existing medical conditions, allergies, medications, and previous treatments is important when evaluating a new health problem.

When this information is scattered across multiple records or healthcare facilities, doctors may need additional time to collect and review it. This can delay the assessment process and make it harder to identify relevant medical history, particularly during emergencies.

Patients may also struggle to remember or communicate all their previous health problems and treatments accurately.

**Medi-Core aims to address this problem by providing a centralized digital platform where relevant patient health information can be organized and accessed efficiently by authorized healthcare professionals.**

The goal is to reduce the time spent searching for previous medical information and help doctors make better-informed clinical assessments.

💡 Proposed Solution

Medi-Core provides a unified healthcare interface that brings important patient information together in one place.

The proposed solution includes:

- Maintaining organized patient medical histories.
- Providing access to previous illnesses, treatments, and prescriptions.
- Displaying relevant patient health metrics through a dashboard.
- Supporting access to patient information for authorized healthcare professionals.
- Providing an emergency response interface to help staff retrieve relevant medical information.
- Supporting appointment and hospital management workflows.

By improving access to existing information, Medi-Core aims to support doctors in understanding a patient's medical background more efficiently.

 🎯 Objectives

- Reduce the difficulty of retrieving previous patient health records.
- Make important medical information easier for doctors to review.
- Improve the organization of patient medical history.
- Support better communication between patients and healthcare professionals.
- Help authorized emergency staff access relevant patient information.
- Provide a unified interface for essential healthcare management activities.

✨ Key Features

👤 Patient Portal
- Patient profile and health information.
- Medical history and previous health records.
- Prescription and medication information.
- Appointment-related information.

🩺 Doctor Portal
- Dedicated doctor interface.
- Support for reviewing available patient information.
- Access to relevant medical history and prescription information, where configured.

❤️ Health Monitoring Dashboard
- Display of vital health metrics, such as heart rate, blood pressure, oxygen saturation, and temperature.
- Organized visualization of available health information.
- ECG-style visual interface.

🚨 Emergency Response Portal
- Emergency patient intake interface.
- Support for linking emergency records with patient information.
- Access to relevant medical background where available and authorized.

🏥 Hospital Management
- Patient admission and discharge workflows.
- Ward and bed management interface.
- Hospital-related information.

📅 Appointments and Prescriptions
- Support for appointment management.
- Prescription and medication schedule interfaces.
- Organized presentation of healthcare information.

🔍 Search and Audit Logs
- Search interface for navigating information.
- Audit-log interface for reviewing recorded activities.

*Actual functionality depends on the application's implementation and configuration.*

🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Building the user interface |
| TypeScript | Type-safe application development |
| Vite | Development server and build tooling |
| Tailwind CSS | Interface styling |
| Lucide React | Icons |
| Firebase Firestore | Cloud data integration |
| Supabase | Additional data integration |
| Google Gemini API | AI integration capability |

🚀 Getting Started

Prerequisites

- Node.js
- npm or Bun
- Git

1. Clone the repository

```bash
git clone https://github.com/Praharsha5969/Medi-core.git
cd Medi-core
```

2. Install dependencies

```bash
npm install
```

3. Configure environment variables

Create a local `.env` file using the project's `.env.example` file, if available.

Configure the required credentials for the services enabled in your application, including Firebase, Supabase, or Gemini where applicable.

Never commit private API keys or credentials to GitHub.

4. Start the development server

```bash
npm run dev
```

Open the local URL displayed in the terminal.

5. Build the application

```bash
npm run build
```

🔮 Future Scope

Medi-Core could be extended with the following features:

- **Unified Medical History:** Support secure access to patient records from multiple healthcare facilities.
- **AI-Assisted Medical Summaries:** Generate summaries of previous illnesses, treatments, and medications for doctors to review.
- **Medical Allergy Alerts:** Highlight documented allergies and medication-related warnings.
- **Emergency Access:** Provide secure, audited access to essential patient information during emergencies.
- **Health Trend Analysis:** Display changes in vital signs and other recorded health measurements over time.
- **Healthcare Interoperability:** Integrate with appropriate healthcare data standards and external systems.
- **Improved Privacy and Security:** Strengthen authentication, access controls, and patient consent management.

These are potential enhancements and should not be interpreted as already implemented features.

⚕️ Security and Disclaimer

Patient health information is sensitive and must be protected. A real-world deployment should implement appropriate authentication, role-based access controls, secure database policies, audit logging, and applicable privacy safeguards.

Medi-Core is an educational and development project. It is not a substitute for professional medical advice, diagnosis, or treatment. Its outputs and displayed health data must not be relied upon for clinical decisions without appropriate validation.

👨‍💻 Developer

**Praharsha Palivela**

GitHub: [@Praharsha5969](https://github.com/Praharsha5969)

Project: [Medi-Core](https://github.com/Praharsha5969/Medi-core)

---

<p align="center">
  <strong>Medi-Core — Making patient medical history more accessible for better-informed healthcare.</strong>
</p>
