# Tech Quiz Application - Cypress Testing Project

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Mongo](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)
![ReactJS](https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=for-the-badge)
![CYPRESS](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)


## Description

This project focuses on enhancing a fully functioning Tech Quiz application by implementing comprehensive testing using Cypress. The application allows users to take a 10-question tech quiz and view their final score, with a strong emphasis on ensuring reliability and robustness through thorough testing.

## 🚀 Project Overview

### User Story
```
AS AN aspiring developer
I WANT to take a tech quiz
SO THAT I can test my knowledge and improve my skills
```

### Acceptance Criteria
```
GIVEN I am taking a tech quiz
WHEN I click the start button
THEN the quiz starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN all questions are answered
THEN the quiz is over
WHEN the quiz is over
THEN I can view my score
WHEN the quiz is over
THEN I can start a new quiz
```

## 🛠 Tech Stack
- Frontend: React
- Backend: Node.js, Express.js
- Database: MongoDB
- Testing: Cypress

## 📦 Project Structure
```
.
├── client/                 // Client application
├── cypress/                // Cypress testing directory
    ├── component/          // Component test folder
    ├── e2e/                // End-to-end test folder
    └── fixtures/           // Test data
├── server/                 // Server application
└── cypress.config.ts       // Cypress configuration
```

## 🔧 Prerequisites
- Node.js (v14 or later)
- npm (v6 or later)

## 📥 Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/tech-quiz-testing.git
```

2. Install dependencies (MongoDB required)
```bash
npm install
```
```bash
npm run build
```
```bash
npm i seed
```
```bash
npm run start:dev
```

## 🧪 Running Tests

To run both component and end-to-end tests (in new terminal):
```bash
npm run test
```

## 📋 Test Coverage
- Component Tests: Verify individual React component behavior
- End-to-End Tests: Validate complete user interaction flow

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

## 🎥 Demonstration
![image](https://github.com/user-attachments/assets/c5538ed9-65bb-40df-93d3-ec63decde254)
![image](https://github.com/user-attachments/assets/84350ae7-8fcb-45d4-a9e3-e0dbb5a4896c)



## 🙌 Acknowledgements
- Cypress Testing Framework
- React
- MongoDB
- Express.js
