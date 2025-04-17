# Express + TypeScript Project

## Introduction

This project demonstrates how to set up a scalable and modern backend using **Express** and **TypeScript**. It also includes configuration for environment variables and instructions for further development.

---

## Features

- **Express**: Fast and minimalist web framework for Node.js.
- **TypeScript**: Type-safe JavaScript for better development experience.
- **dotenv**: Environment variable management.
- **Modular Structure**: Controllers and routes are separated for scalability.

---

## Prerequisites

Make sure you have the following installed:

- **Node.js** (>= 14.x)
- **npm** (>= 6.x) or **yarn**

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd express-typescript-prisma
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add:

```
DATABASE_URL="file:./dev.db"
PORT=3000
```

### 4. Start the Server

For development mode:

```bash
npm run dev
```

For production mode:

```bash
npm run build
npm start
```

---

## Folder Structure

```
/src
  ├── controllers/
  │   ├── user.controller.ts
  ├── routes/
  │   ├── user.routes.ts
  ├── server.ts
/public
  ├── index.html
.env
```

---
