# Career Hub

A private, version-controlled workspace for managing my career documents, job applications, academic applications, research opportunities, and supporting evidence.

This repository serves as the **single source of truth** for my professional profile. It contains my master career profile, tailored resumes, academic CVs, cover letters, SOPs, scholarship materials, application trackers, and supporting evidence.

> **Privacy:** This repository is intended to remain **private** because it may contain personal information, recruiter communication notes, application history, salary details, reference information, and unpublished application materials.

---

## Purpose

The goal of this repository is to keep my career materials:

- Organized
- Version controlled
- Easy to update
- Easy to tailor for specific roles
- Consistent across applications
- Evidence-based
- Ready for AI-assisted resume and application generation

Instead of maintaining disconnected Word/PDF files, this repository keeps the editable source material in Markdown and exports final versions when needed.

---

## Career Focus

My primary career directions are:

- AI/ML Engineer
- NLP / LLM Engineer
- RAG Engineer
- Research Engineer
- Applied AI Researcher
- Research Assistant / PhD Researcher

Primary research and technical interests include:

- Low-resource NLP
- Bengali NLP
- Large Language Models
- Retrieval-Augmented Generation
- Agentic AI
- Medical AI
- Multimodal Learning
- MLOps
- Explainable Machine Learning

---

## Repository Structure

```text
career-hub/
│
├── README.md
│
├── master-profile/
│   └── Career_Master_Profile_Safaet.md
│
├── resumes/
│   ├── master-resume.md
│   ├── ai-ml-engineer/
│   ├── nlp-engineer/
│   ├── rag-llm-engineer/
│   └── research-engineer/
│
├── academic-cv/
│   ├── academic-cv-master.md
│   ├── phd-cv.md
│   └── research-assistant-cv.md
│
├── applications/
│   └── 2026/
│       └── company-name-role/
│           ├── job-description.md
│           ├── resume.md
│           ├── cover-letter.md
│           ├── interview-notes.md
│           └── application-notes.md
│
├── scholarships/
│   ├── DAAD/
│   ├── GKS/
│   ├── MEXT/
│   └── CSC/
│
├── phd-applications/
│   ├── universities.md
│   ├── professors.md
│   ├── research-statement/
│   └── sop/
│
├── trackers/
│   ├── job-applications.csv
│   ├── phd-applications.csv
│   └── professor-outreach.csv
│
├── templates/
│   ├── resume-template.md
│   ├── cover-letter-template.md
│   ├── sop-template.md
│   └── professor-email-template.md
│
└── evidence/
    ├── projects.md
    ├── publications.md
    ├── achievements.md
    └── skill-evidence.md
```

---

## Core Files

### `master-profile/`

The master career profile is the central source of professional information.

It should contain:

- Personal and professional summary
- Education
- Technical skills
- Work experience
- Projects
- Publications
- Research interests
- Achievements
- Leadership
- Certifications
- Career story
- Resume bullet bank
- Skill evidence
- Career gaps
- Career progress

All tailored documents should be created from this source whenever possible.

---

### `resumes/`

Contains resume versions tailored for different career tracks.

Recommended categories:

- AI/ML Engineer
- NLP Engineer
- LLM / RAG Engineer
- Research Engineer
- General Software + AI roles

Each resume should only include experience and projects relevant to the target job.

Example:

```text
resumes/
└── ai-ml-engineer/
    ├── ai-ml-master.md
    ├── abc-ai-ml-engineer.md
    └── xyz-applied-ai-engineer.md
```

---

### `academic-cv/`

Contains research-oriented CVs for:

- PhD applications
- Research Assistant positions
- Research internships
- Scholarships
- Professor outreach

Academic CVs should emphasize:

- Research interests
- Publications
- Research experience
- Academic projects
- Conferences
- Technical methods
- Teaching or mentoring
- References

---

## Job Application Workflow

For every important job application, create a dedicated folder.

Example:

```text
applications/2026/openai-research-engineer/
├── job-description.md
├── resume.md
├── cover-letter.md
├── interview-notes.md
└── application-notes.md
```

Recommended workflow:

1. Save the full job description.
2. Extract the important requirements and keywords.
3. Select relevant evidence from the master profile.
4. Create a tailored resume.
5. Create a cover letter when needed.
6. Submit the application.
7. Update the application tracker.
8. Add interview notes if contacted.
9. Record the final outcome.
10. Keep the folder for future review.

---

## Application Tracking

The main job tracker is:

```text
trackers/job-applications.csv
```

Recommended columns:

```csv
ID,Company,Role,Location,Source,Applied Date,Deadline,Resume Version,Status,Next Action,Follow-up Date,Interview Stage,Outcome,Notes
```

Recommended application statuses:

```text
Interested
Preparing
Ready to Apply
Applied
Screening
Technical Interview
Final Interview
Offer
Rejected
Withdrawn
Closed
```

---

## GitHub Projects Workflow

A GitHub Project board can be used as the visual application tracker.

Suggested columns:

```text
Interested
   ↓
Preparing
   ↓
Applied
   ↓
Screening
   ↓
Technical Interview
   ↓
Final Interview
   ↓
Offer / Closed
```

Each serious application may also be represented as a GitHub Issue.

Example issue title:

```text
[JOB] AI Engineer — Company Name
```

Example issue body:

```md
## Application Information

**Company:** Company Name  
**Role:** AI Engineer  
**Location:** Remote  
**Job URL:**  
**Application Date:**  
**Deadline:**  

## Documents

- Resume:
- Cover Letter:
- Job Description:

## Status

Applied

## Next Action

Follow up after 7 days.

## Notes

Add recruiter communication, interview information, and lessons learned here.
```

---

## Scholarship Tracking

Scholarship materials are maintained separately because their requirements differ significantly from industry applications.

Current target scholarship categories:

- DAAD
- GKS
- MEXT
- CSC

Each scholarship folder may contain:

```text
scholarships/DAAD/
├── universities.md
├── requirements.md
├── research-proposal.md
├── motivation-letter.md
├── academic-cv.md
├── document-checklist.md
└── application-status.md
```

---

## PhD Application Tracking

The `phd-applications/` directory tracks:

- Target universities
- Target professors
- Research fit
- Professor outreach
- Research statements
- SOPs
- Deadlines
- Funding opportunities
- Application status

A professor tracking table can include:

```text
Professor
University
Country
Research Area
Relevant Papers
Contacted?
Date Contacted
Response
Follow-up Date
Research Fit
Status
```

---

## Evidence-First Rule

Every claim included in a resume, CV, SOP, or cover letter should ideally be traceable to evidence.

Examples:

```text
Claim:
Built a multilingual RAG system.

Evidence:
- Project repository
- Architecture notes
- Evaluation results
- Work experience entry
```

The `evidence/` directory exists to prevent unsupported or exaggerated claims.

Never add a metric to a resume unless it can be reasonably supported.

---

## AI-Assisted Application Workflow

This repository is designed to work well with AI tools.

A recommended prompt pattern is:

```text
Use my Career_Master_Profile as the only source of candidate information.

Analyze the job description and create a tailored resume.

Rules:
1. Do not invent experience, skills, metrics, publications, or achievements.
2. Use only evidence available in my career profile.
3. Prioritize the most relevant experience for the job.
4. Match important job-description keywords naturally.
5. Keep bullets achievement-oriented.
6. Flag missing evidence instead of making assumptions.
```

The same workflow can be used for:

- Resume generation
- Cover letters
- SOPs
- Professor outreach emails
- Interview preparation
- Skill-gap analysis

---

## File Naming Convention

Use descriptive and consistent file names.

### Resume

```text
Safaet_Jaman_Resume_AI_ML_Engineer_CompanyName.md
```

### Academic CV

```text
Safaet_Jaman_Academic_CV_PhD_UniversityName.md
```

### Cover Letter

```text
Safaet_Jaman_Cover_Letter_CompanyName_Role.md
```

### SOP

```text
Safaet_Jaman_SOP_University_Program.md
```

Avoid names such as:

```text
resume-final.md
resume-final2.md
resume-latest-final.md
```

Git already manages version history.

---

## Git Workflow

Before making major application changes:

```bash
git pull
```

After updating documents:

```bash
git add .
git commit -m "Tailor resume for AI Engineer role at Company Name"
git push
```

Useful commit examples:

```text
Update master career profile for September 2026
Add AI Engineer application for Company Name
Tailor RAG Engineer resume for Company Name
Add ECCT publication information
Update PhD professor outreach tracker
Add interview notes for Company Name
```

---

## Branch Strategy

For most career management, working directly on `main` is sufficient.

For major document redesigns, optional branches can be used:

```bash
git checkout -b resume-redesign
```

After review:

```bash
git checkout main
git merge resume-redesign
```

---

## Update Routine

### After completing a project

Update:

```text
master-profile/
evidence/projects.md
resumes/
```

### After publishing research

Update:

```text
master-profile/
evidence/publications.md
academic-cv/
```

### After learning a major skill

Update:

```text
master-profile/
evidence/skill-evidence.md
```

### After every application

Update:

```text
applications/
trackers/job-applications.csv
```

### After every interview

Add:

```text
interview-notes.md
```

Record:

- Questions asked
- Questions I struggled with
- Technical topics to review
- Recruiter feedback
- Lessons learned

---

## Monthly Career Review

At the end of every month:

- Update the master career profile.
- Add new projects and measurable achievements.
- Review skill gaps.
- Update application statistics.
- Review interview conversion rate.
- Update GitHub and portfolio links.
- Review unfinished applications.
- Update research progress.
- Update scholarship / PhD deadlines.
- Archive irrelevant opportunities.

---

## Useful Metrics

Over time, track:

```text
Applications submitted
Resume → screening conversion
Screening → interview conversion
Interview → offer conversion
Applications by job source
Applications by role type
Applications by country
Most successful resume version
Most requested technical skills
Most common interview weaknesses
```

These metrics help improve the application strategy instead of applying blindly.

---

## Public vs Private Content

### Keep Private

- Master career profile
- Personal information
- Phone number
- Private email information
- Job application history
- Recruiter notes
- Salary discussions
- Interview feedback
- Recommendation drafts
- Reference details
- Scholarship documents
- Unpublished SOPs

### Keep Public Separately

My public GitHub profile should contain:

- AI/ML projects
- RAG projects
- NLP projects
- Research implementations
- Open-source contributions
- Project documentation
- Portfolio-quality repositories

The career-management repository itself should remain private.

---

## Source of Truth

The intended information flow is:

```text
Career Master Profile
        │
        ├── Job Resume
        ├── Academic CV
        ├── Cover Letter
        ├── SOP
        ├── Research Statement
        ├── Professor Outreach
        └── Interview Preparation
```

The master profile should be updated first whenever meaningful career information changes.

---

## Long-Term Goal

This repository is not only an archive of applications.

It is a continuously improving **career operating system** that connects:

```text
Learning
   ↓
Projects
   ↓
Research
   ↓
Evidence
   ↓
Resume / CV
   ↓
Applications
   ↓
Interviews
   ↓
Feedback
   ↓
Career Improvement
```

The goal is to make every future application faster, more accurate, better tailored, and supported by real evidence.

---

## Owner

**Safaet Jaman Arman**

AI/ML Engineer · NLP Researcher · LLM/RAG Engineer

---

_Last updated: September 2026_
