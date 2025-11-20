# CommunityInsight.AI

> Democratizing civic intelligence for America's 19,500 municipalities through autonomous AI agents

[![Production Status](https://img.shields.io/badge/status-production-success)](https://communityinsight.ai)
[![Security Score](https://img.shields.io/badge/security-98%2F100-brightgreen)](https://communityinsight.ai/security)
[![Kaggle Competition](https://img.shields.io/badge/Kaggle-Agents%20for%20Good-blue)](https://www.kaggle.com/competitions/agents-intensive-capstone-project)

## 🌟 Overview

CommunityInsight.AI is a production-ready civic intelligence platform that empowers municipal governments, nonprofits, and community organizations with AI-driven insights. We solve the critical data gap facing 95% of U.S. municipalities who can't afford $50K-$250K enterprise analytics platforms.

**Live Platform**: [communityinsight.ai](https://communityinsight.ai)

## 🎯 Mission

While large cities afford expensive enterprise data platforms, 95% of America's municipalities rely on spreadsheets and intuition for critical decisions. CommunityInsight.AI democratizes access to powerful civic analytics through ethical AI, making sophisticated community intelligence accessible to every municipality—regardless of size or budget.

## 🤖 5 Autonomous AI Agents

Our platform features specialized AI agents that work 24/7 for your community:

1. **Survey Builder Agent** (Google Gemini) - Generate professional survey templates with customizable Point-of-View options
2. **Grant Discovery Agent** (Claude 4.5) - Automatically discover grant opportunities and generate compelling proposals
3. **Ballot Research Agent** (Google Civic API) - Comprehensive candidate research using nationwide election data
4. **School Discovery Agent** (Google Maps API) - Discover schools serving any U.S. address with boundary-aware intelligence
5. **Community Insight Agent** (Multi-source) - Analyze community data from social media, 311 requests, and demographics

## 🏗️ Technical Architecture

### Tech Stack

**Frontend**
- React 18 + TypeScript
- Tailwind CSS + shadcn/ui components
- TanStack Query for state management
- Wouter for routing

**Backend**
- Node.js + Express.js (TypeScript)
- PostgreSQL with Drizzle ORM
- Neon Database for managed PostgreSQL

**AI & APIs**
- Claude 4.5 Sonnet (Anthropic) - Complex reasoning tasks
- Google Gemini - Speed/cost optimization
- Perplexity AI (sonar-pro) - Real-time research
- OpenAI - Specific use cases

**Federal Data APIs**
- U.S. Census Bureau (American Community Survey)
- USASpending.gov API
- Google Civic Information API
- CDC Social Vulnerability Index
- Federal grant databases (Grants.gov, SAM.gov)

**Social Media & Community Data**
- KWatch.io - Social media monitoring
- Facebook Graph API - Community engagement
- Reddit API - Community discussions
- YouTube Data API - Video content analysis

### System Design Principles

- **Authentic Data Only**: No mock data, only verified government and public sources
- **Ethical AI**: Transparency, explainability, and responsible data usage
- **Nationwide Coverage**: Automated discovery for all 19,500+ U.S. municipalities
- **Scalable Architecture**: Built for production scale from day one
- **Security-First**: 98/100 security score with comprehensive hardening

### Key Features

- Natural language query interface
- Multi-source data integration
- Automated municipal discovery
- Grant-ready report generation
- Real-time community trend alerts
- Social media monitoring
- Transparent token-based pricing
- Mobile-first responsive design

## 📊 Production Readiness

**Status**: ✅ VALIDATED & APPROVED FOR LAUNCH (November 13, 2025)

- **Security Score**: 98/100
- **Validation Coverage**: 7 phases, 11 feature areas, 5 AI agents (100% operational)
- **Performance**: Optimized with caching, indexing, connection pooling
- **Reliability**: Comprehensive disaster recovery and backup procedures

### Infrastructure

- **Database Performance**: Production-ready for 1M+ rows with 23 indexes
- **API Caching**: 70% reduction in DB queries, 50% reduction in Census API calls
- **Rate Limiting**: Global (300 req/min) + feature-specific limiters
- **Error Monitoring**: Real-time metrics with automated alerting
- **Security**: Helmet.js CSP, HSTS, CSRF protection, endpoint authentication

## 🚀 Getting Started

### Prerequisites

```bash
node >= 18.x
postgresql >= 14.x
```

### Installation

```bash
# Clone the repository
git clone https://github.com/stanchat/communityinsight-kaggle.git

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your API keys (see documentation)

# Run database migrations
npm run db:push

# Start development server
npm run dev
```

### Required API Keys

- `ANTHROPIC_API_KEY` - Claude AI
- `GOOGLE_MAPS_API_KEY` - Google Maps and Civic API
- `DATABASE_URL` - PostgreSQL connection string
- `OPENAI_API_KEY` - OpenAI (optional)
- `PERPLEXITY_API_KEY` - Perplexity AI (optional)

See `.env.example` for complete list.

## 📖 Documentation

- **Architecture Overview**: See [docs.html](https://stanchat.github.io/communityinsight.ai/docs.html)
- **API Documentation**: Available at `/api/docs` when running locally
- **Production Deployment**: See `replit.md` for comprehensive runbook
- **Security Audit**: 98/100 score with detailed findings in codebase

## 🎓 Kaggle Competition

CommunityInsight.AI was submitted to Kaggle's "Agents for Good" competition, showcasing:

- 5 autonomous AI agents serving civic needs
- Production-ready architecture with authentic government data
- Nationwide coverage for 19,500+ U.S. municipalities
- Open-source contribution to civic technology

**Competition Entry**: [View on Kaggle](https://www.kaggle.com/competitions/agents-intensive-capstone-project/writeups/communityinsight-ai-democratizing-civic-intellige)

## 💡 Use Cases

**Municipal Governments**
- Track community sentiment and emerging issues
- Discover grant opportunities for infrastructure projects
- Research candidates and ballot measures
- Generate data-driven reports for council meetings

**Nonprofit Organizations**
- Find grant funding opportunities
- Analyze community needs and feedback
- Generate professional survey templates
- Create compelling grant proposals with AI assistance

**Community Advocates**
- Monitor local government social media
- Track 311 service requests
- Research school boundaries and demographics
- Access comprehensive community data

## 🛡️ Security & Privacy

- All data from authenticated government APIs only
- No personally identifiable information (PII) stored
- Comprehensive audit logging for transparency
- Regular security assessments
- GDPR and compliance-ready architecture

## 📈 Metrics & Scale

- **Coverage**: 19,500+ U.S. municipalities
- **AI Agents**: 5 autonomous agents operational
- **Federal APIs**: 3+ integrated data sources
- **Cost Reduction**: 50% vs. traditional platforms
- **Uptime**: Production monitoring with SLA targets

## 🤝 Contributing

We welcome contributions! This is an open-source civic technology project.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available for civic good.

## 👥 Team

**Stanley D Chatman** - Founder & CEO  
Senior tech leader and civic innovation expert with 25+ years of experience leading digital product teams and building AI-powered solutions for communities.

**Stan Tarr** - Chief Operating Officer  
20+ years in insurance, tech, and operations leadership.

## 📧 Contact

- **Website**: [communityinsight.ai](https://communityinsight.ai)
- **Email**: [Contact Us](https://communityinsight.ai/contact)
- **GitHub**: [stanchat/communityinsight-kaggle](https://github.com/stanchat/communityinsight-kaggle)

## 🙏 Acknowledgments

- Kaggle "Agents for Good" competition
- U.S. Census Bureau for open data APIs
- Google Civic Information API team
- Open-source civic technology community

---

**Built with ethical AI practices for civic good** | Patent Pending
