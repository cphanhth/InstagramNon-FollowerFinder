# Instagram Non-Follower Finder

## Overview
This project consists of a **frontend** and **backend** that work together to find Instagram users who do not follow you back. The backend uses **Puppeteer** to automate the process of logging into an Instagram and scraping follower and following data, while the frontend provides an intuitive UI for users to enter their Instagram credentials and view non-followers. Currently the backend is only deployed locally on my device, so the website does not work when I am not running the backend.

## Features
- Secure login with Puppeteer-based automation
- Fetches and compares followers and followings
- Displays users who do not follow back
- Frontend built with React.js
- Backend built with Express.js and Puppeteer

## Technologies Used
### Backend:
- **Node.js** with **Express.js**
- **Puppeteer** for web scraping
- **CORS** for cross-origin requests

### Frontend:
- **React.js** with Hooks
- **Axios** for API requests
- **CSS** for styling

## Setup and Installation
### Prerequisites
Ensure you have **Node.js** and **npm** installed on your system.

### Backend Setup
1. Navigate to the backend directory:
   ```sh
   cd server
