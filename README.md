# HRMS-Upgrade ➕🏥

Welcome to the HRMS-Upgrade repository! This project is a comprehensive HealthCare Management System built using modern web technologies to ensure scalability, maintainability, and a seamless user experience. This README provides a detailed overview of the project, including its features, setup instructions, and more.

![Screenshot 2024-07-06 at 3 32 38 PM](https://github.com/themihirmathur/HRMS-Upgrade/assets/92594107/36b09a81-2214-4950-bd28-dd086dc9ed45)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Table of Contents
1. Introduction
2. Tech Stack
3. Features
4. Getting Start

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Introduction

HRMS-Upgrade is a robust healthcare patient management application designed to streamline the process of patient registration, appointment scheduling, and management. The application is built using Next.js and provides a responsive and intuitive user interface. Patients can easily register, book, and manage their appointments, while administrators have powerful tools for scheduling, confirming, and canceling appointments. The system also includes SMS notifications to keep patients informed about their appointment status.

For those who prefer visual learning, our in-depth tutorial on the JavaScript Mastery YouTube channel guides you through the development of this project step-by-step.

![Screenshot 2024-07-06 at 3 31 46 PM](https://github.com/themihirmathur/HRMS-Upgrade/assets/92594107/c35be8af-bedc-4eac-9b7d-b669f18d6df2)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Tech Stack

- **Next.js**: React framework for server-side rendering and static site generation.
- **Appwrite**: Backend server for Web, Mobile, and Flutter developers.
- **Typescript**: Superset of JavaScript for type safety and enhanced development experience.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **ShadCN**: Custom components for enhanced styling.
- **Twilio**: Cloud communications platform for sending SMS notifications.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Features

- **Patient Registration**: Users can sign up and create a personal profile.
- **Appointment Booking**: Patients can schedule appointments with doctors at their convenience.
- **Admin Appointment Management**: Administrators can view, confirm, and schedule appointments.
- **Appointment Cancellation**: Admins can cancel appointments as needed.
- **SMS Notifications**: Patients receive SMS notifications for appointment confirmations.
- **Complete Responsiveness**: The application is fully responsive and works on all device types.
- **File Upload**: Secure file upload and storage using Appwrite.
- **Performance Monitoring**: Integration with Sentry for tracking application performance and error detection.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Getting Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository

To clone the repository, run the following command:

```bash
git clone https://github.com/adrianhajdin/healthcare.git
cd healthcare
```

### Installation

Install the project dependencies using npm:

```bash
npm install
```

### Set Up Environment Variables

Create a new file named `.env.local` in the root of your project and add the following content:

```env
# APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=<your-project-id>
API_KEY=<your-api-key>
DATABASE_ID=<your-database-id>
PATIENT_COLLECTION_ID=<your-patient-collection-id>
APPOINTMENT_COLLECTION_ID=<your-appointment-collection-id>
NEXT_PUBLIC_BUCKET_ID=<your-bucket-id>
NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io).

### Running the Project

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

---

Thank you for using HRMS-Upgrade! If you have any questions or encounter any issues, please don't hesitate to reach out for assistance.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
