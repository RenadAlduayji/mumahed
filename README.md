<p align="center">
  <img src="images/logo.png" width="180" alt="Mumahed logo">
</p>

<h1 align="center">Mumahed | مُمهِّد</h1>
<p align="center"><b>A graduate recruitment app designed for fresh graduates, built around a user-centered design process</b></p>
<p align="center">CS 351 – Human-Computer Interaction · Princess Nourah bint Abdulrahman University · 2025/2026</p>
<p align="center">🎨 <a href="https://www.figma.com/proto/p7SRcWEqox1aInIP8buf5I/project-phase2?node-id=8-5&p=f&scaling=scale-down&content-scaling=fixed&page-id=8%3A3&starting-point-node-id=8%3A5&show-proto-sidebar=1"><b>View the interactive Figma prototype</b></a></p>

---

## The Problem
Most job platforms, such as LinkedIn and Glassdoor, are built for experienced professionals. Fresh graduates have to fill in long profiles, deal with mandatory "work experience" fields they cannot complete, and scroll past senior roles that are mixed into entry-level results.

## Our Solution
**Mumahed** is a mobile-first recruitment app built for that moment. It puts academic projects, COOP training, and skills first, filters for real entry-level roles, and includes an **AI career advisor** that suggests career paths and the courses needed to close skill gaps.

## Design Process

```
Research  →  Personas & Tasks  →  Requirements  →  Prototype  →  Usability Testing  →  Enhancements
```

### 1. User Research
- **Semi-structured interviews** with 6 upcoming graduates, 3 fresh graduates, and 1 HR recruiter
- **Naturalistic observation** of fresh graduates during real job searches

**Key insights**
| Insight | What we found |
|---|---|
| Academic identity | Seniors want graduation projects shown as practical evidence of their skills. |
| The experience paradox | Mandatory experience fields frustrate graduates. They were seen typing "None" just to get past them. |
| Search fatigue | Users spent a lot of time filtering out roles that needed 3+ years of experience. |
| Profile time | Graduates spent **2–4 hours** creating a single profile on existing platforms. |
| Mobile-first | Most users prefer applying on their phones, but current sites scale poorly on mobile. |
| Recruiter efficiency | Quick "candidate cards" with GPA and major would save hours of screening. |

### 2. Personas
- **Noura, 23**: a Computer Science graduate who wants to apply to many jobs quickly and reuse her CV.
- **Ahmad, 35**: an HR recruiter who reviews large numbers of graduate CVs.

### 3. Key Features
**For graduates**
- Profile that highlights graduation projects, academic achievements, and COOP training
- CV templates made for fresh graduates, with export to PDF
- Filters by major, GPA, and **"True Entry-Level"** status
- AI career advisor that recommends courses for skill gaps
- Career Directory that explains job titles and which majors they fit
- Smart notifications for matching jobs

**For recruiters**
- Quick-View candidate cards (major, GPA, university, graduation year)
- Automatic candidate ranking by job fit
- Shortlists, private notes, and ratings for team collaboration

### 4. UX Requirements
- Apply to a job in **3 steps or fewer**
- Set up a basic profile in **under 5 minutes**
- Real-time progress bar while completing a profile
- Minimum **44×44 px** touch targets
- Visual or haptic feedback after a successful application

## Screens I Designed

### Onboarding
Five screens that introduce new users to Mumahed's main features: smart job matching, the CV builder, the interview coach, and the skill gap advisor.

<p align="center">
  <img src="images/onboarding-1-welcome.png" width="150" alt="Welcome">
  <img src="images/onboarding-2-job-matching.png" width="150" alt="Smart Job Matching">
  <img src="images/onboarding-3-cv-builder.png" width="150" alt="CV Builder & Analysis">
  <img src="images/onboarding-4-interview-coach.png" width="150" alt="Interview Coach">
  <img src="images/onboarding-5-skill-gap.png" width="150" alt="Skill Gap Advisor">
</p>

### CV Builder
Graduates can build a CV from templates made for fresh graduates, upload an existing CV, or use the **AI-Powered Smart CV**. Smart CV suggests content for the target job, optimizes the layout, checks ATS keywords, and reviews grammar and tone.

<p align="center">
  <img src="images/cv-builder-templates.png" width="200" alt="CV templates">
  <img src="images/cv-builder-upload.png" width="200" alt="Upload CV">
  <img src="images/cv-builder-smart-cv.png" width="200" alt="AI-Powered Smart CV">
</p>

<p align="center">
  <a href="https://www.figma.com/proto/p7SRcWEqox1aInIP8buf5I/project-phase2?node-id=8-5&p=f&scaling=scale-down&content-scaling=fixed&page-id=8%3A3&starting-point-node-id=8%3A5&show-proto-sidebar=1">
    <img src="https://img.shields.io/badge/▶_Try_the_interactive_prototype-Figma-1E8F6E?style=for-the-badge&logo=figma&logoColor=white" alt="Open Figma prototype">
  </a>
</p>

## Usability Testing
We ran task-based testing with **5 scenarios** covering both user types: a graduate with no CV, a graduate with a CV, a graduate exploring opportunities, an HR employee posting a job for the first time, and an HR employee reviewing applicants. We recorded time on task, errors, and observations for each task.

**Result:** The app was found **usable**. Participants completed more than 70% of the tasks easily, including sign-up, login, browsing, uploading a CV, applying, and checking application status.

**Issues found → design improvements**
| Issue | Improvement |
|---|---|
| First-time users were unsure while building a CV | Step-by-step guidance with a progress indicator for each section |
| Users weren't sure their uploaded CV was strong | CV evaluation score with a strengths and weaknesses summary |
| Low confidence before applying | Profile-to-job **match percentage** shown before applying |
| Users tried to select several filters at once | Multi-select filters and more detailed major sub-categories |
| Unclear fields when HR posted a job | Clearer labels and example hints |
| HR couldn't compare applicants | Side-by-side applicant comparison view |

## My Role
- Came up with the project idea
- Designed the **Mumahed logo**
- Designed the **onboarding flow** (5 screens) and the **CV Builder** screens (templates, CV upload, and AI-Powered Smart CV)

## Team
Renad Alduayji · Lujain Alahmari · Remas Alqahtani · Reuof Jubran · Dai Khalid · Lina Alsarhan

## Documents
- 📄 [Phase 1: Research, personas & requirements](docs/mumahed-phase1-research-and-requirements.pdf)
- 📄 [Phase 2: Logo, prototype & interaction design](docs/mumahed-phase2-prototype.pdf)
- 📄 [Phase 3: Usability testing & enhancements](docs/mumahed-phase3-usability-testing.pdf)
