# Graph Report - agents  (2026-09-23)

## Corpus Check
- 64 files · ~111,800 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 1 file(s) not represented in the graph (top: (none) 1)

## Summary
- 352 nodes · 452 edges · 26 communities
- Extraction: 84% EXTRACTED · 16% INFERRED · 0% AMBIGUOUS · INFERRED: 72 edges (avg confidence: 0.79)
- Token cost: 224,683 input · 0 output

## Community Hubs (Navigation)
- Business-Ideen & Validierung
- Security & Threat Modeling
- Strategie, CFO & Customer Success
- Produktmanagement & Priorisierung
- Prototyping, ASO & Growth
- Erfindungs-Pipeline
- Payments & Buchhaltung
- Datenschutz & Rechtsprüfung
- Content, Social & Chief of Staff
- Technische Doku & Operations
- UI/UX Design-Systeme
- Privacy Engineering & NoSignups
- Softwarearchitektur & Steuern
- Mobile Apps & Release
- Finanzanalyse & FP&A
- Sales Deals & Pipeline
- Marke & Visual Storytelling
- Backend & Datenbanken
- CMS & DevOps
- Analytics & Support
- Bild-Prompts & Inklusion
- API-Plattform
- HR-Onboarding
- Agenten-Set & Studio Producer
- Code- & UI-Review
- UX-Research

## God Nodes (most connected - your core abstractions)
1. `The Agency Curated Agent Set` - 56 edges
2. `Subagent` - 22 edges
3. `10 Business Ideas in Unsaturated Niches` - 15 edges
4. `Chief Financial Officer Agent` - 12 edges
5. `Data Privacy Officer Agent` - 12 edges
6. `UI Designer Agent` - 11 edges
7. `Payments & Billing Engineer` - 11 edges
8. `Backend Architect Agent` - 10 edges
9. `CMS Developer Agent` - 10 edges
10. `Operations Manager` - 10 edges

## Surprising Connections (you probably didn't know these)
- `invention-verifier Agent` --semantically_similar_to--> `Reality Checker Agent`  [INFERRED] [semantically similar]
  erfindungen/README.md → .claude/agents/testing-reality-checker.md
- `Pre-order Validation Principle` --semantically_similar_to--> `Default to NEEDS WORK`  [INFERRED] [semantically similar]
  business-ideen/README.md → .claude/agents/testing-reality-checker.md
- `EU AI Act Documentation and Training` --conceptually_related_to--> `Legal Compliance Checker Agent`  [INFERRED]
  business-ideen/README.md → .claude/agents/support-legal-compliance-checker.md
- `ESG EcoVadis Support for SME Suppliers` --conceptually_related_to--> `SOC 2`  [AMBIGUOUS]
  business-ideen/README.md → .claude/agents/security-compliance-auditor.md
- `business-strategist Agent` --references--> `Business Strategist Agent`  [EXTRACTED]
  business-ideen/AGENTEN-STATUS.md → .claude/agents/business-strategist.md

## Hyperedges (group relationships)
- **New Web App 0-to-1 Workflow** — _claude_agents_design_ux_researcher_ux_researcher_agent, _claude_agents_design_ui_designer_ui_designer_agent, _claude_agents_engineering_frontend_developer_frontend_developer_agent, _claude_agents_engineering_backend_architect_backend_architect_agent, _claude_agents_engineering_code_reviewer_code_reviewer_agent [EXTRACTED 1.00]
- **CMS Developer Escalation Network** — _claude_agents_engineering_cms_developer_cms_developer_agent, _claude_agents_engineering_backend_architect_backend_architect_agent, _claude_agents_engineering_frontend_developer_frontend_developer_agent, _claude_agents_engineering_database_optimizer_database_optimizer_agent, _claude_agents_engineering_devops_automator_devops_automator_agent [EXTRACTED 1.00]
- **Mobile Build-to-Store Pipeline** — _claude_agents_engineering_mobile_app_builder_mobile_app_builder_agent, _claude_agents_engineering_mobile_release_engineer_mobile_release_engineer_agent, _claude_agents_engineering_devops_automator_devops_automator_agent [INFERRED 0.75]
- **Invention Discovery & Verification Pipeline** — _claude_agents_invention_scout_invention_scout, _claude_agents_invention_verifier_invention_verifier, _claude_agents_invention_scout_invention_candidate_format, _claude_agents_invention_verifier_invention_scoring_rubric, _claude_agents_invention_verifier_inventions_ledger [EXTRACTED 1.00]
- **Finance Agent Suite** — _claude_agents_finance_bookkeeper_controller_bookkeeper_controller, _claude_agents_finance_financial_analyst_financial_analyst, _claude_agents_finance_fpa_analyst_fp_a_analyst, _claude_agents_finance_tax_strategist_tax_strategist [INFERRED 0.85]
- **Exactly-Once Payment Correctness** — _claude_agents_engineering_payments_billing_engineer_idempotency_key, _claude_agents_engineering_payments_billing_engineer_webhooks_as_source_of_truth, _claude_agents_engineering_payments_billing_engineer_webhook_signature_verification_and_dedupe, _claude_agents_engineering_payments_billing_engineer_daily_reconciliation_query [INFERRED 0.85]
- **Business Ideas Multi-Agent Pipeline** — business_ideen_agenten_status_business_strategist_agent, _claude_agents_testing_reality_checker_reality_checker_agent, _claude_agents_specialized_pricing_analyst_pricing_analyst_agent, _claude_agents_sales_offer_lead_gen_strategist_offer_and_lead_gen_strategist_agent, business_ideen_readme_10_business_ideas_in_unsaturated_niches [EXTRACTED 1.00]
- **Invention Radar Scout-Verify-Store Loop** — erfindungen_readme_daily_scheduled_routine, erfindungen_readme_invention_scout_agent, erfindungen_readme_invention_verifier_agent, erfindungen_inventions_confirmed_inventions [EXTRACTED 1.00]
- **Threat Modeling and Secure SDLC** — _claude_agents_security_architect_security_architect_agent, _claude_agents_security_appsec_engineer_application_security_engineer_agent, _claude_agents_security_appsec_engineer_stride_threat_model, _claude_agents_security_appsec_engineer_owasp_top_10_secure_coding_patterns, _claude_agents_security_architect_threat_model_document [INFERRED 0.85]

## Communities (26 total, 0 thin omitted)

### Community 0 - "Business-Ideen & Validierung"
Cohesion: 0.08
Nodes (29): Realistic Scope Setting, Senior Project Manager Agent, Task List Format Template, Core Four Lead Channels, Grand Slam Offer Value Equation, Lead Getters Amplifiers, Lead Magnet Types, Offer and Lead Gen Strategist Agent (+21 more)

### Community 1 - "Security & Threat Modeling"
Cohesion: 0.09
Nodes (27): CCPA, Application Security Engineer Agent, Defense in Depth, Dependency Vulnerability Management, OWASP Top 10 Secure Coding Patterns, SAST DAST Integration, STRIDE Threat Model, Adversarial Thinking Framework (+19 more)

### Community 2 - "Strategie, CFO & Customer Success"
Cohesion: 0.08
Nodes (25): Business Case Framework, Business Model Design Framework, Business Strategist Agent, Competitive Analysis Framework, Market Entry Framework, Scenario Planning Framework, SWOT & Strategic Options Framework, Annual Financial Planning Framework (+17 more)

### Community 3 - "Produktmanagement & Priorisierung"
Cohesion: 0.10
Nodes (21): Now Next Later Roadmap, Opportunity Assessment, Product Manager Agent, Product Requirements Document, RICE Prioritization, Kano Model, Product Sprint Prioritizer Agent, Sprint Planning Process (+13 more)

### Community 4 - "Prototyping, ASO & Growth"
Cohesion: 0.11
Nodes (20): Core Hypothesis, Instant Analytics And A/B Testing, Rapid Development Stack, Rapid Prototyper, shadcn ui, Validation-Driven Feature Selection, App Store Optimizer, ASO Strategy Framework (+12 more)

### Community 5 - "Erfindungs-Pipeline"
Cohesion: 0.14
Nodes (20): Invention Candidate Format, Invention Scout, Novelty Check, Profitability Check, Duplicate Rejection, Invention Scoring Rubric, Invention Verifier, Inventions Ledger (+12 more)

### Community 6 - "Payments & Buchhaltung"
Cohesion: 0.14
Nodes (18): Month-End Close Checklist, Daily Reconciliation Query, Idempotency Key, Money As Integer Minor Units, Payments & Billing Engineer, PCI Scope Reduction, Revenue Recognition Handoff, SCA 3DS (+10 more)

### Community 7 - "Datenschutz & Rechtsprüfung"
Cohesion: 0.13
Nodes (17): Article 30 Records of Processing, Breach Response Protocol, Data Privacy Officer Agent, Data Processing Agreement Checklist, Data Protection Impact Assessment, Data Subject Rights Workflow, GDPR, Legitimate Interest Assessment (+9 more)

### Community 8 - "Content, Social & Chief of Staff"
Cohesion: 0.10
Nodes (17): Brand Storytelling, Content Creator, Editorial Calendar, Campaign Management, Platform Strategy Framework, Social Media Strategist, Thought Leadership Development, Executive Dashboards (+9 more)

### Community 9 - "Technische Doku & Operations"
Cohesion: 0.13
Nodes (16): Docs-as-Code, Docusaurus, OpenAPI Documentation, README Template, Technical Writer, Tutorial Structure Template, Balanced Scorecard, Business Continuity Planning (+8 more)

### Community 10 - "UI/UX Design-Systeme"
Cohesion: 0.18
Nodes (13): Component Library Architecture, Design System First Approach, Responsive Design Framework, UI Designer Agent, WCAG AA Compliance, CSS Design System Foundation, Information Architecture, Layout Framework Specifications (+5 more)

### Community 11 - "Privacy Engineering & NoSignups"
Cohesion: 0.15
Nodes (13): Anonymization vs Pseudonymization, Consent Enforced At Write Path, Data Minimization, PII Discovery And Classification, Privacy By Design, Privacy Engineer, Retention Automation, Right To Be Forgotten Pipeline (+5 more)

### Community 12 - "Softwarearchitektur & Steuern"
Cohesion: 0.18
Nodes (12): Architecture Decision Record, Bounded Context, Dependency Direction Rule, Domain-Driven Design, Quality Attribute Analysis, Software Architect, Trade-offs Over Best Practices, Economic Substance Principle (+4 more)

### Community 13 - "Mobile Apps & Release"
Cohesion: 0.20
Nodes (11): UI Finish Gate, CI/CD Pipeline Architecture, Android Jetpack Compose, iOS SwiftUI, Mobile App Builder Agent, React Native Cross-Platform, fastlane Pipeline, iOS Signing Model (+3 more)

### Community 14 - "Finanzanalyse & FP&A"
Cohesion: 0.18
Nodes (11): DCF Analysis, Financial Analyst, LBO Modeling, Sensitivity Analysis, Three-Statement Financial Model, Variance Analysis Report, Annual Operating Plan, FP&A Analyst (+3 more)

### Community 15 - "Sales Deals & Pipeline"
Cohesion: 0.22
Nodes (11): Challenger Messaging Commercial Teaching, Command of the Message, Deal Assessment, Deal Strategist Agent, MEDDPICC Qualification Framework, Winning Battling Losing Zones, Deal Health Scoring, Forecasting Methodology (+3 more)

### Community 16 - "Marke & Visual Storytelling"
Cohesion: 0.25
Nodes (8): Brand Foundation Framework, Brand Guardian Agent, Brand Voice Guidelines, Trademark Strategy, Visual Identity System, Information Design & Data Visualization, Visual Narrative Development, Visual Storyteller Agent

### Community 17 - "Backend & Datenbanken"
Cohesion: 0.25
Nodes (8): Backend Architect Agent, Database Architecture, Microservices Architecture, Observability by Design, System Architecture Specification, Database Optimizer Agent, PostgreSQL, Query Optimization & Indexing

### Community 18 - "CMS & DevOps"
Cohesion: 0.25
Nodes (8): CMS Developer Agent, Drupal, Drupal Custom Module, Gutenberg Custom Block, WordPress, DevOps Automator Agent, Infrastructure as Code (Terraform), Prometheus Monitoring & Alerting

### Community 19 - "Analytics & Support"
Cohesion: 0.25
Nodes (8): Analytics Reporter Agent, Customer Lifetime Value Segmentation, Executive Dashboard, Marketing Performance Dashboard, Customer Support Analytics Dashboard, Knowledge Base Management System, Omnichannel Support Framework, Support Responder Agent

### Community 20 - "Bild-Prompts & Inklusion"
Cohesion: 0.33
Nodes (7): Genre-Specific Prompt Patterns, Image Prompt Engineer Agent, Prompt Structure Framework, AI Bias Mitigation, Dignified Video Prompt, Inclusive Visuals Specialist Agent, Subagent

### Community 21 - "API-Plattform"
Cohesion: 0.29
Nodes (7): API Platform Engineer Agent, Backward-Compatibility Rules, Contract-First OpenAPI, Rate Limiting, SDK Generation, Versioning & Deprecation Lifecycle, API Contract Governance

### Community 22 - "HR-Onboarding"
Cohesion: 0.29
Nodes (7): 30-60-90 Day Onboarding Plan, Benefits Enrollment Guide, Compliance Training Tracker, Day One Orientation Schedule, HR Onboarding, Manager Onboarding Guide, Pre-Boarding Checklist

### Community 23 - "Agenten-Set & Studio Producer"
Cohesion: 0.29
Nodes (7): Strategic Portfolio Plan, Strategic Portfolio Review, Studio Producer Agent, Agent Chaining, Agent Name Format Rule, msitarzewski/agency-agents, The Agency Curated Agent Set

### Community 24 - "Code- & UI-Review"
Cohesion: 0.33
Nodes (6): Design Contract, Evidence Before Opinion, UI Finish-Gate Reviewer Agent, UIZZE Reference Catalogue, Code Reviewer Agent, Review Checklist (Blockers/Suggestions/Nits)

### Community 25 - "UX-Research"
Cohesion: 0.40
Nodes (5): Usability Testing Protocol, User Journey Mapping, User Persona Template, User Research Study Framework, UX Researcher Agent

## Ambiguous Edges - Review These
- `Docs-as-Code` → `SOP Framework`  [AMBIGUOUS]
  .claude/agents/operations-manager.md · relation: conceptually_related_to
- `SOC 2` → `ESG EcoVadis Support for SME Suppliers`  [AMBIGUOUS]
  business-ideen/README.md · relation: conceptually_related_to

## Knowledge Gaps
- **156 isolated node(s):** `Competitive Analysis Framework`, `Market Entry Framework`, `Business Model Design Framework`, `SWOT & Strategic Options Framework`, `Treasury & Capital Structure` (+151 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 191 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Docs-as-Code` and `SOP Framework`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `SOC 2` and `ESG EcoVadis Support for SME Suppliers`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `The Agency Curated Agent Set` connect `Agenten-Set & Studio Producer` to `Business-Ideen & Validierung`, `Security & Threat Modeling`, `Strategie, CFO & Customer Success`, `Produktmanagement & Priorisierung`, `Prototyping, ASO & Growth`, `Payments & Buchhaltung`, `Datenschutz & Rechtsprüfung`, `Content, Social & Chief of Staff`, `Technische Doku & Operations`, `UI/UX Design-Systeme`, `Privacy Engineering & NoSignups`, `Softwarearchitektur & Steuern`, `Mobile Apps & Release`, `Finanzanalyse & FP&A`, `Sales Deals & Pipeline`, `Marke & Visual Storytelling`, `Backend & Datenbanken`, `CMS & DevOps`, `Analytics & Support`, `Bild-Prompts & Inklusion`, `API-Plattform`, `HR-Onboarding`, `Code- & UI-Review`, `UX-Research`?**
  _High betweenness centrality (0.855) - this node is a cross-community bridge._
- **Why does `Business Strategist Agent` connect `Strategie, CFO & Customer Success` to `Business-Ideen & Validierung`, `Bild-Prompts & Inklusion`, `Agenten-Set & Studio Producer`?**
  _High betweenness centrality (0.124) - this node is a cross-community bridge._
- **Why does `Reality Checker Agent` connect `Business-Ideen & Validierung` to `Erfindungs-Pipeline`?**
  _High betweenness centrality (0.121) - this node is a cross-community bridge._
- **Are the 21 inferred relationships involving `Subagent` (e.g. with `Business Strategist Agent` and `Chief Financial Officer Agent`) actually correct?**
  _`Subagent` has 21 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Competitive Analysis Framework`, `Market Entry Framework`, `Business Model Design Framework` to the rest of the system?**
  _156 weakly-connected nodes found - possible documentation gaps or missing edges._