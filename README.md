# Java-Spring-Boot-GenAI-Masterclass

Structured coursework, notes, and hands-on projects for learning:

- Core Java
- Spring Core (IoC/DI)
- Spring Boot REST APIs
- Spring Data JPA
- Spring Security
- Generative AI applications with Spring AI

## Repository Structure

```text
.
├── docs/
│   ├── roadmap.md
│   └── module-checklists.md
└── projects/
    ├── maven/
    │   ├── pom.xml
    │   ├── core-java/
    │   ├── spring-core/
    │   ├── spring-boot-rest/
    │   ├── spring-data-jpa/
    │   ├── spring-security/
    │   └── spring-ai/
    └── gradle/
        ├── settings.gradle
        ├── build.gradle
        ├── core-java/
        ├── spring-core/
        ├── spring-boot-rest/
        ├── spring-data-jpa/
        ├── spring-security/
        └── spring-ai/
```

## Start Here

1. Follow the learning path in `/docs/roadmap.md`
2. Track module progress in `/docs/module-checklists.md`
3. Choose one build system:
   - Maven: `projects/maven`
   - Gradle: `projects/gradle`

## Build Commands

### Maven (all modules)

```bash
mvn -f projects/maven/pom.xml validate
```

### Gradle (all modules)

```bash
cd projects/gradle
./gradlew tasks
```

> Note: Gradle wrapper is not yet added. Use local Gradle installation until wrapper is committed.
