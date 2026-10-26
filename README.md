# Tandorost 🩺
### A Smarter Approach to Personal Health Management

**Tandorost** is a health-focused web platform designed to bring personal health management, nutrition tracking, scientific knowledge, and AI-assisted tools together in one place.

The project aims to make health information more accessible and help users better understand their daily habits through a clean, organized, and extensible web application.

> 🚀 **Coming Soon — Tandorost is under active development.**

---

## 🌟 About the Project

Managing personal health often involves using multiple tools for nutrition, health records, educational resources, and community discussions.

Tandorost aims to bring these experiences together in a unified platform, with a focus on usability, modular architecture, and future expansion.

The long-term vision is to build a connected health platform where users can access useful tools, explore reliable information, and make more informed decisions about their everyday well-being.

## ✨ Key Features

### 👤 User Accounts
- User registration and authentication.
- Personalized access to platform features.
- Subscription-related functionality.

### 🥗 AI-Assisted Nutrition
- Natural-language food descriptions.
- Estimated food quantities and calorie information.
- A workflow designed to let users review estimates before saving them.
- Support for local AI inference, with potential for additional AI integrations.

### 📊 Personal Health Tracking
- Tools for recording and organizing health-related information.
- A foundation for expanding personal health monitoring features.

### 📚 Health Education
- Health-related articles and educational content.
- An organized way to explore information about health and well-being.

### 🔬 Scientific Community
- Community-oriented scientific discussions.
- Posts and channels designed to support knowledge sharing.

### 🤖 AI Integration
- An architecture intended to support AI-assisted functionality.
- Local model integration for selected tasks.
- Potential for optional external AI services as the project evolves.

### 🎁 Subscription and Rewards
- Subscription management features.
- A weekly giveaway mechanism designed to reward eligible participants.

---

## 🏗️ Project Architecture

Tandorost is being developed as a modular web application, with separate responsibilities for application logic, data storage, user-facing pages, and AI-related functionality.

The current project is built around the following components:

```text
Tandorost/
│
├── app.py
│   └── Main Flask application and web routes
│
├── templates/
│   └── HTML templates and user interface pages
│
├── static/
│   └── Static assets, styles, and frontend resources
│
├── models/
│   └── Directory for model-related resources
│
├── food_estimator.py
│   └── Food estimation functionality
│
├── ai_food_parser.py
│   └── Natural-language food description parsing
│
├── run_weekly_lottery.py
│   └── Standalone weekly lottery runner
│
├── README_FA.md
│   └── Persian project documentation
│
└── README.md
    └── English project documentation
```

*This is a simplified overview of the main project components, not a complete representation of every file or dependency.*

### Architectural Principles

- **Modularity:** Keep major responsibilities separated to make future development easier.
- **Maintainability:** Organize application logic so that new features can be introduced incrementally.
- **Extensibility:** Leave room for future AI services, data sources, and health-related modules.
- **User-centered design:** Prioritize clear navigation and accessible functionality.
- **Responsible AI:** Treat AI-generated nutrition estimates as estimates that users should be able to review, rather than guaranteed medical or nutritional facts.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core application logic |
| Flask | Web application framework |
| SQLite | Database support in the current application |
| HTML and CSS | User interface and styling |
| JavaScript | Interactive frontend functionality |
| Local AI models | AI-assisted processing for supported features |

The technology stack may evolve as the project grows.

---

## 🗺️ Development Roadmap

Tandorost is being developed incrementally. Potential development priorities include:

- [ ] Improve consistency across the user interface.
- [ ] Expand and refine nutrition estimation.
- [ ] Improve AI integration and error handling.
- [ ] Strengthen authentication and application security.
- [ ] Expand personal health tracking tools.
- [ ] Improve health information organization and discoverability.
- [ ] Refine scientific community features.
- [ ] Improve deployment and database configuration.
- [ ] Expand testing and documentation.
- [ ] Explore additional data sources and optional AI providers.

These items describe development goals; they do not imply that every feature is already complete.

---

## 🔒 Privacy and Security

Health-related information deserves careful handling.

The project aims to improve data protection, access control, and responsible handling of user information as development progresses.

Before using the platform with real or sensitive health information, its security, privacy practices, deployment configuration, and data-storage mechanisms should be reviewed.

---

## ⚠️ Disclaimer

Tandorost is a software project for health information management and educational purposes.

AI-generated food and calorie estimates may be inaccurate. The platform should not be treated as a substitute for professional medical advice, diagnosis, or treatment.

---

## 📌 Project Status

**Status: Under Development**

Tandorost is being built toward a broader, integrated health platform. Features, architecture, and user experience may change as development continues.

## 🚀 Coming Soon

**Tandorost is coming soon.**

We are working toward bringing its health tools, nutrition features, and AI-assisted capabilities together in a more complete experience.

Stay tuned for updates.

---

*Built with Python, Flask, and a vision for more accessible digital health tools.*
