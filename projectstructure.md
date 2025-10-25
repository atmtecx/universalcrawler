universalcrawler/
├── backend/ # Spring Boot application
│ ├── src/main/java/com/universalcrawler/
│ │ ├── controller/
│ │ │ └── CrawlerController.java
│ │ ├── model/
│ │ │ └── RepositoryInfo.java
│ │ ├── service/
│ │ │ └── CrawlerService.java
│ │ └── UniversalCrawlerApplication.java
│ ├── src/main/resources/
│ │ └── application.properties
│ ├── pom.xml
│ └── README.md
│
├── frontend/ # Angular application
│ ├── src/
│ │ ├── app/
│ │ │ ├── components/
│ │ │ │ └── repo-list/
│ │ │ │ ├── repo-list.component.ts
│ │ │ │ ├── repo-list.component.html
│ │ │ │ └── repo-list.component.css
│ │ │ └── services/
│ │ │ └── crawler.service.ts
│ │ ├── index.html
│ │ └── main.ts
│ ├── angular.json
│ ├── package.json
│ └── README.md
│
├── database/
│ ├── init.sql
│ └── docker-compose.yml
│
├── docs/
│ ├── UML_Diagram.png
│ ├── architecture-overview.md
│ └── api-specs.md
│
├── LICENSE
├── README.md
└── .gitignore
