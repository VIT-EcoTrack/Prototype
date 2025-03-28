Eco Track ♻️

Smart Waste Management with Blockchain & AI



Eco Track is a next-generation digital platform that enhances waste management through blockchain transparency and AI-driven analytics. Our system incentivizes responsible recycling, tracks waste-to-energy conversion, and helps municipalities optimize collection processes in real-time.

🌟 Key Features

🟢 Blockchain Waste Tracking

Immutable Records: Tamper-proof logging of all waste submissions using blockchain technology.

QR-Code Integration: Unique QR-codes for waste items to ensure accurate tracking at collection points.

Public Ledger: Transparent and auditable records for municipal and community verification.


<div align="center">
<img width="1280" alt="Screenshot" src="https://github.com/user-attachments/assets/f67cf56f-f214-443d-83f6-4878fb8fcfc5" />
</div>


🟢 EcoToken Rewards

Incentivized Recycling: Earn ERC-20 EcoTokens for verified waste submissions.

Utility & Redemption: Use tokens for local discounts, eco-initiatives, or donations.

Polygon Network: Fast, low-cost transactions with Ethereum Layer 2 integration.

<div align="center">
<img width="1280" alt="Screenshot" src="https://github.com/user-attachments/assets/6cbb7fcc-2681-45a5-a0f0-8197f1209b6b" />
</div>

🟢 Waste Analytics Dashboard

Real-Time Visualization: Dynamic heatmaps displaying waste generation patterns.

AI Route Optimization: Intelligent algorithms for optimizing collection truck routes.

Predictive Insights: Forecasting tools to identify future waste hotspots and streamline resource allocation.

<div align="center">
<img width="1280" alt="Screenshot" src="https://github.com/user-attachments/assets/4d269a0c-753d-48ba-a8f3-aacd5c81105a" />
</div>

🟢 Community Tools

Illegal Dumping Reports: Crowdsourced reporting and monitoring of waste violations.

Community Clean-Up: Support for organizing and promoting environmental clean-up drives.

Educational Resources: Access to information on sustainable waste management practices.

<div align="center">
<img width="1280" alt="Screenshot" src="https://github.com/user-attachments/assets/ea090504-0651-4bc5-b86b-1fa6fbfdd29e" />
</div>

🎨 Frontend Implementation

Technologies Used

Framework: Next.js 14 (App Router for optimized routing and performance)

Styling: Tailwind CSS with Shadcn/ui components for rapid, consistent UI development

State Management: Zustand for lightweight and scalable global state handling

Maps: Mapbox GL JS for high-performance interactive waste heatmaps

Charts: Nivo React visualization library for analytical and interactive charts

Core User Interfaces

User Dashboard

Personalized recycling history with visual analytics

Token balance overview and reward redemption portal

Waste submission interface with QR-code and image upload support

Waste Heatmap

Interactive, color-coded waste density visualization

Dynamic filtering by waste categories (plastic, organic, hazardous, etc.)

Crowdsourced problem area tagging and community feedback

Admin Portal

Submission verification queue with blockchain integration

Optimized route planning for municipal waste collection vehicles

Data-driven analytics for energy conversion and sustainability tracking

UI/UX Principles

Mobile-First: Fully responsive design for optimal experience across devices

Accessibility: WCAG 2.1 AA compliance for inclusive user interaction

Theming: Support for light/dark mode preferences

Localization: Regional formatting for dates, numbers, and languages

🔧 Backend Services

Architecture Overview

Authentication: Secure wallet and email-based authentication via NextAuth.js

API Layer: tRPC for type-safe and efficient API endpoints

Database: PostgreSQL with TimescaleDB extension for time-series data

Blockchain Integration: Smart contracts deployed on Ethereum and Polygon

AI Microservices: Python-based AI models for waste classification and route prediction

System Workflow

Users submit waste with QR-codes and images via the dashboard.

Data is recorded on the blockchain and verified by the admin portal.

AI algorithms analyze waste patterns to optimize collection.

Users receive EcoTokens for approved submissions, redeemable for rewards.

🚀 Getting Started

Prerequisites

Node.js v18+ for backend and frontend execution

PostgreSQL for database management

MetaMask (or compatible) for blockchain wallet interactions

Installation

git clone https://github.com/your-repo/ecotrack.git
cd ecotrack
npm install
cp .env.example .env
npm run dev

Environment Configuration

Ensure to populate the .env file with the following variables:

DATABASE_URL: PostgreSQL connection string

NEXTAUTH_SECRET: Secret for authentication encryption

POLYGON_RPC_URL: Polygon RPC endpoint for blockchain interactions

MAPBOX_ACCESS_TOKEN: API key for Mapbox services

📜 Smart Contracts

Contract Modules

WasteLedger.sol: Handles waste submission logging and validation

EcoToken.sol: ERC-20 token implementation for EcoToken rewards

EnergyProof.sol: Tracks and verifies waste-to-energy conversions

Deployment Details

Network: Polygon (Ethereum Layer 2)

Audit: Undergoing security review for contract integrity

Explorer: Transactions can be tracked via Polygonscan
