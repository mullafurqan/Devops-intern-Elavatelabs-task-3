  # Build a Version-Controlled DevOps Project with Git 

Welcome to my DevOps project. This project demonstrates Git best practices including branching workflows, pull requests, documentation, and versioning.

---

## Objective

- Follow industry-standard Git workflow
- Maintain separate branches for development and production
- Use Pull Requests for merging
- Document all tasks in markdown
- Use tags for versioning
- Maintain clean repo using `.gitignore`

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Git | Version control & collaboration |
| GitHub | Remote repository + PR workflow |
| Markdown | Documentation |
| CMD / Terminal | Executing Git commands |

---

## Branching Strategy

| Branch | Description |
|--------|-------------|
| main | Production branch |
| dev | Development branch |
| feature-* | Individual features or tasks |

Example:
```
feature-jenkins-setup  
feature-ci-cd  
feature-docker-image  
```

---

## Git & PR Workflow Summary

1. Create feature branch from `dev`
2. Develop and commit changes
3. Push feature branch to GitHub
4. Create Pull Request into `dev`
5. Once tested, merge `dev` into `main`
6. Create version tags for stable releases

---

## Project Structure

```
DevOps-Project/
│
├── README.md
├── .gitignore
└── docs/
    └── task-doc.md
```

---

## Tags (Versioning)

Semantic versioning applied:
```
v1.0.0  → First stable version
```

---

## Documentation

Task details recorded in:
```
docs/task-doc.md
```

---

## Author

**Name:** Furqan Mulla  
**Role:** DevOps Enthusiast  
**Goal:** Mastering automation and CI/CD pipelines

---
