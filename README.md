# My Fullstack Projects

This directory lists various fullstack projects.

## Projects Overview

| Project Name                      | Description | Link |
| ---------------------------------- | ----------- | ---- |
| react-node-graphql-frontend                         | Fullstack React Node App with GraphQL | [Link to repo](https://github.com/andrepbo/react-node-graphql-frontend) |
| react-node-graphql-backend                         | Fullstack React Node App with GraphQL | [Link to repo](https://github.com/andrepbo/react-node-graphql-backend) |

## How to Use

To get started, clone a project:

```bash
git clone https://github.com/andrepbo/[project-name].git
cd [project-name]
```

Follow the specific setup instructions for each project.

## Using docker-compose
### Create a .env.local file in the same directory as docker-compose.yml and define:

```ini
BACKEND_SOURCE=/path/to/custom/backend
FRONTEND_SOURCE=/path/to/custom/frontend
```

If you don’t set these variables, Docker Compose will default to ./backend and ./frontend.

### Start the Services
```bash
docker-compose up -d
```

### Stop the Services
```bash
docker-compose down
```

## Contribution

Suggestions and improvements are always welcome! If you'd like to contribute or report any issues, feel free to open a pull request or create an issue in the respective project repository.