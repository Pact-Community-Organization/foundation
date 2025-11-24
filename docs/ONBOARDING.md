# Community Member Onboarding Process

This document outlines the comprehensive onboarding process for new community members in the Pact Community Organization (PCO). It covers the journey from initial interest to formal organizational roles, including role identification, assignment procedures, and progression paths.

## Current Organization State

**Important Note**: As of November 2025, the PCO is in its early stages with:
- **1 Active Member**: DaisukeFlowers (Organization Owner/Admin)
- **4 Teams Created**: Core-Maintainers, Catalog-Team, Security-WG, Website-Team
- **Repository Permissions**: Teams have `maintain` access to assigned repositories
- **Governance Structure**: Basic framework exists, but Council and complex hierarchy not yet implemented

The onboarding process is designed to scale from this minimal structure to the full governance model described in [GOVERNANCE.md](../governance/GOVERNANCE.md).

## Overview

The PCO follows a structured yet flexible approach to community participation, allowing members to start contributing immediately while providing clear paths for increased responsibility and formal roles.

## Phase 1: Community Discovery and Initial Engagement

### How New Members Join

1. **Discovery Channels**
   - GitHub repositories (pact-contract-catalog, foundation, website)
   - Pact documentation and forums
   - Social media and developer communities

2. **Initial Engagement**
   - Read [CONTRIBUTING.md](../community/CONTRIBUTING.md)
   - Review [Code of Conduct](../community/CODE_OF_CONDUCT.md)
   - Join relevant GitHub Discussions
   - Subscribe to organization updates

3. **First Contributions**
   - Report bugs or issues
   - Suggest improvements via GitHub issues
   - Submit documentation improvements
   - Participate in community discussions

## Phase 2: Contributor Status

### Automatic Role Assignment
- **Trigger**: First approved contribution (issue, PR, or discussion)
- **Process**: Automatic via GitHub workflows
- **Permissions**: Read access to public repositories
- **Duration**: Ongoing while actively contributing

### Contributor Responsibilities
- Follow contribution guidelines
- Maintain code of conduct compliance
- Provide constructive feedback
- Help other community members

### Recognition and Tracking
- Contributions tracked via GitHub activity
- Monthly contributor acknowledgments
- Access to contributor-only channels (when available)

## Phase 3: Role Identification and Nomination

### Role Assessment Criteria

#### Currently Available Team Roles
- **Core-Maintainers**: `maintain` permissions on foundation repository
  - Technical Excellence: Code quality, Pact/Kadena understanding
  - Consistency: Regular contributions over 3+ months
  - Code Review: Helpful PR reviews and constructive feedback
  - Communication: Clear documentation and community engagement

- **Catalog-Team**: `maintain` permissions on pact-contract-catalog repository
  - Contract validation expertise and metadata management
  - Understanding of Pact smart contract standards
  - Experience with contract auditing and validation

- **Website-Team**: `maintain` permissions on website repository
  - Web development skills (HTML, CSS, JavaScript)
  - Content management and deployment experience
  - Understanding of static site generation

- **Security-WG**: Security triage permissions across repositories
  - Security analysis and vulnerability assessment experience
  - Understanding of smart contract security principles
  - Responsible disclosure practices

#### Future Roles (Not Yet Implemented)
- **Council Member**: Governance advisory role (requires 3+ council members)
- **Director**: Strategic oversight (currently held by org owner)
- **Team Leads**: Coordination roles within teams

### Nomination Process

1. **Self-Nomination**
   - Submit interest via GitHub issue in foundation repository
   - Include contribution history and relevant experience
   - Specify desired role/team

2. **Peer Nomination**
   - Existing maintainers can nominate promising contributors
   - Requires sponsor's endorsement and reasoning

3. **Automated Suggestions**
   - GitHub analytics identify high-impact contributors
   - Monthly review of contribution metrics

## Phase 4: Role Assignment Process

### Current Process (Minimal Organization Structure)

#### Step 1: Nomination Submission
```markdown
**Issue Template**: Role Nomination Request

Title: "Nomination: [Username] for [Team]"

Body:
- Nominee's GitHub username
- Proposed team (Core-Maintainers, Catalog-Team, Security-WG, Website-Team)
- Nomination reason and evidence
- Sponsoring member (if applicable)
- Nominee's statement of interest
```

#### Step 2: Background Check
- Review contribution history (3+ months preferred)
- Assess code quality and community engagement
- Verify code of conduct compliance
- Check for conflicts of interest

#### Step 3: Organization Owner Review
- Current process: Organization owner (DaisukeFlowers) reviews all nominations
- Evaluation timeframe: Within 7-14 days
- Decision criteria: Technical fit, community contribution, team needs

#### Step 4: Role Assignment
- Organization owner adds member to appropriate GitHub team
- Automatic permission assignment via GitHub team membership
- Welcome message and onboarding information provided

#### Step 5: Onboarding and Training
- Welcome message from organization owner
- Access to team-specific documentation
- Introduction to team communication channels
- 30-day probationary period with check-in

### Future Process (When Council is Established)

#### For Core Maintainer Roles
1. **Nomination**: Submit via GitHub issue
2. **Background Check**: 6+ month history review
3. **Council Review**: 7 business days, voting process
4. **Director Approval**: Final decision (when Director role is established)
5. **Permission Assignment**: Repository-specific access granted

#### For Team-Specific Roles
1. **Team Lead Nomination**: Core maintainers propose candidates
2. **Team Discussion**: Member review and feedback
3. **Core Maintainer Approval**: Via majority vote
4. **Permission Assignment**: Repository-specific access granted

## Phase 5: Role Management and Progression

### Probationary Periods
- **All Roles**: 30-90 day initial evaluation
- **Performance Metrics**: Contribution quality, communication, reliability
- **Feedback Process**: Regular check-ins with mentors/sponsors

### Role Progression Paths

#### Current Path (Available Now)
```
Contributor → Team Member
     ↓           ↓
  1-3 months  Ongoing
```

**Available Teams:**
- Core-Maintainers (foundation repository)
- Catalog-Team (pact-contract-catalog repository)
- Website-Team (website repository)
- Security-WG (cross-repository security triage)

#### Future Paths (When Organization Scales)
```
Contributor → Team Member → Team Lead → Core Maintainer → Council Member
     ↓           ↓            ↓            ↓              ↓
  1-3 months  3-6 months   6-12 months  12+ months    18+ months
```

**Future Roles:**
- Team Leads (coordination within teams)
- Council Members (governance advisory)
- Director (strategic oversight)

### Role Removal Process

#### Current Process
- **Authority**: Organization owner (DaisukeFlowers) handles all role changes
- **Process**: Direct communication and GitHub team management
- **Documentation**: Updates to teams.md and internal records

#### Voluntary Removal
- Member submits resignation via GitHub issue or direct communication
- Organization owner removes from GitHub teams
- Public acknowledgment of service (when appropriate)

#### Involuntary Removal
- **Trigger**: Code of conduct violation, inactivity, or performance issues
- **Process**:
  1. Private discussion with member
  2. Organization owner decision
  3. Removal from GitHub teams
  4. Public announcement (if appropriate)

#### Appeals Process
- Member may appeal decision within 7 days
- Organization owner reviews appeal evidence
- Final decision by organization owner

#### Future Process (With Council)
- Council review and recommendation
- Director final decision
- Formal appeals process with neutral mediation

## Internal Documentation and Tracking

### Required Documentation Updates

#### For Each Role Assignment
1. **teams.md Update**: Add member to appropriate team section
2. **GitHub Team Management**: Automatic via GitHub UI or API
3. **Internal Records**: Track assignment date and rationale

#### Regular Reviews
- **Monthly**: Organization owner reviews team memberships and activity
- **Quarterly**: Assess team effectiveness and contribution patterns
- **Annually**: Complete organization audit and process review

### Internal Tools and Processes

#### GitHub Team Management
- Teams created via GitHub admin UI or `gh team` commands
- Permission levels: `read`, `triage`, `write`, `maintain`, `admin`
- Current teams: Core-Maintainers, Catalog-Team, Security-WG, Website-Team

#### Access Control
- Repository-specific permissions via team membership
- Organization membership required for team access
- Automatic permission synchronization through GitHub

#### Communication Channels
- GitHub issues and discussions (public)
- Direct communication with organization owner
- Future: Team-specific channels when community grows

## Success Metrics and KPIs

### Community Health
- **Growth Rate**: New contributor acquisition
- **Retention Rate**: Contributor-to-maintainer conversion
- **Diversity**: Geographic and skill diversity metrics

### Process Efficiency
- **Time to Role Assignment**: Average days from nomination to assignment
- **Onboarding Satisfaction**: Post-onboarding surveys
- **Process Completion Rate**: Percentage of nominations completed

### Organizational Impact
- **Contribution Quality**: PR acceptance rates, issue resolution time
- **Innovation Rate**: New initiatives from community members
- **Governance Participation**: Council and maintainer engagement

## Continuous Improvement

### Regular Process Reviews
- **Quarterly**: Council reviews onboarding metrics
- **Annually**: Complete governance and process audit
- **Community Feedback**: Annual community survey

### Process Updates
- RFC process for significant changes
- GitHub issues for incremental improvements
- Documentation updates following changes

## Emergency Procedures

### Security-Related Role Assignment
- **Immediate Assignment**: Security WG roles can be assigned immediately
- **Expedited Process**: 24-hour review period for critical security roles
- **Temporary Permissions**: Short-term access during emergencies

### Conflict Resolution
- **Escalation Path**: Contributor → Organization Owner
- **Mediation Process**: Organization owner handles all conflicts directly
- **Documentation**: All conflicts and resolutions recorded internally

#### Future Escalation Path (With Full Governance)
- Contributor → Team Lead → Core Maintainers → Council → Director

---

## Quick Reference Guide

### For New Contributors
1. Read CONTRIBUTING.md and Code of Conduct
2. Start with small contributions (issues, docs, discussions)
3. Engage consistently for 3+ months
4. Express interest in specific teams via GitHub issue

### For Nominating Members
1. Use role nomination issue template
2. Provide specific evidence and reasoning
3. Include nominee's contribution history
4. Submit to foundation repository issues

### For Organization Owner (Current Process)
1. Review nominations within 7-14 days
2. Consider technical fit and team needs
3. Add approved members to GitHub teams
4. Ensure smooth onboarding process

### Available Teams and Permissions
- **Core-Maintainers**: `maintain` on foundation repo
- **Catalog-Team**: `maintain` on pact-contract-catalog repo
- **Website-Team**: `maintain` on website repo
- **Security-WG**: Security triage across repos

---

*This document reflects the current state of the PCO (minimal structure) and provides a roadmap for future governance evolution. As the organization grows, this document will be updated to implement the full Council and Director structure described in [GOVERNANCE.md](../governance/GOVERNANCE.md). Last updated: November 2025*