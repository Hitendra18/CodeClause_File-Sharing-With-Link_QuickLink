# CodeClause_File-Sharing-With-Link_QuickLink

Welcome to the File Sharing Website project! This web application allows you to easily share files with others using a simple drag-and-drop or browse interface. You can generate shareable links or directly send files via email. This repository contains the source code and files for the website.

![Home Page](https://github.com/Hitendra18/CodeClause_File-Sharing-With-Link_QuickLink/assets/88924097/eefcb19b-72bd-49d1-9314-5e507f15486d)
![File uploaded](https://github.com/Hitendra18/CodeClause_File-Sharing-With-Link_QuickLink/assets/88924097/0068de0e-9e1d-4050-adb1-04be9942e443)
![email sent](https://github.com/Hitendra18/CodeClause_File-Sharing-With-Link_QuickLink/assets/88924097/69fd162e-679f-4b3c-b188-ab7f9b5a2951)
![download page](https://github.com/Hitendra18/CodeClause_File-Sharing-With-Link_QuickLink/assets/88924097/aca4ac67-bf6e-4ca5-8b9c-a29ef438c646)



## Features

- Drag-and-drop or browse file upload
- Generate shareable links
- Send files via email
- Easy-to-use interface
- Responsive web design
- Secure file storage using MongoDB
- Built with HTML, CSS, JavaScript (Node.js), and MongoDB
- Deployed using Render.com

## Prerequisites

- Node.js and npm installed
- MongoDB database (can be local or hosted)
- Other dependencies (install using `npm install`)

## Installation

1. Clone this repository: `git clone https://github.com/your-username/your-repo.git`
2. Navigate to the project folder: `cd https://github.com/Hitendra18/CodeClause_File-Sharing-With-Link_QuickLink`
3. Install dependencies: `npm install`

## Configuration

1. Rename `.env.example` to `.env`.
2. Fill in the required environment variables in `.env`:
   - `MONGODB_URI`: Your MongoDB connection URI
   - `MAILER_EMAIL`: Your email address for sending emails
   - `MAILER_PASSWORD`: STMP service password
   - ...other configuration variables

## Usage

1. Start the server: `npm start` or `npm run dev` (if using nodemon).
2. Open a web browser and visit: `http://localhost:3000` (or the specified port).
3. Upload a file by dragging and dropping or browsing.
4. Choose between generating a shareable link or sending the file via email.
5. Follow the on-screen instructions to complete the process.

## Deployment

This website is deployed using Render.com. To deploy it yourself:

1. Create an account on Render.com.
2. Connect your GitHub repository to Render.
3. Configure the necessary environment variables in the Render dashboard.
4. Deploy your app using the provided deployment instructions.
