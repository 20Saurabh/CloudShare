# CloudShare

This complete project includes **React**, **Spring Boot**, **MongoDB**, and **Tailwind CSS** to help you build a professional-grade **file manager web app**.

## Table of Contents

1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Installation Guide](#installation-guide)  
   - [Step 1: Setup Database](#step-1-setup-database)  
   - [Step 2: Setup Clerk Authentication](#step-2-setup-clerk-authentication)  
   - [Step 3: Setup Razorpay](#step-3-setup-razorpay)  
   - [Step 4: Backend Setup](#step-4-backend-setup)  
   - [Step 5: Frontend Setup](#step-5-frontend-setup)  



## Features

With this project, you'll learn to:

- Upload, preview, download & delete files
- Toggle files between public/private visibility
- Share public files via unique links
- View files in grid or list mode with beautiful UI
- Implement user-based file access using **Clerk authentication**
- Build a responsive, modern UI using **Tailwind CSS** and **Lucide icons**
- Follow clean code structure with reusable components (e.g., `FileCard`, `FileListRow`)



## Tech Stack

- **Frontend:** React, Tailwind CSS, ClerkAuth  
- **Backend:** Spring Boot  
- **Database:** MongoDB  
- **Authentication:** Clerk  
- **Payments:** Razorpay   


## Installation Guide

### Step 1: Setup Database
- Install **MongoDB** ([Tutorial](https://www.youtube.com/watch?v=KYIOJrE3zjk))  
- Create a new database

### Step 2: Setup Clerk Authentication
1. Create an account in [Clerk](https://clerk.com)  
2. Create a new application  
3. Copy the following keys:  
   - `CLERK_PUBLISHABLE_KEY`  
   - `Frontend API URL`  
   - `JWKS URL`  
   - `Webhook Signing Secret`

### Step 3: Setup Razorpay
1. Create a Razorpay account  
2. Go to profile settings → API Keys  
3. Note down **Key ID** and **Secret Key**

### Step 4: Backend Setup
1. Download the project and extract it  
2. Open the backend API (`cloudshareapi`) in IntelliJ IDEA  
3. Open `application.properties` and update database & API keys  
4. Run `CloudshareapiApplication.java`  

### Step 5: Frontend Setup
1. Open the frontend application (`cloudsharewebapp`) in **Visual Studio Code** or **WebStorm**  
2. Open `.env` file and update keys and API URLs  
3. In terminal, navigate to the frontend root folder and run:

```bash
npm install
npm run dev
```


