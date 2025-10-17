# GitHub User Status Reporter

![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20App-brightgreen?style=for-the-badge&logo=github)
[Live Demo](https://rammarch2005.github.io/github-user-created/)

## Table of Contents
*   [Project Overview](#project-overview)
*   [Features](#features)
*   [Setup Instructions](#setup-instructions)
*   [Usage](#usage)
*   [Technical Implementation Details](#technical-implementation-details)
*   [License](#license)

## Project Overview

This project demonstrates an accessible method for reporting the status of an asynchronous operation, specifically a GitHub user lookup. It utilizes ARIA live regions to provide real-time updates on the lookup's progress (loading, success, or failure) in a way that is easily consumable by assistive technologies like screen readers. The primary goal is to enhance user experience by giving immediate, clear, and accessible feedback on backend interactions.

## Features

*   **Real-time Status Updates:** Provides immediate feedback on GitHub user lookup operations.
*   **Accessible Feedback:** Implements `aria-live="polite"` on a dedicated status region (`#github-status`) to announce lookup states (e.g., "Loading...", "User found!", "User not found.") to assistive technologies without interrupting the user.
*   **Clear Visual Indicators:** Displays status messages prominently on the screen for all users.
*   **Error Handling:** Reports when a user is not found or if there are issues communicating with the GitHub API.
*   **Simple User Interface:** A straightforward input field and button for ease of use.

## Setup Instructions

This is a client-side web application, so no complex backend setup is required.

1.  **Clone the Repository:**