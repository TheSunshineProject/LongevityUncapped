# Design Document for Longevity Uncapped Website

## Introduction
This document provides a technical overview of the Longevity Uncapped website. It details the architectural choices and design decisions with a focus on user experience, simplicity, and integration of dynamic features like the news gallery and the Longevity Bot.

## Architecture Overview

### Front-End Design
- **Technology Stack**: The website is built using React.js. This choice was driven by React's robust ecosystem and its capability to integrate complex functionalities like the news gallery seamlessly.
- **User Interface**: The website features a simple header with a title and subheader. A dark background theme was chosen for its ease on the eyes, enhancing readability and comfort for users.
- **Responsive Design**: The UI is designed to be responsive, ensuring compatibility and optimal viewing across various devices.

### Back-End Design
- **Server and API**: The backend is structured to support the front-end React application, handling data requests and responses efficiently.

### News Gallery Implementation
- **Manual Curation**: The news gallery is formatted and curated manually, featuring top picks in longevity research and health tips. This manual curation is a strategic choice to ensure the quality and relevance of the content presented to users.

### Longevity Bot Integration
- **Initial Implementation**: Due to time constraints, the Longevity Bot, powered by GPT technology, was initially developed separately. A link to the bot is provided on the website for user access.
- **Future Integration Plan**: The next phase involves integrating the Longevity Bot directly into the website, enhancing user interaction and providing personalized assistance within the site.

## Design Decisions

### Choice of React.js
- The decision to use React.js was primarily due to its suitability in integrating complex components like the news gallery and its widespread support and scalability.

### UI/UX Considerations
- The dark theme and simple header design were chosen to create an aesthetically pleasing and user-friendly interface, considering the target audience's preferences.

### Longevity Bot Deployment
- The initial external linking of the Longevity Bot was a strategic decision to meet project timelines while still providing the functionality to users. The integration plan is outlined for future development.

## Challenges and Solutions
- **Time Constraint**: The main challenge was the time constraint, particularly in the integration of the Longevity Bot. The solution was to provide a separate link to the bot as an interim measure.
- **Content Curation**: Ensuring high-quality, relevant content in the news gallery required manual curation, balancing the need for quality content against the time required for curation.
