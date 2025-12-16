# ☁️ Cloud App

Real-time AWS region optimization for smarter deployment decisions.

## Overview

Cloud App helps developers choose the best AWS region by combining live latency testing, current pricing data, spot availability trends, service health status, and carbon intensity scores in a single dashboard.

## Year 1 Features

**Core Functionality**
- Browser-based latency testing to all AWS regions
- Real-time EC2 pricing (on-demand, reserved, spot)
- Intelligent recommendations based on speed, cost, and sustainability
- 30-day spot instance availability trends
- Regional service health monitoring
- Carbon intensity scoring per region

**Smart Recommendations**
- Multi-factor scoring: latency + cost + availability + environmental impact
- Personalized suggestions based on workload requirements
- Side-by-side region and instance type comparisons
- Savings calculator for migration scenarios

**User Experience**
- Single-page dashboard with clean interface
- Adjustable priority weights (speed vs. cost vs. carbon)
- Export results as JSON/CSV
- Mobile responsive design

## Tech Stack

Backend: Python (FastAPI) | Frontend: HTML/CSS/JS | Data: AWS APIs (Pricing, EC2, Health)

## Goal

Make AWS region selection data-driven instead of guesswork, helping developers reduce costs and improve performance from day one.
