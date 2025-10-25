🕷️ Universal Crawler

Universal Crawler is a powerful, modular, and open-source web crawler built using Spring Boot, Angular, and MySQL.
It can crawl any website, including GitHub, to extract valuable data such as repositories, metadata, links, and structured content — all through a clean RESTful API and an intuitive web interface.

🚀 Features

🌐 Universal Crawling Engine — Supports crawling of any public website (GitHub, blogs, e-commerce sites, etc.)

⚙️ Modular Architecture — Backend in Spring Boot, frontend in Angular, and database in MySQL.

🔍 Smart Filtering — Fetch and filter content by keywords, language, stars, or tags.

📊 Data Storage — Save crawled data in MySQL for analysis.

🧠 Extensible — Add custom parsers for specific websites easily.

🧩 Dockerized Deployment — Run with a single command using docker-compose up.

🛡️ REST API — Fully documented endpoints for integration with other apps.

🧱 Architecture Overview
  Frontend (Angular) ---> REST API (Spring Boot) ---> Database (MySQL)
                                   |
                                   ---> External Websites (GitHub, etc.)
Frontend: Angular application for searching, viewing, and managing crawl results.

Backend: Spring Boot handles business logic and data storage.

Database: MySQL stores crawled data persistently.

Integration: Docker Compose orchestrates all services seamlessly.

⚙️ Installation and Setup
Prerequisites

🧩 Java 17+

🧩 Node.js 18+

🧩 MySQL 8+

🧩 Docker (optional, for containerized setup)

Clone the repository
  git clone https://github.com/<your-username>/universal-crawler.git
  cd universal-crawler
Run with Docker
  cd backend
  mvn spring-boot:run
Visit the app at:
👉 http://localhost:4200

🧠 API Example
Search GitHub Repositories
    Request: GET /api/github/search?keyword=java
    [
      {
        "name": "spring-boot",
        "description": "Spring Boot makes it easy to create stand-alone apps.",
        "stars": 69000,
        "url": "https://github.com/spring-projects/spring-boot"
      }
    ]

📘 UML & Documentation

You can find UML diagrams and design docs in /docs/:

UML_Diagram.png — Class and Sequence Diagrams

architecture-overview.md — System design explanation

api-specs.md — API details and usage

🧩 SDLC, Agile & ITIL Practices

This project follows:

SDLC: Requirements → Design → Implementation → Testing → Deployment → Maintenance

Agile Methodology: Iterative 2-week sprints, backlog management, GitHub Issues as user stories

Scrum Practices: Daily standups, sprint reviews, retrospectives

ITIL Framework: Change, Incident, and Release management mapped to GitHub workflows

🤝 Contributing

We love contributions ❤️

1. Fork this repository
2. Create a new branch
    git checkout -b feature/your-feature
3. Commit your changes
   git commit -m "Add new feature"
4. Push and create a Pull Request

All contributions will be reviewed following the project's Agile guidelines.

  🧑‍💻 Maintainer

Project: Universal Crawler
Author: Universal Crawler Team
License: MIT License

 🪪 License   
         MIT License

      Copyright (c) 2025 Universal Crawler
      
      Permission is hereby granted, free of charge, to any person obtaining a copy
      of this software and associated documentation files (the "Software"), to deal
      in the Software without restriction, including without limitation the rights
      to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
      copies of the Software, and to permit persons to whom the Software is
      furnished to do so, subject to the following conditions:
      
      The above copyright notice and this permission notice shall be included in
      all copies or substantial portions of the Software.
      
      THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
      IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
      FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
      AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
      LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
      OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
      THE SOFTWARE.

  ⭐ Support

If you find this project useful,
please star the repository 🌟 on GitHub and help others discover it.

  
  
