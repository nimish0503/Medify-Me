# [MedifyMe](https://medifymeiitbhu.me/)

MedifyMe is a web application that provides users with a platform to manage their health records and appointments.

![landingPage](https://user-images.githubusercontent.com/96655163/232332327-36459110-9580-45bf-8002-e655624321e2.png)

## Problem

Patients often have to visit multiple doctors, clinics, or hospitals for their treatment, which can lead to fragmented and incomplete medical records. This can be a major issue for patients and healthcare providers, especially those with chronic conditions. It can lead to ineffective or even dangerous treatments due to a lack of information about previous diagnoses, medications, and procedures. In cases of emergencies or sudden health issues, it is challenging to provide relevant medical information to healthcare providers in a timely and accurate manner. Moreover, patients may face difficulties in tracking their medication schedules, keeping up with follow-up appointments, and accessing their medical records when needed.

## Objective

MedifyMe is a web application I developed to simplify healthcare management for both patients and doctors. It aims to solve these issues by providing a centralized platform for patients to store and manage their medical records, including doctor's notes, prescriptions, test results, and appointment history, utilizing OCR and generative AI to ease the record management process for both patients and the healthcare provider. This allows for a more complete and accurate medical record, facilitating better treatment outcomes and reducing the risk of medical errors. The platform helps patients keep track of their medical history, prescriptions, appointments, and test reports. It also provides reminders for medications and tests, and allows patients to give feedback about their treatment experiences. The tool is segmented into various tabs to ease different parts of the healthcare process.

## Methodology

MedifyMe's frontend is built using React for user interfaces. The backend is built using Node.js, with Express as the web application framework, and MongoDB as the NoSQL database for storing patient and doctor data. Google Cloud Storage Buckets are used for storing users' medical prescriptions and bills.

The application uses Google Oauth2 for authentication, React-Redux for state management, React-Toolkit-Query for handling query requests, React-Cookies for storing and accessing cookies, and React-Toastify for displaying toast information. It also utilizes OCR Space’s API to extract medicine data from prescriptions, tests, and reports uploaded by users.

## Results

MedifyMe provides an easy and secure communication channel for patients and doctors to exchange messages and medical information. Patients can ask questions, get advice, and share updates with their doctors in a timely and convenient manner. Payments for various appointments and tests can be made on the platform itself, reducing hassle.

MedifyMe provides users with a user-friendly and secure platform for managing their health records and appointments. Users can view their medical history, schedule appointments with doctors, and receive personalized recommendations based on their input.

## Getting Started

To get started with MedifyMe, follow the steps below:
1. Fork this repository by clicking on the Fork button in the top right corner of this page.
2. Clone your forked repository to your local machine.
3. Navigate to both the frontend and backend folders in the terminal and run the command `npm install` to install the required dependencies.
4. Run the command `npm start` to start the application.

## Tech Stack
### Frontend
- React
- React-Redux
- React-Toolkit-Query
- Google Oauth2
- React-Cookies
- React-Toastify
- Vite

### Backend
- Node.js
- Express
- MongoDB
- Google Cloud Storage Buckets
- OCR Space
- OPENAI's API with prompt engineering

## UI Design

The entire UI of MedifyMe has been built in Figma, and the design is available [here](https://www.figma.com/file/p850Ggh3o7Wx06xZKHPmRP/Aaspaas-MedifyMe-GFG?node-id=0%3A1&t=MQ3j3cVIlFJdoxmI-1).
