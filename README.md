# AI Email Reply Extension

An AI-powered browser extension that helps users generate smart,
context-aware email replies directly inside Gmail.

------------------------------------------------------------------------

##  Overview

The AI Email Reply Extension integrates seamlessly with Gmail to help
users compose professional and contextually relevant email responses in
one click. It uses a Spring Boot backend connected to an AI model API to
generate intelligent replies based on the email content.

This project demonstrates full-stack development, browser extension
architecture, API integration, and cloud deployment.

------------------------------------------------------------------------

## Features

• Generate AI-powered email replies instantly\
• Seamless integration inside Gmail interface\
• Multiple reply tone options (professional, friendly, concise, etc.)

------------------------------------------------------------------------

## Tech Stack

### Backend

• Java\
• Spring Boot\
• REST APIs\
• AI Model API Integration\
• Docker\
• Render (Cloud Deployment)

### Frontend (Extension)

• JavaScript\
• Chrome Extension APIs\
• DOM Manipulation

------------------------------------------------------------------------

## System Architecture

1.  User opens Gmail
2.  Extension injects custom reply assistant UI
3.  User clicks "Generate Reply"
4.  Email content is sent to Spring Boot backend
5.  Backend calls AI API for response generation
6.  Generated reply is returned and inserted into Gmail compose box

<img width="500" height="250" alt="Img1" src="https://github.com/user-attachments/assets/36a94c06-8a9c-458e-93a9-5cf14f4f3203" />

<img width="500" height="250" alt="Img2" src="https://github.com/user-attachments/assets/dd8b7312-4bc3-4cb1-9832-85fdbe71f5b1" />

<img width="500" height="250" alt="Img3" src="https://github.com/user-attachments/assets/3e6f70e7-f0e1-4b46-8481-d5ca583817f6" />

<img width="500" height="250" alt="Img4" src="https://github.com/user-attachments/assets/3a5c693e-e6c9-4566-be22-a0e5bf76d245" />

------------------------------------------------------------------------

## Deployment

### Backend Deployment

• Containerized using Docker\
• Deployed on Render cloud platform\
• REST APIs exposed securely over HTTPS

### Extension Publishing

• Published on Microsoft Edge Add-ons Store

------------------------------------------------------------------------

##  Key Learning Highlights

• Built production-ready REST APIs using Spring Boot\
• Implemented browser extension content scripts and service workers\
• Integrated generative AI APIs into real-world applications\
• Dockerized backend services for scalable deployment\
• Managed cross-origin communication between extension and backend\
• Published and maintained a live browser extension

------------------------------------------------------------------------

##  Installation (Development Setup)

### Backend Setup

1.  Clone the repository
2.  Navigate to backend folder
3.  Build the project


```
    mvn clean install
```
4.  Run the Spring Boot application


```
    mvn spring-boot:run
```
------------------------------------------------------------------------

### Extension Setup

1.  Open browser and go to Extensions
2.  Enable Developer Mode
3.  Click "Load Unpacked"
4.  Select extension project folder - ai-email-extension.zip

------------------------------------------------------------------------

## Store Links

• Extension Store Listing: https://microsoftedge.microsoft.com/addons/detail/ai-email-reply/eickailglijggnibpniefeamaiekckgb?hl=en-US\
Not available on chrome store but can be used by following Extension setup.

------------------------------------------------------------------------

## Author

**Amol Anshuman**

