# Product Analysis Framework

Detailed methodology for comprehensive product analysis and clone assessment.

## Business Model Analysis

### Revenue Model Classification

**Subscription (SaaS)**
- Monthly/annual recurring revenue
- Tiered pricing common
- Indicators: pricing page shows "/month", "per user", "billed annually"
- Clone consideration: Predictable revenue, but requires retention focus

**Marketplace/Platform**
- Transaction fees (typically 5-20%)
- Two-sided markets
- Indicators: seller/buyer distinction, "take rate" mentions
- Clone consideration: Chicken-egg problem, network effects

**Freemium**
- Free tier with paid upgrades
- Conversion rates typically 2-5%
- Indicators: "Free forever" tier, feature gating
- Clone consideration: Need large user base for conversion

**Usage-Based**
- Pay per use/consumption
- Variable costs
- Indicators: credits, API calls, usage meters
- Clone consideration: Align costs with revenue

**One-Time Purchase**
- Single transaction
- May have maintenance fees
- Indicators: "buy once", lifetime deals
- Clone consideration: Need continuous customer acquisition

### Revenue Estimation Methods

**Employee-Based Estimate (SaaS)**
```
Employee count x $150-200k ARR per employee = Estimated ARR
```
Example: 50 employees x $175k = ~$8.75M ARR

**Funding-Based Estimate**
```
Last funding round / typical dilution (20-25%) = Post-money valuation
Revenue multiple for stage = Estimated revenue
```
Example: $10M Series A / 0.20 = $50M valuation; at 10x multiple = ~$5M ARR

**App Store Ranking Method**
- Top 10 in category: $1M+ monthly revenue
- Top 50: $100k-$1M monthly
- Top 200: $10k-$100k monthly

**Traffic-Based Estimate**
```
Monthly visitors x conversion rate x average order value = Monthly revenue
```

## Feature Analysis

### MVP Feature Identification

Ask: "What is the minimum feature set needed to deliver core value?"

**Feature Categorization:**
- **Core**: Essential for basic functionality (must clone)
- **Expected**: Users assume these exist (should clone)
- **Delighters**: Differentiation features (opportunity)
- **Unnecessary**: Over-engineering (skip)

### Competitive Feature Matrix

| Feature | Target | Competitor 1 | Competitor 2 | Priority |
|---------|--------|--------------|--------------|----------|
| Feature A | Yes | Yes | No | Must-have |
| Feature B | Premium | Yes | Yes | Important |
| Feature C | No | Yes | No | Opportunity |

### Feature Gap Analysis

Sources for identifying gaps:
1. **Review sites**: G2, Trustpilot - "I wish it had..."
2. **Reddit/forums**: User complaints and requests
3. **Support pages**: FAQ reveals common issues
4. **Competitor marketing**: "Unlike X, we have..."

## Market Analysis

### TAM/SAM/SOM Framework

**TAM (Total Addressable Market)**
- Everyone who could potentially use the product
- Usually from industry reports (Gartner, Statista)

**SAM (Serviceable Addressable Market)**
- Your target segment within TAM
- Geographic, demographic, or use-case specific

**SOM (Serviceable Obtainable Market)**
- Realistic market capture in 3-5 years
- Typically 1-5% of SAM for new entrants

### Market Signal Analysis

**Growing Market Indicators:**
- Increasing search volume (Google Trends)
- New VC investment in space
- New entrants launching
- Regulatory tailwinds
- Media coverage increasing

**Declining Market Indicators:**
- Consolidation (acquisitions)
- Reduced funding activity
- Pivot announcements from players
- Feature commoditization
- Negative press/regulatory pressure

## Technology Assessment

### Complexity Scoring

| Level | Characteristics | Clone Effort | Risk |
|-------|-----------------|--------------|------|
| Low | CRUD app, standard integrations | 2-4 weeks MVP | Low |
| Medium | Custom algorithms, multiple integrations | 1-3 months MVP | Medium |
| High | ML/AI core, real-time processing | 3-6 months MVP | High |
| Very High | Network effects, proprietary data | 6+ months | Very High |

### Tech Stack Investigation

**Detection Methods:**
1. **BuiltWith/Wappalyzer**: Frontend frameworks, analytics, CDN
2. **Job postings**: Required skills reveal stack
3. **GitHub**: Open source contributions
4. **Blog/docs**: Technical architecture posts
5. **LinkedIn**: Employee skills and backgrounds

### Build vs. Buy Analysis

For each major component, evaluate:
- Open source alternatives available?
- SaaS tools for this function?
- Custom development required?
- Maintenance complexity?

## Competitive Analysis

### Porter's Five Forces (Simplified)

1. **Rivalry**: How intense is competition?
2. **New Entrants**: How easy to enter? (your opportunity)
3. **Substitutes**: What else solves the problem?
4. **Buyer Power**: Can customers easily switch?
5. **Supplier Power**: Dependencies on platforms/APIs?

### Positioning Map

Plot competitors on two axes:
- X-axis: Simple ←→ Complex
- Y-axis: Budget ←→ Premium

Identify gaps for positioning your clone.

### Moat Assessment

| Moat Type | Strength | Clone Difficulty |
|-----------|----------|------------------|
| Network effects | Very Strong | Very Hard |
| Switching costs | Strong | Hard |
| Brand recognition | Medium | Medium |
| Economies of scale | Medium | Medium |
| Regulatory/licenses | Strong | Hard |
| Proprietary data | Strong | Hard |
| Patents | Strong | Avoid |
| First-mover | Weak | Easy to overcome |

## SWOT Analysis Template

### Strengths (Internal Positive)
Look for:
- Strong funding/backing
- Experienced team
- Unique technology
- Strong brand
- Large user base
- Good reviews

### Weaknesses (Internal Negative)
Look for:
- Poor reviews/ratings
- Limited features
- Bad UX complaints
- Slow development
- High pricing complaints
- Limited geography

### Opportunities (External Positive)
Look for:
- Underserved markets
- Missing features
- Pricing gaps
- Geographic expansion
- Regulatory changes
- Technology shifts

### Threats (External Negative)
Look for:
- Well-funded competitors
- Platform dependency
- Regulatory risks
- Market saturation
- Technology obsolescence

## Clone Strategy Framework

### Geographic Clone
- Target different country/region
- Localize language, payment, compliance
- Example: Clone US product for MENA market

### Vertical Clone
- Same solution, different industry
- Adapt terminology and workflows
- Example: Clone HR SaaS for healthcare staffing

### Pricing Clone
- Same features, different price point
- Target budget-conscious segment
- Example: Affordable alternative to enterprise tool

### Feature Clone
- Core features + missing gaps
- Address top complaints
- Example: Clone + mobile app that competitor lacks

### Niche Clone
- Specialized version for subset
- Deep expertise in narrow area
- Example: Generic CRM → Real estate CRM
