# 🐉 Poke-Storage API

A full-stack backend integration that bridges the **PokeAPI** with a local database. This service allows users to fetch Pokémon data and persist their favorite Pokémon names using a **Node.js** and **Express** architecture.

---

## 🛠 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Runtime** | Node.js |
| **Framework** | Express.js |
| **Database** | MongoDB / PostgreSQL (ORM: Mongoose / Sequelize) |
| **API Source** | [PokeAPI](https://pokeapi.co/) |
| **HTTP Client** | Axios |

---

## ✨ Features

* **PokeAPI Integration:** Seamlessly fetch real-time data from the official Pokémon API.
* **Data Persistence:** Save Pokémon names and metadata to a database to keep track of your "caught" collection.
* **RESTful Routing:** Clean API endpoints for fetching and storing data.
* **Error Handling:** Middleware-based error management for failed API lookups or DB connection issues.

---

## 🚀 Getting Started

### 1. Prerequisites
* **Node.js** (v18 or higher recommended)
* **Database**: Ensure your local or cloud database instance is running.

### 2. Installation
```bash
# Clone the repository
git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)

# Navigate to project directory
cd your-repo-name

# Install dependencies
npm install
