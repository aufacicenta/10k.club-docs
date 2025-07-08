# Explorer Submission Process & Rewards

This document outlines the complete process for Explorers to submit investment opportunities, the reward system for quality submissions, and the community voting mechanism.

## Submission Platform & Method

### Primary Submission Channel: Discord Integration

**Platform**: Private Discord channel `#opportunity-submissions` (Explorer-only access)

**Submission Bot**: Custom Discord bot with structured interface
- **Template Enforcement**: Ensures all REQUIRED fields are completed
- **File Upload Support**: Direct attachment of documents and photos (up to 25MB per file)
- **Auto-Validation**: Real-time checking for completeness
- **Status Tracking**: Live updates (submitted → under review → approved/rejected)
- **Version Control**: Track revisions and updates to submissions

### Submission Workflow

#### Step 1: Template Preparation
1. **Download Template**: Access Real Estate Opportunity Template from `#explorer-resources`
2. **Complete Offline**: Fill out all REQUIRED sections thoroughly
3. **Gather Documents**: Prepare all supporting documentation
4. **Quality Check**: Self-review using internal checklist

#### Step 2: Initial Submission
1. **Bot Command**: Use `/submit-opportunity` command in `#opportunity-submissions`
2. **Template Upload**: Attach completed opportunity report
3. **Document Upload**: Attach all supporting documents
4. **Auto-Validation**: Bot checks for completeness and required fields
5. **Confirmation**: Receive submission ID and tracking information

#### Step 3: Pre-Review Process
1. **Peer Review**: Random assignment of 2 other Explorers for initial feedback
2. **24-Hour Window**: Peer reviewers provide quality assessment
3. **Quality Score**: Receive 1-10 quality rating
4. **Revision Opportunity**: Address feedback before public submission

#### Step 4: Public Submission
1. **Community Preview**: 48-hour preview in `#opportunity-preview`
2. **Initial Feedback**: Community members can ask questions
3. **Final Adjustments**: Last chance to refine submission
4. **Formal Submission**: Moves to official voting process

## Explorer Reward System

### Immediate Submission Rewards

#### Completion Bonus: $50 USDC
**Criteria**: 
- All REQUIRED template sections completed
- Supporting documentation attached
- Passes automated validation checks
- Explorer certification signed

**Payment**: Within 24 hours of successful submission
**Purpose**: Compensate time investment and encourage quality submissions
**Frequency**: Per submission (regardless of approval outcome)

#### Quality Bonus: $25 USDC
**Criteria**:
- Peer review score ≥ 8.0/10
- Exceptional research depth
- Clear, professional presentation
- Comprehensive risk analysis

**Payment**: After peer review completion
**Purpose**: Reward exceptional effort and thoroughness
**Evaluation**: Based on peer Explorer feedback

### Performance-Based Rewards

#### Tier 1: Community Approval Reward
**Trigger**: Opportunity receives ≥60% approval in community vote
**Reward**: $200 USDC
**Benefits**: 
- "Approved Explorer" Discord badge (30 days)
- Priority review queue for future submissions
- Recognition in monthly newsletter

**Payment Timeline**: Within 48 hours of vote conclusion

#### Tier 2: Investment Execution Reward
**Trigger**: DAO actually deploys funds into approved opportunity
**Reward**: 0.5% of total investment amount
**Examples**:
- $100,000 investment = $500 reward
- $500,000 investment = $2,500 reward
- $1,000,000 investment = $5,000 reward

**Payment Timeline**: Upon confirmed fund deployment
**Verification**: Auditor-confirmed transaction records

#### Tier 3: Performance Success Reward
**Trigger**: Project meets or exceeds projected ROI after 12 months
**Reward**: 1% of net profits for first 2 years
**Calculation**: Based on auditor-verified financial reports
**Purpose**: Long-term alignment with project success

**Example Calculation**:
```
Project: $500K investment, $75K annual net profit
Explorer Reward: $750 per year for 2 years = $1,500 total
```

### Monthly Performance Incentives

#### Top Explorer Award: $1,000 USDC
**Criteria**: Most approved opportunities in the month
**Scoring System**: Quality-weighted (approval rate × quality scores)
**Recognition**: Featured in Discord, special role color
**Announcement**: First Monday of each month

#### Regional Explorer Bonus: $300 USDC
**Criteria**: Best opportunity from each major region monthly
**Regions**: North America, South America, Europe, Asia, Africa, Oceania
**Purpose**: Encourage global diversification
**Selection**: Based on community vote scores and regional investment focus

#### Accuracy Master Bonus: $500 USDC
**Criteria**: ROI predictions within 2% of actual performance (after 12 months)
**Tracking**: Long-term performance monitoring
**Recognition**: "Crystal Ball" Discord badge
**Payment**: Annual assessment and reward

## Community Voting Process

### Phase 1: Initial Community Review (48 hours)

**Participants**: All 10k.club members
**Platform**: Discord thread in `#opportunity-discussion`
**Purpose**: 
- Initial feedback and questions
- Clarification requests
- Community sentiment gauge

**Activities**:
- Q&A with submitting Explorer
- Preliminary risk assessment discussions
- Market knowledge sharing from local members
- Technical questions and clarifications

### Phase 2: Auditor Assessment (5 business days)

**Participants**: 2-3 assigned Auditors (randomly selected)
**Process**:
1. **Financial Analysis**: Verify all calculations and projections
2. **Market Research**: Validate comparable sales and rental data
3. **Risk Assessment**: Evaluate and score identified risks
4. **Legal Review**: Assess legal structure and compliance requirements
5. **Due Diligence**: Confirm supporting documentation authenticity

**Deliverable**: Formal Auditor Report with recommendation:
- ✅ **APPROVE**: Ready for investment
- ❌ **REJECT**: Not suitable for 10k.club
- 🔄 **REVISE**: Needs specific modifications
- ⏸️ **DEFER**: Good opportunity, wrong timing

### Phase 3: Formal Community Voting (7 days)

**Platform**: Snapshot (gasless voting)
**Voting Power**: 1 member = 1 vote (equal voting rights)
**Quorum Requirement**: 25% of total members (2,500 votes minimum)
**Approval Threshold**: 60% approval required for investment

#### Voting Interface

**Snapshot Proposal Format**:
```
Title: [REAL ESTATE] Costa Rica Food Market - $500K Investment

Executive Summary:
- Total Investment: $500,000 USD
- Location: San José, Costa Rica
- Business Model: Food market rental spaces
- Projected ROI: 12-15% annually
- Timeline: 6 months development + operations
- Explorer: [Pseudonym]

Financial Highlights:
- Cap Rate: 8.5%
- Cash-on-Cash Return: 14%
- Break-even Timeline: 18 months
- 5-year IRR: 16.2%

Auditor Assessment: APPROVE (2/3 auditors recommend)
Risk Level: MODERATE
Investment Category: International Real Estate

Voting Options:
🟢 APPROVE - Deploy $500K investment
🔴 REJECT - Not suitable for 10k.club
🟡 REVISE - Needs modifications (specify in comments)
⚪ DEFER - Good opportunity, wrong timing

Voting Period: 7 days from proposal creation
Required Quorum: 2,500 votes (25% of members)
Approval Threshold: 1,500 approve votes (60%)
```

#### Discord Integration During Voting

**Automated Notifications**:
- `@everyone` announcement when voting opens
- Daily progress updates with current vote counts
- 48-hour warning before voting closes
- 24-hour final reminder
- Immediate results announcement

**Discussion Channels**:
- `#proposal-discussion-[ID]`: Dedicated channel per opportunity
- `#auditor-reports`: Public auditor assessment details
- `#explorer-ama-[ID]`: Live Q&A with submitting Explorer
- `#voting-help`: Technical support for voting process

### Phase 4: Post-Vote Actions

#### If Approved (≥60% approval + quorum met):
1. **Immediate Actions**:
   - Explorer receives Tier 1 reward ($200 USDC)
   - Legal structure setup initiated
   - Executive recruitment begins for region
   - Fund allocation approved in Gnosis Safe multisig

2. **Implementation Timeline**:
   - Week 1-2: Legal entity formation
   - Week 3-4: Fund transfer and property acquisition
   - Month 2-6: Development/renovation phase
   - Month 7+: Operational phase begins

#### If Rejected or Deferred:
1. **Feedback Compilation**: Detailed analysis of rejection reasons
2. **Improvement Guidance**: Specific recommendations for future submissions
3. **Resubmission Eligibility**: Can resubmit after addressing concerns
4. **Learning Resources**: Access to additional training materials

## Quality Control & Gamification

### Explorer Performance Tracking

**Individual Metrics**:
- Submission completion rate
- Community approval percentage
- Average quality scores
- ROI prediction accuracy
- Geographic diversity of submissions

**Leaderboards** (Updated monthly):
1. **Most Approved Opportunities**
2. **Highest Quality Scores**
3. **Best ROI Predictions**
4. **Most Diverse Geographic Coverage**
5. **Highest Community Engagement**

### Achievement System

**Milestone Badges**:
- 🏆 **First Approval**: First community-approved opportunity
- 🌍 **Global Explorer**: Opportunities from 5+ countries
- 💎 **Diamond Finder**: 3+ opportunities with >20% actual ROI
- 🎯 **Accuracy Master**: ROI predictions within 2% of actual
- 🚀 **Volume Leader**: 10+ quality submissions
- 👑 **Community Favorite**: Highest average community vote scores

**Special Recognition**:
- Monthly Explorer spotlight in Discord
- Annual "Explorer of the Year" award ($5,000 USDC)
- Exclusive access to advanced market research tools
- Priority consideration for Executive roles in approved projects

### Continuous Improvement

**Feedback Integration**:
- Monthly Explorer surveys on process improvements
- Regular template updates based on submission patterns
- Community voting on process modifications
- Quarterly review of reward structures

**Training & Development**:
- Monthly webinars on market research techniques
- Access to professional real estate analysis tools
- Mentorship program pairing new and experienced Explorers
- Regional market expertise sharing sessions

---

*This comprehensive system ensures high-quality opportunity submissions while providing meaningful rewards and recognition for Explorer contributions to the 10k.club DAO.*
