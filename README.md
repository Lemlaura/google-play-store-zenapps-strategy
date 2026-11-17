# Google Play Store Market Strategy for ZenApps

> Data-driven go-to-market strategy to help ZenApps launch profitable apps.

**Live Analysis:** `play_store_analysis.ipynb`

### The Business Question
ZenApps, a fictional mobile startup, needed to answer: *Where should we build our next app to maximize downloads and revenue?* With 3M+ apps on the Play Store, guessing is expensive.

### What I Did
Analyzed 10,841 Play Store apps to identify profitable opportunities.

**Data Processing:**
- Cleaned installs (1,000+ to 1B+), pricing, ratings, and review data
- Fixed data type issues, handled nulls in Rating/Category
- Engineered features: Revenue estimate, Price Tier, Rating buckets

**Analysis:**
- Category saturation vs demand analysis
- Free vs Paid monetization model breakdown
- Rating, Reviews & Installs correlation for virality drivers
- User sentiment and pricing strategy

### Key Findings That Drive Strategy

1.  **Market is Free-Dominant:** 92% apps are free. Revenue comes from Ads/IAP, not upfront price.
2.  **Winner Categories:** GAME, FAMILY, TOOLS drive 45% of installs but are highly saturated.
3.  **Sweet Spot:** 4.3 - 4.6 rating = highest installs. Below 4.0 gets penalized by algorithm.
4.  **Pricing:** $0.99-$4.99 paid apps have lowest success rate. Either go Free or Premium >$5.

### My Recommendation to ZenApps
**Build a Freemium Productivity/Health App:**
- Low competition, high retention
- Target 4.5+ rating via UX focus
- Monetize via subscription, not paid download
- Launch in Family + Tools intersection

### Stack
Python | Pandas | Data Visualization | Business Strategy

### Repo Structure