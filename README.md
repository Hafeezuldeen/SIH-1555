# Smart India Hackathon Workshop

# Date: 14.11.2025

## Register Number:21223220028

## Name: Hafeezul Deen S

## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).


## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.


## Problem Creater's Organization
Ministry of Ayush


## Idea
Our idea is to create a "Virtual AYUSH Garden," an accessible, web-based platform that brings a rich herbal garden to life using interactive 3D models. Users can explore, learn about, and interact with medicinal plants from anywhere. It's a digital bridge to traditional knowledge, making AYUSH plant education engaging and universally available.


## Proposed Solution / Architecture Diagram
We propose a simple and robust client-server architecture. The frontend will be a React application that handles the 3D rendering using Three.js. This frontend will communicate with a Node.js/Express.js backend API. The API will fetch plant information (names, uses) from a MongoDB database and retrieve media files (3D models, images, videos) from a dedicated media storage like AWS S3.

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/fa5077f1-8b84-4aa0-8237-610454eb375e" />



## Use Cases
Students: Can virtually explore and study plants for their AYUSH courses, using the 3D models and detailed info for learning and research.

AYUSH Practitioners: Can quickly search for a specific plant, review its medicinal uses, and use the platform to educate patients.

Public/Enthusiasts: Can take guided "Virtual Tours" (e.g., "Plants for Skin Care") and learn about the benefits of common herbs.

Researchers: Can use the search and filter to find plants based on specific criteria like habitat or medicinal properties.


## Technology Stack
Frontend: React.js

3D Rendering: Three.js (or @react-three/fiber)

Backend: Node.js, Express.js

Database: MongoDB

Storage: AWS S3 (or Firebase Storage)

Deployment: Vercel (Frontend), Heroku / AWS (Backend)


## Dependencies
react

three

@react-three/fiber (for integrating Three.js with React)

@react-three/drei (helpers for 3D scenes)

express (backend framework)

mongoose (for connecting to MongoDB)

cors (for API access)

aws-sdk (for connecting to S3)

nodemon (for development)
