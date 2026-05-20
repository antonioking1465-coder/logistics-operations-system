# Logistics Operations System

Enterprise-grade logistics management platform for fleet tracking, dispatch optimization, and financial reporting.

## Features

- **Operations Dashboard** - Real-time fleet status, vehicle health, and performance metrics
- **Dispatch Management** - Load creation, assignment, optimization, and tracking
- **Fleet Tracking** - Real-time GPS tracking, maintenance scheduling, fuel monitoring
- **Financial Reporting** - Revenue analytics, expense tracking, profitability analysis
- **Real-time Updates** - WebSocket-based live data streaming
- **Role-based Access Control** - Admin, Dispatcher, Driver, and Accountant views

## Tech Stack

- **Frontend:** React 18 with TypeScript
- **Backend:** Node.js/Express with TypeScript
- **Database:** PostgreSQL
- **Real-time:** Socket.io
- **Deployment:** Docker + Docker Compose

## Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Docker & Docker Compose

### Installation

```bash
# Clone repository
git clone https://github.com/antonioking1465-coder/logistics-operations-system.git
cd logistics-operations-system

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env

# Initialize database
npm run db:migrate

# Start development servers
npm run dev
```

### Docker Compose

```bash
docker-compose up -d
```

## Login Credentials

- **Email:** admin@logisticsops.com
- **Password:** password

## Project Structure

```
logistics-operations-system/
├── frontend/                 # React UI application
├── backend/                  # Express API server
├── database/                 # PostgreSQL schemas and seeds
├── docker-compose.yml        # Container orchestration
└── README.md
```

## Key Modules

### 1. Operations Dashboard
- Real-time fleet visualization
- Vehicle status monitoring
- KPI tracking

### 2. Fleet Management
- Vehicle tracking
- Maintenance scheduling
- Location history

### 3. Dispatch Management
- Load creation and assignment
- Route tracking
- Status updates

### 4. Financial Reporting
- Revenue analytics
- Expense tracking
- Profitability by vehicle

## Support

For issues, create a GitHub issue in this repository.

## License

Proprietary - A&A Kings LLC & M2fifty Logistics
