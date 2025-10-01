# Competitor Research: OddAlerts & OddsJam

## Overview
This document captures observed product areas, user flows, and design conventions from two leading betting analytics platforms—OddAlerts and OddsJam. The goal is to mirror their standard of polish while tailoring the experience to our product vision.

## Core Value Propositions
- **Real-time odds intelligence** – Both platforms surface the best prices across sportsbooks, highlighting market movement and line discrepancies.
- **Personalized alerts** – Automated notifications (email, SMS, push, and in-app) based on user-defined triggers such as line movement, value percentage, or new arbitrage opportunities.
- **Actionable insights** – Positive Expected Value (EV) bets, arbitrage calculators, and recommended picks derived from live data and historical performance models.
- **Comprehensive bet tracking** – Tools to log, categorize, and analyze personal betting performance with profit/loss reporting.
- **Education & community** – Articles, video tutorials, and private community channels that teach sports betting strategy and product usage.

## Information Architecture & Page-Level Features

### 1. Landing / Marketing Site
- Hero banner with a live odds preview and clear value proposition.
- Testimonials, trust signals, and integration logos (sportsbooks, data providers).
- Pricing plans with feature comparison tables and call-to-action (CTA) buttons for “Start Free Trial” and “Book a Demo”.
- Embedded explainer video demonstrating workflow.

### 2. Dashboard (Post Login)
- Personalized overview displaying:
  - Upcoming matches of interest (based on user preferences).
  - Recent alerts and recommended bets.
  - Snapshot of bankroll and recent performance.
- Modular cards that can be rearranged or toggled.
- Quick filters for sports, leagues, and bet types.

### 3. Odds Screen / Market Explorer
- Multi-sport navigation bar with sub-filters for leagues and bet markets.
- Live odds tables with columns for each sportsbook, highlighting the best line per market.
- Toggle between decimal, American, and fractional odds.
- Visual indicators for line movement (color-coded arrows, sparkline graphs).
- Bulk selection tool to add bets to tracker or alert lists.

### 4. Positive EV & Arbitrage Tools
- Table of opportunities ranked by EV %, with filters for minimum edge, hold percentage, and sportsbook availability.
- Detailed modal per opportunity showing implied probabilities, recommended stake, and historical trend graph.
- Integration with bet tracker (one-click to log outcome) and alert system (subscribe to future updates on the same market).
- Arbitrage calculator supporting multiple legs and stake allocation suggestions.

### 5. Alerts & Automation Center
- Rule builder interface enabling users to create triggers based on odds movement, EV threshold, or game events.
- Notification channel management (email, SMS, Discord, in-app).
- Alert history timeline with filtering by status (sent, snoozed, triggered, dismissed).
- Template library of popular alert recipes for quick setup.

### 6. Bet Tracker & Analytics
- Entry form supporting manual input and direct import from integration APIs.
- Categorization by sport, bet type, sportsbook, and custom tags.
- Performance dashboards: ROI over time, closing line value (CLV), hit rate by market, bankroll projection.
- Export to CSV, Google Sheets, or third-party bankroll management tools.
- Social sharing options for big wins or streaks.

### 7. Educational Hub
- Resource library with filters by sport, proficiency level, and topic (e.g., bankroll management, line shopping).
- Video tutorials embedded via modular cards.
- Live or recorded webinars schedule, with registration links.
- Glossary of betting terms integrated across the app via tooltip system.

### 8. Community & Support
- In-app chat or Discord/Slack community integration.
- Ticketing system for support with SLA indicators.
- Status page displaying data provider health and sportsbook connectivity.
- Feedback portal for feature requests, using upvote mechanisms.

### 9. Pricing & Subscription Management
- Tiered plans (Starter, Pro, Elite) with access controls for features (e.g., number of alerts, sports coverage, data refresh frequency).
- Self-service billing portal supporting trials, coupons, and upgrades/downgrades.
- Usage dashboards illustrating current allotments (alerts used, API calls, seats).

## Design & UX Patterns
- **Dark mode default** with neon accent colors for key data points; light mode optional.
- **Data-dense tables** with sticky headers, horizontal scrolling for many sportsbooks, and quick search.
- **Responsive layout** that reorganizes cards for tablets and mobile; dedicated native mobile apps supplement the web experience.
- **Progressive disclosure**: simple summary rows expand into detail modals rather than navigating away.
- **Guided onboarding**: checklist with progress meter, tooltips, and sample alerts to demonstrate functionality.
- **Contextual help**: inline info icons linking to knowledge base articles and videos.

## Integration & Technical Considerations
- Partnerships with major sportsbooks (DraftKings, FanDuel, Caesars, BetMGM) for deep linking to place bets.
- Real-time feeds from odds providers (Sportradar, Don Best, etc.) with websocket updates.
- Authentication via email/password, SSO (Google, Apple), and optional 2FA.
- API endpoints for programmatic access to odds, alerts, and tracking data.
- Webhooks for sending alert events to third-party automation tools (Zapier, Slack).

## Differentiation Opportunities for Our Product
- Emphasize customizable dashboards with drag-and-drop cards and saved layouts.
- Provide machine learning-driven projections with transparency (feature importance, confidence intervals).
- Offer collaborative bet tracking for groups or syndicates, including shared bankrolls.
- Create a public-facing odds portal with SEO-friendly pages to drive organic traffic.
- Introduce gamification (achievement badges, streak tracking) to encourage engagement.

## Next Steps
1. **Map MVP scope** against these feature categories, prioritizing high-impact modules (Odds Screen, Alerts, Bet Tracker).
2. **Design system audit** to define typography, color palette, card/table components inspired by competitor aesthetics.
3. **Data provider evaluation** ensuring low-latency odds feeds and reliable integrations.
4. **Usability testing plan** with target users familiar with OddAlerts/OddsJam to benchmark against their workflows.
5. **Roadmap sequencing** to deliver incremental value while building towards parity with competitor suites.

