# 🌸 Career Comeback Navigator for Women

> A Generative AI-powered career guidance application designed to help women restart their professional journey after a career break.

## 📌 Project Overview

**Career Comeback Navigator for Women** is a Generative AI application built using **AWS PartyRock**.

The application is designed specifically for women returning to work after a career break due to caregiving, personal reasons, family responsibilities, or other circumstances.

Instead of providing generic career advice, the application analyzes the user's:

- Previous job or field
- Years of experience
- Career break duration
- Reason for the career break
- Current skills
- Experience gained during the career break
- Target career or job role
- Available learning time
- Learning budget
- Confidence level

Based on this information, it generates a personalized **Career Comeback Roadmap**.

---

## 🎯 Problem Statement

Returning to work after a career break can be challenging.

Women may face difficulties such as:

- Identifying transferable skills from previous experience
- Understanding current skill requirements
- Finding suitable career roles
- Identifying skill gaps
- Deciding what to learn and where to learn it
- Managing learning within a limited time and budget
- Preparing for a structured career comeback

There is a need for an accessible and personalized solution that can guide users through these challenges.

---

## 💡 Proposed Solution

**Career Comeback Navigator** uses Generative AI to analyze a user's career profile and generate a personalized career comeback plan.

The application identifies existing strengths, analyzes skill gaps, suggests suitable career paths, recommends learning resources, and provides a structured roadmap for returning to work.

---

## ✨ Key Features

### 1. 📝 Career Assessment

The user provides information about their professional background, career break, skills, experience, target role, learning time, budget, and confidence level.

### 2. ✂️ Transferable Skills Analysis

The application identifies skills that the user already possesses and explains how those skills can be useful in their target career.

For example, skills gained through tailoring and household management can be mapped to areas such as:

- Attention to detail
- Time management
- Budget planning
- Organization
- Problem solving
- Client understanding
- Pattern execution
- Fabric knowledge

### 3. 📊 Skill Gap Analysis

The application categorizes the skills that need to be developed into:

- 🟢 Low Effort Gaps
- 🟡 Medium Effort Gaps
- 🔴 High Effort Gaps

It also provides an estimated time range for developing these skills.

### 4. 💼 Career Role Recommendations

The application identifies suitable career roles based on the user's existing skills, experience, target role, and skill gaps.

For each recommended role, it can provide information such as:

- Salary range
- Growth opportunities
- Required skills
- Difficulty level
- Estimated entry time
- Fit with the user's existing experience

### 5. 📚 Learning Resource Recommendations

The application recommends learning resources according to the user's available budget.

Resources may include:

- YouTube
- Canva Design School
- Coursera
- Pinterest
- Behance
- Vogue India / Elle India
- NIFT learning content
- Other relevant learning platforms

### 6. 🗺️ Personalized Career Comeback Roadmap

The application combines the assessment results into a personalized roadmap.

The roadmap connects the user's existing career background with their target career and provides actionable guidance for moving forward.

### 7. 📋 Final Career Report

The application generates a final career report containing recommended career paths and personalized guidance based on the user's assessment.

---

## 🤖 AI Technology

### Generative AI

Generative AI is used to analyze the information provided by the user and generate personalized career guidance.

The AI transforms the user's career background, existing skills, career-break experience, goals, available time, and budget into structured recommendations.

### AWS PartyRock

The application was created and deployed using **AWS PartyRock**, a platform for building Generative AI applications.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| AWS PartyRock | Building and hosting the Generative AI application |
| Generative AI | Personalized career analysis and recommendations |
| Prompt Engineering | Designing the AI instructions and outputs |

---

## ⚙️ How It Works

```text
                USER
                  │
                  ▼
        ┌───────────────────┐
        │ Career Assessment │
        └─────────┬─────────┘
                  │
                  ▼
        ┌───────────────────┐
        │ Profile Analysis  │
        └─────────┬─────────┘
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
Transferable Skills    Skill Gap Analysis
        │                   │
        └─────────┬─────────┘
                  ▼
        Career Role Recommendations
                  │
                  ▼
        Learning Resources
                  │
                  ▼
        Career Comeback Roadmap
                  │
                  ▼
          Final Career Report
