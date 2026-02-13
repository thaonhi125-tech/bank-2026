# Prof Roh Bank AI - Client Intelligence Dashboard

## Overview

This project is a web-based Client Intelligence Dashboard for relationship managers at "Prof Roh Bank AI". It leverages a mock AI engine to analyze synthetic customer data, identify behavioral patterns, and provide actionable insights. The goal is to help bank staff make smarter, data-driven decisions to enhance client relationships, increase profitability, and mitigate risk.

The application is a single-page React application styled with Tailwind CSS.

## Features Implemented

### Core Application Structure
*   **Single-Page React App:** Built using React and Babel, running directly in the browser.
*   **Styling:** Uses Tailwind CSS for a modern, clean, and responsive user interface inspired by Apple's design language.
*   **Routing:** A custom state-based routing system manages different views:
    *   Login Page
    *   Client List View
    *   Client Dashboard View
    *   Client Profile View

### Client Profiles & Data
*   **Diverse Mock Data:** A comprehensive set of mock client profiles has been created to simulate a realistic client portfolio, including:
    *   **Alex Tan:** The "Cash-Flow Juggler" (Young Professional)
    *   **Sarah Lee:** The "Optimizer" (Affluent Saver)
    *   **Mike Chen:** The "Rate Shopper" (SME Owner)
    *   **Emily White:** The "Variable Earner" (Gig Economy Professional)
    *   **David Green:** The "Capital Guardian" (Pre-Retiree)
    *   **Olivia Blue:** The "Global Spender" (Digital Nomad)
    *   **James Black:** The "Future High-Earner" (University Student)
*   **Client List:** An interactive list to browse and select clients, with visual risk indicators.

### Intelligence Dashboard
*   **Vital Signs:** Key metrics at a glance: Net Value Score, Risk Probability, and Churn Likelihood.
*   **Behavioral DNA:** Provides a qualitative summary of the client's financial archetype and behavior.
*   **Recommendation Engine:**
    *   **Green Light (Sell):** A clear, actionable product recommendation that aligns with the client's needs and the bank's strategy.
    *   **Red Light (Avoid):** A warning against products that would be detrimental to the client or the bank.
    *   **Pop-up Modals:** Clicking on a recommendation opens a modal with more details.
*   **AI-Suggested Script:** Provides talking points for the relationship manager, tailored to the client's specific situation and the recommended product.

### Interactive Tools
*   **Call Client Modal:**
    *   Initiated from the dashboard header.
    *   Simulates a call interface, displaying the client's name and number.
    *   Presents the AI-suggested script for easy reference.
    *   Includes a "Copy to Clipboard" feature for the script.
*   **Live Data Collection (Survey):**
    *   Launched via the "Start Survey" button.
    *   A modal presents a series of discovery questions to ask the client in real-time.
    *   The questions are designed to gather precise data for deeper analysis by the AI model, covering:
        1.  **Financial Stress Test** (Scale input)
        2.  **Life Event Horizon** (Checkbox input)
        3.  **Risk Sentiment** (Radio button input)
    *   Features a polished UI for easy interaction during a client conversation.

## Plan for Current Request

The user has requested to commit the current state of the application and push it to a new GitHub repository.

**Steps:**
1.  Initialize a new Git repository.
2.  Add all current project files to the staging area.
3.  Create a commit with a descriptive message.
4.  Rename the default branch to `main`.
5.  Add the specified remote GitHub repository URL.
6.  Push the `main` branch to the remote repository.
