# codeforces-visualizer
# Codeforces Stats Visualizer

A modern React-based web application that visualizes competitive programming statistics and performance insights of Codeforces users using the official Codeforces API.

## Overview

Codeforces Stats Visualizer enables users to analyze their competitive programming journey through interactive performance metrics such as:

- User profile information
- Best contest rank
- Last solved problem
- Problem-solving statistics
- Tag-wise problem analysis
- Live API-based data fetching

The application is designed to provide a clean and responsive user experience while demonstrating frontend development, API integration, and state management concepts using React.

---

## Features

- Search any Codeforces handle
- Fetch real-time user data using Codeforces REST APIs
- Display best contest rank achieved
- View last solved problem details
- Analyze solved problem count
- Tag-wise problem distribution analysis
- Responsive UI with loading shimmer effect
- Optimized frontend rendering using React Hooks

---

## Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3

### APIs
- Codeforces Official API

### Build Tool
- Parcel Bundler

---

## Project Structure

```bash
├── Body.js
├── Header.js
├── Footer.js
├── CartShimmer.js
├── index.js
├── style.css
├── index.html
├── package.json
└── README.md
```

---

## Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/samrat-sarkar-git/Codeforces-Stats-Visualizer.git
```

### Navigate to Project Directory

```bash
cd Codeforces-Stats-Visualizer
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm start
```

The application will run on:

```bash
http://localhost:1234
```

---

## API Endpoints Used

### User Information
```bash
https://codeforces.com/api/user.info?handles={handle}
```

### User Rating History
```bash
https://codeforces.com/api/user.rating?handle={handle}
```

### User Submission Status
```bash
https://codeforces.com/api/user.status?handle={handle}
```

---

## Core Functionalities

### Unique Problem Filtering
The application filters duplicate solved problems using a custom Set-based approach to ensure accurate problem count statistics.

### Tag Analysis
Problem tags are aggregated dynamically using JavaScript Map structures for performance visualization and category analysis.

### Loading Skeleton UI
A shimmer loading component improves user experience during asynchronous API calls.

---

## Learning Outcomes

This project helped in gaining practical experience in:

- React Hooks (`useState`, `useEffect`)
- REST API integration
- State management
- Component-based architecture
- Asynchronous JavaScript
- Responsive UI design
- Data filtering and aggregation
- Frontend performance optimization

---

## Future Improvements

- Add graphical data visualization using charts
- Dark mode support
- Contest rating trend graph
- User comparison feature
- Mobile-first optimization
- Pagination for submissions
- Better error handling and validations

---

## License

This project is licensed under the MIT License.
