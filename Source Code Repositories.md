At Galenica, we use GitHub for version control and collaboration. Our repository structure follows best practices to ensure clarity and ease of navigation1:

text
galenica-repo/
├── src/
│   ├── backend/
│   ├── frontend/
│   └── shared/
├── tests/
├── docs/
├── scripts/
├── .github/
│   └── workflows/
├── .gitignore
├── README.md
├── CONTRIBUTING.md
└── LICENSE
We maintain separate repositories for different projects and microservices. Each repository adheres to the following guidelines:

The src directory contains all source code, divided into logical subdirectories.

The tests directory houses all unit and integration tests.

The docs folder contains project documentation.

The scripts directory includes build and deployment scripts.

The .github/workflows directory contains our CI/CD pipeline configurations.

We use feature branches for development and enforce pull requests for code reviews before merging into the main branch
