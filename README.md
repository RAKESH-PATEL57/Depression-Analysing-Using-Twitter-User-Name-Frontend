# Depression Analysis Frontend

This repository contains the frontend code for the Depression Analysis project. The frontend allows users to enter a Twitter username and view an analysis of their recent tweets, predicting if the user might be experiencing signs of depression.

## Live Demo

Access the live application [here](https://depression-analysing.netlify.app/).

## Technologies Used

- **React.js:** A powerful JavaScript library for building interactive user interfaces.
- **CSS:** For styling and ensuring a visually appealing design.
- **Axios:** For making API requests to the backend.
- **Vite:** A fast and modern development environment for building React applications.

## Features

- **Username Input:** Users can enter a Twitter username to analyze their tweets.
- **Loading State:** Displays a loading indicator while analysis is in progress.
- **Timer Mechanism:** Prevents users from submitting another username until 15 minutes have passed.
- **Error Handling:** Displays meaningful error messages for invalid inputs or failed API requests.
- **Responsive Design:** Ensures a seamless user experience across all devices.

## How It Works

1. Users enter a Twitter username and submit the form.
2. The frontend sends a request to the backend API with the entered username.
3. The backend fetches and analyzes the tweets and returns the results.
4. The frontend displays the tweets and the analysis result.
5. A timer starts, preventing further submissions for 15 minutes.

## Installation and Setup

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
