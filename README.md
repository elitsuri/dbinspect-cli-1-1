# DBInspect CLI 1

> Database inspection CLI with schema diff, query runner, and export

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C, POSIX, SQLite, Makefile

## 🏗️ Architecture
Backend service with C, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/dbinspect-cli-1
cd dbinspect-cli-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
