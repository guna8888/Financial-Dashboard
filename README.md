# Financial Dashboard 💰

## Vision
A free, open-source personal finance app that helps users understand their spending, manage budgets, and get AI-powered insights—without subscriptions.

## Problem We're Solving
Most people:
- Don't know where their money goes
- Forget expenses until month-end
- Pay for features they could get free
- Miss opportunities to optimize spending

## What You Get
- 📊 **Expense Tracking**: Log spending with categories
- 📈 **Analytics**: Visual breakdown of spending patterns
- 💡 **AI Insights**: Smart categorization, anomaly detection, predictions
- 💳 **Budget Management**: Set limits, get alerts
- 🔒 **Privacy First**: Your data is yours (open-source)

## Tech Stack
- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, TypeScript
- **Database**: PostgreSQL 15
- **ORM**: Prisma
- **AI/ML**: TensorFlow.js, Python microservices (Phase 3+)
- **Deployment**: Vercel (frontend), Railway (backend)

## Getting Started

### Prerequisites
- macOS with M4 (or Intel)
- Node.js v25+
- PostgreSQL 15+
- Git

### Installation

```bash
# Clone this repo
git clone https://github.com/YOUR_USERNAME/Financial-Dashboard.git
cd Financial-Dashboard

# Frontend setup
cd frontend
npm install
npm start

# Backend setup (in another terminal)
cd ../backend
npm install
npm run dev
```

### Project Structure
cat > CHANGELOG.md << 'EOF'
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added
- Initial project setup
- GitHub repository
- Project structure (frontend, backend, database folders)
- Documentation (README, CHANGELOG)

### Planned
- User authentication system
- Expense CRUD operations
- Category management

---

## [0.0.1] - 2026-09-22

### Added
- Project initialized
- Base folder structure created
- Documentation framework started

### Status
🔴 Foundation Phase - Just starting!

---

**Version Format**: [MAJOR].[MINOR].[PATCH]
- MAJOR: Big features (e.g., AI integration done)
- MINOR: Medium features (e.g., authentication done)
- PATCH: Bug fixes (e.g., fixed login bug)
