# AZ-500: Microsoft Azure Security Technologies Study Plan

## Overview

- **Goal**: Pass AZ-500 by May 30/31, 2025.
- **Duration**: 5 weeks (April 27–May 31, 2025), ~70.5 hours.
- **Resources**:
  - Microsoft Learn (free)
  - Pluralsight AZ-500 course (~$299/year or free trial)
  - Whizlabs AZ-500 practice tests (~$20)
  - Azure portal (Free Tier/Sandbox)
  - John Savill YouTube (free)
- **Background**: AZ-900, AZ-104 certified; familiar with Azure AD, NSGs, Conditional Access, Blob Storage.
  
## Week 1: Manage Identity and Access (April 27–May 3, 2025, 14.5 hours)
**Goal**: Master Azure AD, Conditional Access, MFA, RBAC, and Privileged Identity Management (PIM).
  
**Sunday, April 27 (2 hours)**

- [x] Read AZ-500 exam skills outline on Microsoft Learn (30 min).
  - **Resource**: Microsoft Learn AZ-500
  - **Knowledge Goal**: Understand exam structure and objectives.
- [x] Complete Microsoft Learn module: “Manage Azure Active Directory identities” (1 hour).
  - **Resource**: Microsoft Learn
  - **KnowledgeGoal**: Understand Azure AD structure, user/group management.
- [x] Lab: Create an Azure AD user, assign roles, enable MFA (Azure portal, 45 min).
  - **Resource**: Azure portal
  - **Knowledge Goal**: Configure MFA and basic user management.
- [x] Review notes: Key Azure AD concepts (tenants, users, groups) (15 min).
  - **Knowledge Goal**: Solidify Azure AD terminology.
     
***Resource list used during study***
- *https://www.youtube.com/watch?v=YjFAGujrYRk* - Enable MFA
- *https://learn.microsoft.com/en-us/training/modules/manage-azure-active-directory-identities/* - Manage Azure Active Directory identities
- *https://learn.microsoft.com/en-us/training/modules/manage-security-controls-identity-access/* - Unit 1 and 2
- *https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-500#skills-at-a-glance* - AZ-500 exam skills outline
- *https://www.udemy.com/course/exam-azure-2/?couponCode=25BBPMXPLOYTRMT* - Udemy course (Unit 1 - 15)

**Monday, April 28 (2.5 hours)**

- [ ] Watch Pluralsight: “Manage Identities in Azure AD” (1 hour).
  - **Resource**: Pluralsight
  - **Knowledge Goal**: Deepen Azure AD management skills.
- [x] Lab: Configure a Conditional Access policy (e.g., require MFA for admins) (1 hour).
  - **Resource**: Azure portal
  - **Knowledge Goal**: Implement Conditional Access policies.
- [ ] Quiz: Microsoft Learn practice questions on Azure AD (30 min).
  - **Resource**: Microsoft Learn
  - **Knowledge Goal**: Test Azure AD knowledge.

  ***Resource list used during study***
- *https://www.udemy.com/course/exam-azure-2/?couponCode=25BBPMXPLOYTRMT* - Udemy course (Unit 15 - )

**Tuesday, April 29 (2 hours)**

- [ ] Complete Microsoft Learn: “Implement Azure AD role-based access control” (1 hour).
  - **Resource**: Microsoft Learn
  - **Knowledge Goal**: Understand RBAC roles and scope.
- [ ] Lab: Assign custom RBAC roles to a resource group (45 min).
  - **Resource**: Azure portal
  - **Knowledge Goal**: Create and apply custom RBAC roles.
- [ ] Create flashcards: RBAC roles vs. Azure AD roles (15 min).
  - **Knowledge Goal**: Differentiate RBAC and Azure AD roles.

**Wednesday, April 30 (2.5 hours)**

 Watch Pluralsight: “Implement Privileged Identity Management” (1 hour).Resource: PluralsightKnowledge Goal: Understand PIM workflows.
 Lab: Enable PIM for an Azure AD role, test just-in-time access (1 hour).Resource: Azure portalKnowledge Goal: Configure and test PIM.
 Review notes: PIM workflows and audit logs (30 min).Knowledge Goal: Understand PIM auditing and reporting.

Thursday, May 1 (2 hours)

 Complete Microsoft Learn: “Secure external identities with Azure AD” (1 hour).Resource: Microsoft LearnKnowledge Goal: Manage B2B/B2C identities.
 Lab: Invite a guest user, configure B2B collaboration (45 min).Resource: Azure portalKnowledge Goal: Set up B2B collaboration.
 Quiz: Azure AD B2B vs. B2C (15 min).Resource: Microsoft LearnKnowledge Goal: Differentiate B2B and B2C scenarios.

Friday, May 2 (2 hours)

 Watch John Savill YouTube: “Azure AD Security Features” (45 min).Resource: John Savill YouTubeKnowledge Goal: Explore advanced Azure AD security.
 Lab: Review audit logs and sign-in logs in Azure AD (1 hour).Resource: Azure portalKnowledge Goal: Analyze security logs.
 Review Week 1 notes, focus on weak areas (15 min).Knowledge Goal: Reinforce identity concepts.

Saturday, May 3 (1.5 hours)

 Take Microsoft Learn practice assessment for identity and access (45 min).Resource: Microsoft LearnKnowledge Goal: Assess Week 1 mastery.
 Review incorrect answers, update notes (30 min).Knowledge Goal: Identify and address gaps.
 Plan Week 2 schedule (15 min).Knowledge Goal: Stay organized.

## Week 2: Implement Platform Protection (May 4–10, 2025, 14.5 hours)
**Goal**: Master network security (NSGs, Azure Firewall), host security, and container security.
  
Sunday, May 4 (2 hours)

 Complete Microsoft Learn: “Implement network security” (1 hour).Resource: Microsoft LearnKnowledge Goal: Configure NSGs and network security.
 Lab: Create an NSG, apply rules to a subnet (45 min).Resource: Azure portalKnowledge Goal: Apply NSG rules effectively.
 Review: NSG vs. ASG differences (15 min).Knowledge Goal: Clarify NSG/ASG use cases.

Monday, May 5 (2.5 hours)

 Watch Pluralsight: “Azure Firewall and DDoS Protection” (1 hour).Resource: PluralsightKnowledge Goal: Understand Azure Firewall features.
 Lab: Deploy Azure Firewall, configure DNAT rule (1 hour).Resource: Azure portalKnowledge Goal: Implement Azure Firewall.
 Quiz: Firewall vs. NSG features (30 min).Resource: PluralsightKnowledge Goal: Differentiate Firewall and NSG.

Tuesday, May 6 (2 hours)

 Complete Microsoft Learn: “Implement host security” (1 hour).Resource: Microsoft LearnKnowledge Goal: Secure VMs and hosts.
 Lab: Enable Microsoft Defender for Servers on a VM (45 min).Resource: Azure portalKnowledge Goal: Configure Defender for Servers.
 Create flashcards: Defender for Cloud features (15 min).Knowledge Goal: Memorize Defender capabilities.

Wednesday, May 7 (2.5 hours)

 Watch Pluralsight: “Secure containers in Azure” (1 hour).Resource: PluralsightKnowledge Goal: Understand container security.
 Lab: Deploy a container in Azure Container Instances, apply security settings (1 hour).Resource: Azure portalKnowledge Goal: Secure containers.
 Review: Container security best practices (30 min).Knowledge Goal: Apply container security principles.

Thursday, May 8 (2 hours)

 Complete Microsoft Learn: “Implement DDoS protection” (45 min).Resource: Microsoft LearnKnowledge Goal: Configure DDoS protection.
 Lab: Enable DDoS Standard protection on a VNET (45 min).Resource: Azure portalKnowledge Goal: Implement DDoS Standard.
 Quiz: DDoS protection tiers (30 min).Resource: Microsoft LearnKnowledge Goal: Understand DDoS tiers.

Friday, May 9 (2 hours)

 Watch John Savill: “Azure Network Security” (45 min).Resource: John Savill YouTubeKnowledge Goal: Deepen network security knowledge.
 Lab: Combine NSG, Firewall, and Defender in a hub-spoke topology (1 hour).Resource: Azure portalKnowledge Goal: Integrate security tools.
 Review Week 2 notes (15 min).Knowledge Goal: Reinforce platform protection.

Saturday, May 10 (1.5 hours)

 Take Whizlabs practice test #1 (50 questions, 1 hour).Resource: WhizlabsKnowledge Goal: Assess platform protection knowledge.
 Review incorrect answers, update notes (30 min).Knowledge Goal: Address gaps.

## Week 3: Secure Data and Applications (May 11–17, 2025, 14.5 hours)
**Goal**: Master Key Vault, encryption, Azure Information Protection, and app security.
  
Sunday, May 11 (2 hours)

 Complete Microsoft Learn: “Manage Azure Key Vault” (1 hour).Resource: Microsoft LearnKnowledge Goal: Configure Key Vault.
 Lab: Create a Key Vault, store a secret and key (45 min).Resource: Azure portalKnowledge Goal: Manage secrets and keys.
 Review: Key Vault access policies (15 min).Knowledge Goal: Understand access control.

Monday, May 12 (2.5 hours)

 Watch Pluralsight: “Data encryption in Azure” (1 hour).Resource: PluralsightKnowledge Goal: Understand encryption methods.
 Lab: Enable encryption for Blob Storage (1 hour).Resource: Azure portalKnowledge Goal: Implement data encryption.
 Quiz: Client-side vs. server-side encryption (30 min).Resource: PluralsightKnowledge Goal: Differentiate encryption types.

Tuesday, May 13 (2 hours)

 Complete Microsoft Learn: “Implement Azure Information Protection” (1 hour).Resource: Microsoft LearnKnowledge Goal: Apply sensitivity labels.
 Lab: Configure sensitivity labels for documents (45 min).Resource: Azure portalKnowledge Goal: Implement data classification.
 Create flashcards: AIP vs. Microsoft Purview (15 min).Knowledge Goal: Clarify AIP and Purview roles.

Wednesday, May 14 (2.5 hours)

 Watch Pluralsight: “Secure Azure applications” (1 hour).Resource: PluralsightKnowledge Goal: Secure app authentication.
 Lab: Secure an App Service with managed identities (1 hour).Resource: Azure portalKnowledge Goal: Implement managed identities.
 Review: Managed identities vs. service principals (30 min).Knowledge Goal: Differentiate identity types.

Thursday, May 15 (2 hours)

 Complete Microsoft Learn: “Implement database security” (1 hour).Resource: Microsoft LearnKnowledge Goal: Secure Azure SQL.
 Lab: Enable Transparent Data Encryption (TDE) on Azure SQL (45 min).Resource: Azure portalKnowledge Goal: Configure TDE and firewall rules.
 Quiz: Database security features (15 min).Resource: Microsoft LearnKnowledge Goal: Understand database protections.

Friday, May 16 (2 hours)

 Watch John Savill: “Azure Key Vault and Data Security” (45 min).Resource: John Savill YouTubeKnowledge Goal: Apply Key Vault practically.
 Lab: Integrate Key Vault with an App Service (1 hour).Resource: Azure portalKnowledge Goal: Use Key Vault in apps.
 Review Week 3 notes (15 min).Knowledge Goal: Reinforce data/app security.

Saturday, May 17 (1.5 hours)

 Take Whizlabs practice test #2 (50 questions, 1 hour).Resource: WhizlabsKnowledge Goal: Assess data/app security knowledge.
 Review incorrect answers, update notes (30 min).Knowledge Goal: Address gaps.

## Week 4: Manage Security Operations (May 18–24, 2025, 14.5 hours)
**Goal**: Master Microsoft Defender for Cloud, Azure Sentinel, Azure Monitor, and threat detection.
  
Sunday, May 18 (2 hours)

 Complete Microsoft Learn: “Manage Microsoft Defender for Cloud” (1 hour).Resource: Microsoft LearnKnowledge Goal: Configure Defender for Cloud.
 Lab: Enable Defender for Cloud, review recommendations (45 min).Resource: Azure portalKnowledge Goal: Understand security posture management.
 Review: Defender plans (e.g., CSPM, Servers) (15 min).Knowledge Goal: Clarify Defender offerings.

Monday, May 19 (2.5 hours)

 Watch Pluralsight: “Azure Sentinel for threat detection” (1 hour).Resource: PluralsightKnowledge Goal: Understand SIEM capabilities.
 Lab: Deploy Sentinel, connect a data source (e.g., Azure AD logs) (1 hour).Resource: Azure portalKnowledge Goal: Set up Sentinel.
 Quiz: Sentinel vs. Defender (30 min).Resource: PluralsightKnowledge Goal: Differentiate Sentinel and Defender.

Tuesday, May 20 (2 hours)

 Complete Microsoft Learn: “Implement Azure Monitor for security” (1 hour).Resource: Microsoft LearnKnowledge Goal: Configure security monitoring.
 Lab: Create an alert rule in Azure Monitor (45 min).Resource: Azure portalKnowledge Goal: Write basic KQL queries.
 Create flashcards: Log Analytics queries (15 min).Knowledge Goal: Memorize KQL basics.

Wednesday, May 21 (2.5 hours)

 Watch Pluralsight: “Threat detection and response” (1 hour).Resource: PluralsightKnowledge Goal: Understand incident response.
 Lab: Create a Sentinel playbook for automated response (1 hour).Resource: Azure portalKnowledge Goal: Automate threat responses.
 Review: Incident response workflows (30 min).Knowledge Goal: Triage incidents effectively.

Thursday, May 22 (2 hours)

 Complete Microsoft Learn: “Manage security policies” (1 hour).Resource: Microsoft LearnKnowledge Goal: Manage compliance policies.
 Lab: Assign a custom security policy in Defender for Cloud (45 min).Resource: Azure portalKnowledge Goal: Configure custom policies.
 Quiz: Regulatory compliance in Defender (15 min).Resource: Microsoft LearnKnowledge Goal: Understand compliance features.

Friday, May 23 (2 hours)

 Watch John Savill: “Azure Sentinel and Defender” (45 min).Resource: John Savill YouTubeKnowledge Goal: Integrate Sentinel and Defender.
 Lab: Simulate a security alert, investigate in Sentinel (1 hour).Resource: Azure portalKnowledge Goal: Investigate incidents.
 Review Week 4 notes (15 min).Knowledge Goal: Reinforce security operations.

Saturday, May 24 (1.5 hours)

 Take Whizlabs practice test #3 (50 questions, 1 hour).Resource: WhizlabsKnowledge Goal: Assess security operations knowledge.
 Review incorrect answers, update notes (30 min).Knowledge Goal: Address gaps.

## Week 5: Review and Exam Preparation (May 25–31, 2025, 12.5 hours)
**Goal**: Consolidate knowledge, take practice exams, and finalize hands-on skills.
  
Sunday, May 25 (2 hours)

 Review all notes from Weeks 1–4, focus on weak areas (1 hour).Resource: Personal notesKnowledge Goal: Integrate concepts.
 Lab: End-to-end scenario (secure VM with NSG, Key Vault, Defender) (1 hour).Resource: Azure portalKnowledge Goal: Apply security holistically.

Monday, May 26 (2.5 hours)

 Take Whizlabs full-length practice exam #1 (60 questions, 2 hours).Resource: WhizlabsKnowledge Goal: Simulate exam experience.
 Review incorrect answers, research gaps (30 min).Knowledge Goal: Address final gaps.

Tuesday, May 27 (2 hours)

 Review Microsoft Learn case studies and drag-and-drop questions (1 hour).Resource: Microsoft LearnKnowledge Goal: Master case study scenarios.
 Lab: Revisit weak areas (e.g., Sentinel playbooks, PIM) (1 hour).Resource: Azure portalKnowledge Goal: Strengthen weak skills.

Wednesday, May 28 (2.5 hours)

 Take Whizlabs full-length practice exam #2 (60 questions, 2 hours).Resource: WhizlabsKnowledge Goal: Achieve 80%+ score.
 Review incorrect answers, update notes (30 min).Knowledge Goal: Refine weak areas.

Thursday, May 29 (2 hours)

 Review flashcards and key concepts (e.g., Defender vs. Sentinel, RBAC vs. PIM) (1 hour).Resource: Personal flashcardsKnowledge Goal: Solidify key concepts.
 Lab: Quick review of Key Vault, NSG, and Sentinel setups (1 hour).Resource: Azure portalKnowledge Goal: Confirm hands-on skills.

Friday, May 30 (1.5 hours)

 Light review: Skim notes, focus on high-weight topics (identity, data security) (1 hour).Resource: Personal notesKnowledge Goal: Boost confidence.
 Schedule exam if not already booked (15 min).Resource: Pearson VUEKnowledge Goal: Finalize logistics.
 Relax and prepare mentally (15 min).Knowledge Goal: Reduce stress.

**Saturday, May 31 (Exam Day)**

 Take AZ-500 exam (150 minutes, morning slot recommended).Resource: Pearson VUEKnowledge Goal: Pass with ≥700/1000.
 Post-exam: Note challenging areas for future reference (30 min).Knowledge Goal: Plan next steps.

Tips

Labs: Use Azure Free Tier/Sandbox, delete resources daily to avoid costs.
Progress: Check boxes in GitHub as tasks are completed. Aim for 80%+ on practice tests.
Health: Sleep 7–8 hours, take breaks every 60 minutes.
Contingency: If behind, shift tasks to weekends or extend to June 7, focusing on practice exams.
Post-Exam: Update resume/LinkedIn if passed. Plan next certification (e.g., AZ-305).

