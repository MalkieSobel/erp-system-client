# ERP System – Frontend

Frontend for a custom ERP system I built as a freelance project for a real client (MEfirst). The client uses it to manage their projects from first contact to delivery.

## What it does

- **Projects and stages** – track each project through its stages
- **Products** – add and edit the client's product catalog
- **Agents and contacts** – manage agents, customers and users
- **Documents** – attach and open documents per project
- **Tasks (todos)** – personal task lists
- **Summaries** – reports across projects
- **Login and roles** – JWT-based auth with an auth context

## Stack

- React, React Router
- JWT auth (jwt-decode)
- Talks to a Node.js + SQL backend deployed on Google Cloud Run
- Later moved the hosting to Lovable to cut costs

## Run locally

```bash
npm install
npm start
```

Opens at http://localhost:3000.
