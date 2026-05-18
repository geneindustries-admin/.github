# .github

# Gene Industries GitHub Organisation

This GitHub organisation is structured to scale into a professional AI systems, automation, software, and consulting company.

The goal is to:
- Keep projects organised
- Separate internal/client/product work
- Allow future employees and contractors to work safely
- Make systems scalable to hundreds of projects and clients
- Maintain professional development standards

---

# Organisation Structure

## Root Accounts

### geneindustries-admin
Emergency/root owner account.

Used ONLY for:
- Billing
- Recovery
- Organisation ownership
- Security management
- Emergency access

DO NOT use for daily coding or development.

---

### genehuang-ai
Primary operator/developer account.

Used for:
- Daily development
- Claude Code
- VSCode
- GitHub Desktop
- Terminal work
- Vercel deployments
- AI systems
- Repo management

---

# GitHub Organisation

## geneindustries-org

Main company organisation containing:
- Internal systems
- Client projects
- SaaS products
- AI systems
- Templates
- Experimental projects
- Infrastructure

---

# Team Structure

| Team | Purpose |
|---|---|
| Owners | Root organisation owners |
| core-dev | Main developers/builders |
| automation | n8n + AI workflow systems |
| internal-tools | Internal company systems |
| client-projects | Client/customer work |
| experiments | Prototype/lab projects |
| design | UI/UX/branding |
| contractors | Restricted external access |

---

# Repository Naming Structure

Repositories MUST follow structured naming.

Format:

category-project-client-version

Examples:

---

## Internal Systems

internal-finance-ai  
internal-knowledge-base  
internal-home-ai-system  
internal-sales-dashboard  

Purpose:
Systems used internally by Gene Industries.

---

## Client Projects

client-huanglee-finance-system  
client-mw-ai-chatbot  
client-888sizzling-ordering  

Purpose:
Projects built for paying clients or external organisations.

---

## SaaS Products

saas-ai-voice-assistant  
saas-review-management  
saas-empra-platform  

Purpose:
Long-term products/services owned by Gene Industries.

---

## Experimental Projects

lab-openai-realtime-tests  
lab-claude-agent-tests  
lab-rag-prototype  

Purpose:
Testing, experiments, prototypes, proof-of-concepts.

These repos may be temporary.

---

## Templates

template-nextjs-ai-stack  
template-client-dashboard  
template-vercel-supabase-stack  

Purpose:
Reusable starter projects and infrastructure.

---

# Repository Standards

Every repository should contain:

/docs  
/assets  
/src  
/archive  
README.md  

---

# README Requirements

Every repo README should explain:

- Purpose
- Current status
- Tech stack
- Deployment link
- Owner
- Client
- TODO
- Known issues

---

# Professional Rules

DO:
- Keep naming consistent
- Separate experiments from production
- Separate client work from internal work
- Use teams for permissions
- Use structured READMEs

DO NOT:
- Create random repos
- Mix personal and business systems
- Use names like:
  - test
  - finalfinal
  - newapp
  - prototype2

---

# Long-Term Vision

This organisation is designed to support:
- AI consulting
- Client systems
- SaaS products
- Automation services
- Internal AI operations
- Future employees
- Contractors
- Scalable infrastructure
- Hundreds of customer projects

This is intended to operate as professional long-term business infrastructure.


# Identity & Access Rules

Gene Industries uses an identity-first infrastructure model.

Every person must have:
- Their own company email
- Their own password manager account
- Their own GitHub account
- Their own MFA/2FA setup

No shared logins are allowed.

---

## Company Email Rule

All business systems must use company-managed email addresses.

Examples:
- gene@geneindustries.org
- bob@geneindustries.org
- david@huanglee.org

NOT:
- bob123@gmail.com
- randomhotmail@hotmail.com

Personal emails are only used for:
- recovery
- backup communication
- emergency contact

---

## GitHub Rules

Each user creates their OWN GitHub account using their company email.

Example:
- Username: genehuang-ai
- Email: gene@geneindustries.org

The user is then invited into the GitHub organization.

Users must NEVER share GitHub passwords.

---

## 1Password Rules

Each user receives:
- their own 1Password account
- their own master password
- their own MFA

Administrators should never know employee master passwords.

Vault access is granted based on role.

Example:
- Developers → Development vaults
- Finance → Finance vaults
- Executives → Infrastructure vaults

---

## Offboarding Rule

When someone leaves:
1. Suspend Google Workspace account
2. Remove GitHub organization access
3. Disable 1Password access
4. Rotate critical credentials if required

This ensures systems remain secure without manually changing every password.

---

## Why This Structure Exists

This structure allows Gene Industries to scale cleanly:
- employees
- contractors
- clients
- AI developers
- customer projects
- automation systems
- hundreds of repositories

without becoming disorganized or insecure.
