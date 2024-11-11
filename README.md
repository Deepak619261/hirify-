# Web Hiring Platform Application

## Objective
This project is a React-based web application that allows an admin to manage job postings, track candidates applying for those jobs, and create job-specific assessments. This platform streamlines the hiring process, enabling admins to post jobs, review candidate details, and assign customized assessments for each open position.

## Features & Requirements

### Dashboard for Managing Job Postings
- A page where the admin can monitor and edit job postings.
- Each job listing includes:
  - Job title
  - Job description
  - Number of candidates applied
- Admin actions:
  - Edit, add, and delete job postings.

### Candidate Tracking & Details Page
- Admin can view a list of candidates who applied for each job.
- For each candidate, the following details are displayed:
  - Candidate name
  - Resume link or document (with upload/download functionality)
  - Application date
  - Status (e.g., "Under Review", "Interview Scheduled", etc.)
- Clicking a candidate's name opens a detailed page with:
  - Candidate’s profile information (name, email, contact details, skills, experience)
  - Resume preview (or download link)
  - Status update option

### Job-Specific Test/Assessment Creation
- Allows the admin to create unique assessments for each job.
- On a dedicated page, the admin can:
  - Select a job from a dropdown list.
  - Create multiple-choice questions for that job.
  - Add or edit questions and answers.
- Each job has its own distinct assessment; no two jobs share the same test.

### User Interface & User Experience
- The application is designed to be intuitive and responsive, supporting both desktop and mobile devices.
- Clean and modular code is maintained, adhering to React best practices.
- State management (Redux or React Context API) is used for efficient app performance and data handling.

### Additional Requirements
- **Routing**: Implemented using React Router to navigate between different sections (job postings, candidates, assessments).
- **UI Library**: Use a UI library like Material-UI, Ant Design, or a custom-built component library to maintain a consistent and user-friendly interface.
- **Data Persistence**: Not required, but local storage or mock APIs can be used to simulate data. A basic backend is optional.

## Setup & Running Instructions

### Prerequisites
- Node.js and npm installed on your machine.
- Git installed for version control.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Deepak619261/hirify-.git
