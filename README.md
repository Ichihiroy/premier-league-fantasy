# Premier League Fantasy Card Game⚽️

A full-stack fantasy football app where users can manage teams, buy players, and compete in a Premier League-inspired fantasy game. Built with modern web technologies for speed, scalability, and a smooth user experience.

---

## 🌟 Features

* **User Management**: Sign up, log in, and manage your account securely.
* **Player Marketplace**: Buy and sell players, track user balance, and optimize your squad.
* **Fantasy Teams**: Build your team with real Premier League players.
* **Responsive UI**: Works seamlessly on desktop, tablet, and mobile.
* **Real-time Updates**: Stay updated on player stats and leaderboard changes.

---

## 🛠️ Tech Stack

| Layer              | Technology                                 |
| ------------------ | ------------------------------------------ |
| Frontend           | React 18, Vite, Tailwind CSS, React Router |
| Backend            | Node.js, Express, TypeScript               |
| Database           | PostgreSQL                                 |
| Caching  | Redis                                      |
| Deployment         | Docker, IaC scripts                        |

---

## 🚀 Getting Started

### Prerequisites

* Node.js v18+
* PostgreSQL
* Redis (optional, for caching)

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd premier-league-fantasy
```

2. Copy `.env.example` to `.env` and fill in your values.

3. Install dependencies:

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

4. Start development servers:

```bash
# Backend
cd backend
npm run dev

# Frontend
cd ../frontend
npm run dev
```

Open your browser at `http://localhost:5173` to view the app.

---

## 🏗️ Project Structure

```
fantasy-cards/
├─ frontend/        # React app (Vite)
├─ backend/         # Node/Express API
├─ infra/           # Docker, IaC, deploy scripts
├─ docs/            # API spec, runbooks
├─ .github/         # CI/CD pipelines
├─ .env.example     # Sample environment variables
├─ LICENSE
└─ README.md
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
