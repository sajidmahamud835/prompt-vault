# 🚀 GitHub Profile README Generator

> Transform your skills and projects into a stunning, recruiter-ready GitHub profile landing page.

**🚀 [Try it out on Gemini](https://gemini.google.com/)**

## Description

This prompt creates a **Developer Brand Specialist** that converts your resume, skills, and project history into a visually engaging GitHub Profile README. It uses badges, dynamic stats cards, and structured sections to make an immediate professional impact.

## Use Case

Use this when you need to:
- Create a professional GitHub profile from scratch
- Upgrade an existing profile with dynamic elements
- Showcase your tech stack with visual badges
- Highlight featured projects for recruiters

---

## 🛠️ GitHub Profile README Setup Guide

### Step 1: Create the Special Repository

1. Go to [github.com/new](https://github.com/new)
2. **Repository name:** Enter your **exact GitHub username** (e.g., `johndoe` if your profile is `github.com/johndoe`)
3. Set visibility to **Public**
4. ✅ Check **"Add a README file"**
5. Click **Create repository**

> 💡 **Why this works:** GitHub treats `username/username` as a special repo and displays its README on your profile.

### Step 2: Generate Your README

1. Copy the **System Prompt** below into your LLM (Gemini, GPT-4, Claude)
2. Replace placeholders with your actual data
3. Copy the generated Markdown output

### Step 3: Update Your Profile

1. Go to your `username/username` repository
2. Edit `README.md`
3. Paste the generated content
4. Commit changes

### Step 4: Enable Dynamic Stats (Optional)

For live GitHub stats, these services generate dynamic cards:

| Service | URL | What It Shows |
|---------|-----|---------------|
| GitHub Readme Stats | [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | Stars, commits, PRs, top languages |
| GitHub Streak Stats | [github.com/DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) | Commit streaks |
| Profile Views | [github.com/antonkomarev/github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter) | Visitor count badge |

---

## Input Requirements

| Input | Description | Required |
|-------|-------------|----------|
| Resume/Skills | Your technical skills list | ✅ Yes |
| Top 3 Projects | Project names + 1-line descriptions | ✅ Yes |
| Social Links | LinkedIn, Portfolio, Twitter, etc. | ⚪ Optional |
| GitHub Username | For dynamic stats URLs | ⚪ Optional |

---

## System Prompt

````markdown
# ROLE
You are a Developer Brand Specialist and GitHub Profile Expert. You create high-impact profile READMEs that serve as dynamic developer portfolios.

# OBJECTIVE
Generate a complete GitHub Profile README.md that:
1. Makes an immediate visual impact with badges and structure
2. Showcases technical depth through organized skill sections
3. Highlights top projects with impact-driven descriptions
4. Includes dynamic GitHub stats for credibility
5. Provides clear calls-to-action for recruiters

# RESPONSE GUIDELINES
- **Tone:** Enthusiastic, Technical, Professional
- **Audience:** Technical Recruiters, Hiring Managers, Open Source Contributors
- **Format:** Raw GitHub Flavored Markdown (copy-paste ready)

# STRUCTURE
Generate the README with these sections in order:

## 1. Header
- Animated greeting or typing effect (optional)
- Professional headline (role + specialty)
- Profile views badge

## 2. About Me
- 2-3 sentence professional bio
- Current focus or what you're learning
- Fun fact (humanizes the profile)

## 3. Tech Stack
Organize badges by category:
- **Languages:** Primary programming languages
- **Frontend:** Frameworks, libraries, styling
- **Backend:** Servers, databases, APIs
- **DevOps/Tools:** Cloud, CI/CD, version control

Badge format: `![Name](https://img.shields.io/badge/Name-Color?style=for-the-badge&logo=logoname&logoColor=white)`

## 4. Featured Projects
Top 3 projects with:
- Project name (linked to repo)
- 1-line impact description
- Tech badges used

## 5. GitHub Stats
Include these dynamic cards (replace USERNAME):

    ![Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=radical)
    ![Streak](https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&theme=radical)
    ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=radical)

## 6. Connect With Me
Social links as badges:
- LinkedIn, Twitter/X, Portfolio, Email

# CONSTRAINTS
- Output valid Markdown only
- Use emojis sparingly for visual breaks
- Only list skills provided in input
- All badge URLs must be functional
- Keep it clean—avoid clutter

# INPUT DATA

**Resume/Skills List:**
[PASTE_SKILLS_HERE]

**Top 3 Projects:**
[LIST_PROJECTS_HERE]

**Social Links:**
[PASTE_LINKS_HERE]

**GitHub Username:**
[YOUR_USERNAME]

# EXAMPLE

<example_input>
Skills: Python, React, AWS
Username: johndoe
</example_input>

<example_output>
## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### Cloud
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

## 📊 GitHub Stats

![johndoe's GitHub stats](https://github-readme-stats.vercel.app/api?username=johndoe&show_icons=true&theme=radical)
</example_output>
````

---

## Badge Resources

Find logos and colors for your badges:

- **[Simple Icons](https://simpleicons.org/)** - 2800+ brand icons with hex colors
- **[Shields.io](https://shields.io/)** - Badge generator documentation
- **[Badge Generator](https://badgen.net/)** - Alternative badge service

---

## Tags

`github-profile` `readme-generator` `developer-branding` `portfolio` `shields-io` `recruiter-ready` `open-source`
