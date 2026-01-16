# Open Science: Requirements and Best Practices for Horizon Europe

## Overview

Open Science is a **mandatory** component of all Horizon Europe projects. Unlike US grants where open science is encouraged but flexible, EU projects have specific requirements for Open Access to publications, FAIR data management, and increasingly, open research practices throughout the research lifecycle.

**Key Principle**: "As open as possible, as closed as necessary"

This means defaulting to openness while allowing justified restrictions for privacy, security, commercial exploitation, or other legitimate reasons.

---

## Open Access to Publications

### Mandatory Requirements

**All peer-reviewed scientific publications** must be:
1. Deposited in a trusted repository
2. Available Open Access **immediately upon publication**
3. Published under an open license (CC BY or CC BY-NC preferred)

### No Embargo Periods

Unlike some national policies that allow 6-12 month embargos, Horizon Europe requires **immediate** Open Access at publication. This is a significant change from Horizon 2020.

### Compliance Routes

**Route 1: Gold Open Access (Publisher)**
- Publish in Open Access journal
- Or pay APC for hybrid journal (within limits)
- Ensure CC BY license
- Article Processing Charges (APCs) are eligible costs

**Route 2: Green Open Access (Repository)**
- Publish anywhere, deposit in repository
- Final peer-reviewed version
- No embargo (immediate access)
- May require rights retention

### Rights Retention

To ensure compliance, beneficiaries should:
- Retain sufficient intellectual property rights
- Include acknowledgment clause in publishing agreements
- Use "rights retention" statements in submissions

**Example Rights Retention Statement**:
```
For the purpose of open access, the author has applied a Creative Commons
Attribution (CC BY) license to any Author Accepted Manuscript version
arising from this submission.
```

### Repository Requirements

**Trusted Repositories**:
- Institutional repositories
- Disciplinary repositories (e.g., arXiv, PubMed Central)
- General repositories (e.g., Zenodo)
- European Open Science Cloud (EOSC) connected

**Minimum Repository Features**:
- Persistent identifier (DOI)
- Metadata standards
- Long-term preservation
- Open search and harvesting

### Recommended Repositories

| Discipline | Repository | URL |
|------------|-----------|-----|
| General | Zenodo | https://zenodo.org |
| Physics/Math | arXiv | https://arxiv.org |
| Life Sciences | Europe PMC | https://europepmc.org |
| Social Sciences | SSOAR | https://www.gesis.org/ssoar |
| Humanities | DARIAH | https://www.dariah.eu |
| Institutional | University repository | Varies |

### Publication Costs (APCs)

**Eligible Costs**:
- APCs for Open Access publication
- Must be published during action duration
- Reasonable cost (market benchmarks apply)

**Recommended Approach**:
- Negotiate transformative agreements with publishers
- Use institutional library support
- Consider preprint servers + Diamond OA journals

---

## Research Data Management

### FAIR Principles

All research data should be managed according to FAIR principles:

**Findable**
- Persistent identifier assigned
- Rich metadata describing data
- Indexed in searchable resources

**Accessible**
- Retrievable via standard protocols
- Open access where possible
- Controlled access when necessary
- Metadata always accessible (even if data restricted)

**Interoperable**
- Use standard formats
- Use controlled vocabularies
- Include qualified references to other data

**Reusable**
- Clear data usage license
- Detailed provenance
- Meet domain-relevant standards

### Data Management Plan (DMP)

**Mandatory Deliverable** for all Horizon Europe projects.

**Timeline**:
- Initial DMP: Typically Month 6
- Updates: At each reporting period
- Final DMP: End of project

**DMP Content Requirements**:

1. **Data Summary**
   - What data will be collected/generated?
   - What formats and volumes?
   - What purpose does data serve?

2. **FAIR Data**
   - How will data be findable (identifiers, keywords)?
   - How will data be accessible (repository, formats)?
   - How will data be interoperable (standards, formats)?
   - How will data be reusable (license, documentation)?

3. **Allocation of Resources**
   - What are the costs of data management?
   - Who is responsible for data management?
   - What resources are needed for long-term preservation?

4. **Data Security**
   - What provisions for data security?
   - How to handle sensitive data?
   - Backup and recovery procedures?

5. **Ethical and Legal Compliance**
   - Are there ethical issues with data sharing?
   - What consent has been obtained?
   - How to comply with GDPR?

6. **Data Sharing and Preservation**
   - How will data be shared?
   - Which repository will be used?
   - How long will data be preserved?

### DMP Template

```markdown
# Data Management Plan: [ACRONYM]

## 1. Data Summary

### 1.1 Data Description
| Dataset | Format | Size | Purpose | WP |
|---------|--------|------|---------|-----|
| [Dataset 1] | [Format] | [Est. size] | [Purpose] | WP[X] |
| [Dataset 2] | [Format] | [Est. size] | [Purpose] | WP[Y] |

### 1.2 Data Origin
- [ ] Collected through project activities
- [ ] Generated through simulations/modeling
- [ ] Existing data reused
- [ ] Data from third parties

## 2. FAIR Data

### 2.1 Making Data Findable
- Repository: [Name and URL]
- Persistent identifier: [DOI/other]
- Metadata standard: [Standard used]
- Keywords and ontologies: [List]

### 2.2 Making Data Accessible
- Access level: [ ] Open [ ] Restricted [ ] Closed
- If restricted, explain: [Justification]
- Format: [Formats used]
- Access protocol: [How to access]

### 2.3 Making Data Interoperable
- Standards: [Data standards used]
- Vocabularies: [Controlled vocabularies]
- Links: [Links to other data]

### 2.4 Making Data Reusable
- License: [License applied]
- Documentation: [How data is documented]
- Quality assurance: [QA procedures]

## 3. Allocation of Resources

### 3.1 Data Management Costs
| Activity | Cost | Funding Source |
|----------|------|----------------|
| [Activity] | EUR [X] | WP[X] |

### 3.2 Responsibilities
- Data Management Lead: [Partner, Person]
- Dataset owners: [By dataset]

## 4. Data Security

### 4.1 Security Measures
[Description of security provisions]

### 4.2 Sensitive Data Handling
[If applicable]

## 5. Ethical and Legal Compliance

### 5.1 Ethical Issues
[Description or N/A]

### 5.2 GDPR Compliance
[If personal data involved]

### 5.3 IPR and Licensing
[Description]

## 6. Data Sharing and Preservation

### 6.1 Sharing Strategy
[When and how data will be shared]

### 6.2 Long-term Preservation
- Repository: [Name]
- Preservation period: [Duration]
- Format: [Preservation format]
```

### Data Sharing

**Default: Open**
- Share data as openly as possible
- Use open licenses (CC0, CC BY)
- Deposit in trusted repositories
- Enable re-use by others

**When Restrictions Are Justified**:
- Personal data protection (GDPR)
- Security-sensitive data
- Commercial confidentiality (time-limited)
- Third-party data with restrictions
- Ethical considerations

**Even When Restricted**:
- Metadata should still be open
- Describe data that exists
- Explain access conditions
- Enable controlled access where possible

### Data Licenses

| License | Permissions | Recommended For |
|---------|-------------|-----------------|
| CC0 | Full public domain | Non-personal research data |
| CC BY 4.0 | Attribution required | Most research data |
| CC BY-NC 4.0 | Non-commercial + attribution | Data with potential commercial value |
| Custom | Varies | Sensitive data with restrictions |

---

## Open Science Practices

### Beyond Publications and Data

Horizon Europe encourages broader open science practices:

**Open Methodologies**
- Share protocols and methods
- Use electronic lab notebooks
- Register studies in advance

**Open Peer Review**
- Transparent review processes
- Signed reviews where appropriate
- Post-publication review

**Early Sharing**
- Preprints
- Working papers
- Conference presentations

**Open Source Software**
- Code developed in project
- Reusable tools
- Documented and maintained

**Citizen Science**
- Public participation in research
- Co-design with stakeholders
- Societal engagement

### Preprints

**Encouraged Practice**:
- Deposit preprints before/during peer review
- Use preprint servers (arXiv, bioRxiv, etc.)
- Update with DOI link when published
- Include funding acknowledgment

**Benefits**:
- Immediate dissemination
- Feedback before publication
- Priority establishment
- Compliance with open science goals

### Open Source Software

**When Software is Project Output**:
- Use open source licenses (MIT, Apache, GPL, etc.)
- Deposit in repositories (GitHub, GitLab, Zenodo)
- Provide documentation
- Enable reuse and contribution

**Software Management Plan** (if significant software output):
- Similar to DMP
- Covers development, documentation, licensing, sustainability

---

## European Open Science Cloud (EOSC)

### What is EOSC?

EOSC is the EU's initiative to create a federated, open infrastructure for research data and services across disciplines and borders.

### EOSC and Horizon Europe

**Alignment Encouraged**:
- Deposit data in EOSC-compliant repositories
- Use EOSC services where available
- Contribute to EOSC development

**EOSC Services**:
- B2FIND (metadata discovery)
- B2SHARE (general data repository)
- B2DROP (file sharing)
- OpenAIRE (publication/data harvesting)

### EOSC Compliance

To be EOSC-compliant, repositories should:
- Provide persistent identifiers
- Use standard metadata schemas
- Support harvesting (OAI-PMH)
- Ensure long-term preservation
- Be open for deposit

---

## Open Science in Proposals

### Where to Address Open Science

**Section 1: Excellence (1.2 Methodology)**
- Open science practices in methodology
- Research data management approach
- Collaboration and sharing plans

**Section 2: Impact**
- Dissemination through open channels
- Data sharing for impact maximization
- FAIR data for reuse

**Impact Pathway**
- Open outputs as enabling factor for uptake
- Citizen science for societal engagement

### Example Proposal Text

```markdown
**Open Science Practices**

[ACRONYM] is committed to Open Science and will implement the following
practices:

**Open Access Publications**: All peer-reviewed publications will be
published Open Access immediately upon publication. Authors will retain
sufficient rights through rights retention statements. Publications will
be deposited in [repository] with CC BY 4.0 license.

**FAIR Data Management**: Research data will be managed according to
FAIR principles and the project Data Management Plan (D1.2, M6). Data
will be deposited in [repository] and made openly accessible where
possible, with justified restrictions for [specify any restrictions].

**Open Methodologies**: Protocols and methodologies will be shared via
[protocols.io/other platform]. Code developed in the project will be
released under [license] on [GitHub/GitLab] with documentation.

**Early Sharing**: Preprints will be deposited on [arXiv/bioRxiv/other]
to enable early dissemination and feedback.

**Citizen Science**: [If applicable - describe engagement activities]
```

---

## Costs and Resources

### Eligible Open Science Costs

| Cost Type | Eligibility | Notes |
|-----------|-------------|-------|
| APCs | Yes | Within market price limits |
| Repository fees | Yes | If not free |
| Data management | Yes | Personnel, tools, storage |
| Software development | Yes | Documentation, licensing |
| Citizen science | Yes | Engagement activities |

### Budget Considerations

- Include DMP preparation costs
- Budget for long-term data preservation
- Consider APC costs (EUR 2,000-5,000 typical)
- Include data curator/manager role if needed
- Software documentation costs

### Resource Planning

**Personnel**:
- Data Management Lead (1-2 PM)
- Data stewards per WP (0.5-1 PM each)

**Tools**:
- Repository storage
- DMP tools (DMPonline, etc.)
- Electronic lab notebooks

**Training**:
- FAIR data training
- Data management workshops

---

## Open Science Checklist

### Proposal Stage
- [ ] Open Access commitment stated
- [ ] Research data management approach outlined
- [ ] FAIR principles referenced
- [ ] DMP deliverable included
- [ ] Repository identified
- [ ] Open science costs budgeted

### Project Start
- [ ] Rights retention strategy in place
- [ ] Repository accounts set up
- [ ] DMP template prepared
- [ ] Data management responsibilities assigned

### During Project
- [ ] Publications deposited immediately
- [ ] DMP updated at reporting periods
- [ ] Data deposited as generated
- [ ] Metadata created and updated
- [ ] Open science practices documented

### Project End
- [ ] All publications Open Access
- [ ] Final DMP delivered
- [ ] All data deposited/archived
- [ ] Long-term preservation ensured
- [ ] Code/software released

---

## Common Mistakes

### Publications
- Signing away rights to publishers
- Allowing embargoes
- Not depositing in repositories
- Missing funding acknowledgment

### Data
- No DMP or incomplete DMP
- Not following FAIR principles
- Depositing data too late (or never)
- Inadequate metadata
- Not planning long-term preservation

### General
- Treating open science as afterthought
- Not budgeting for open science activities
- Ignoring GDPR when sharing data
- Not using persistent identifiers

---

## Resources

### Tools
- **DMPonline**: https://dmponline.dcc.ac.uk/ (DMP writing tool)
- **Zenodo**: https://zenodo.org/ (General repository)
- **OpenAIRE**: https://www.openaire.eu/ (Guidance and tools)
- **EOSC Portal**: https://eosc-portal.eu/ (Services directory)

### Guidance
- **Open Access Policy**: Horizon Europe Programme Guide
- **FAIR Data Guidelines**: GO FAIR initiative
- **DMP Templates**: DMPonline templates
- **Rights Retention**: Plan S resources

### Training
- OpenAIRE webinars and training
- Research Data Alliance resources
- FOSTER Open Science training

---

**Key Message**: Open Science is not an add-on but an integral part of how Horizon Europe research should be conducted. Plan for it from the start, budget appropriately, and embed open practices throughout the research lifecycle.
