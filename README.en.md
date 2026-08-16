**English** | [简体中文](./README.zh-CN.md)

# Career Analysis Skill

Career Analysis Skill is a career analysis tool for job seekers. Instead of relying mainly on what you can remember or what is already written on your resume, it looks through your real work files to uncover evidence of what you have actually done, which capabilities you have built, and which strengths may have been overlooked or underestimated.

You do not need to remember the details of every project from years ago, nor do you need to manually read, deduplicate, categorize, or rename a large archive of work files. The Skill first identifies materials with meaningful career evidence, builds a **Career Evidence Package**, and then uses that evidence to analyze your strengths, gaps, career direction, and positioning.

**Current status: Public Beta**

## Why does this exist?

Using AI to write resumes, improve bullet points, and tailor applications to job descriptions has become a normal part of the job search process. Presenting your experience clearly and competitively is useful.

But most resume optimization starts from one limitation: it can only work with the experiences you have already remembered and written down.

After several years of work, many project details fade. A difficult problem you spent months solving, a complex cross-functional project, or a method you gradually developed may now be reduced to a single resume bullet — or may not appear on your resume at all.

At the same time, traces of that work often still exist in project plans, presentations, retrospectives, data files, meeting notes, schedules, reports, and final deliverables.

Those files can reveal things that memory alone often misses: the kinds of problems you repeatedly solved, why certain responsibilities were given to you, where you consistently performed well, and which capabilities appeared across multiple projects even though you never thought of them as professional strengths.

Career Analysis Skill is designed to bring that information back into view.

## How does it work?

A resume can be part of the analysis, but it is not the center of it. Think of your resume as a summary of **how you currently describe yourself**, while your work files provide another layer of information: **what actually happened in your work**.

You can start with a large archive of historical work files. You do not need to decide in advance which projects are the “most important.” The Skill first filters the material, identifies files with stronger career-analysis value, and gradually builds a Career Evidence Package.

```text
Historical work files
        ↓
Identify relevant materials
        ↓
Career Evidence Package
        ↓
Reconstruct project facts and personal contribution
        ↓
Identify recurring capability evidence
        ↓
Analyze capability structure, career direction, and positioning
```

Career Evidence does not mean automatically attributing every result found in a document to you personally. Work files preserve more context than memory alone, but they may also describe team outcomes, lack important context, or make it unclear who actually led a piece of work.

The Skill therefore tries to distinguish between participation and ownership, team outcomes and individual contribution, and the difference between having encountered a type of work and having developed a repeatable capability.

The goal is not to build the most impressive possible professional image. It is to help you see a **more complete version of your actual professional experience**.

## What will you get?

After the analysis, the Skill generates a structured career analysis report based on the Career Evidence Package. The goal is not simply to summarize your past work, but to reorganize evidence scattered across different projects and files into something useful for career decisions.

The report may include:

* **Career history and core projects** — the experiences that make up the most meaningful parts of your professional track record.
* **Core capabilities and supporting evidence** — what real projects or work records support each capability assessment.
* **Capability strengths** — abilities that appear repeatedly across different projects and have developed into relatively stable strengths.
* **Underestimated capabilities** — abilities already demonstrated in your work but rarely reflected in your resume or self-description.
* **Capability gaps and evidence gaps** — areas where your experience is currently weaker or where there is not yet enough evidence to support a strong claim.
* **Capability structure and transferable skills** — which parts of your existing experience may transfer to new roles or career directions.
* **Career direction and role positioning** — which directions may be more compatible with your existing experience and how you may position yourself professionally.
* **Resume calibration** — if a resume is included, the Skill can compare it with your work evidence to identify important strengths that may be missing, understated, or inaccurately represented.

This is not primarily a tool for finding weaknesses. In many cases, the more valuable outcome is realizing that **you have built more than you currently remember or know how to describe**.

The report can then become a foundation for rewriting your resume, choosing target roles, evaluating career directions, and preparing the next stage of your job search.

## When is it useful?

**Before rewriting your resume**

You can first analyze your real work history, understand what you have actually built, and then decide which experiences deserve space on your resume, what should become a core selling point, and how you want to position yourself.

**After your resume has already been optimized with AI**

The purpose is not to undo or criticize the optimization. Instead, you can place that polished resume back alongside your real work evidence and ask different questions:

Are there important capabilities that are still missing? Did the resume tool mainly improve what was already written while overlooking stronger evidence hidden in older projects? Does the professional image presented by the resume actually reflect the most competitive parts of your experience?

Career Analysis Skill and resume optimization tools are therefore complementary.

One helps you express your experience better.

The other helps make sure you have **more real, specific, traceable experience worth expressing in the first place**.

## Who is it for?

This Skill may be useful if you have been working for some time, have accumulated a large archive of project materials, but still find it difficult to explain what you have really built over the years.

It is especially relevant for people who are:

* actively job searching
* preparing to rewrite their resume
* considering a role or career transition
* unsure how to summarize a complex career history
* trying to identify their strongest transferable capabilities
* using AI resume tools but wanting a deeper understanding of their actual professional strengths

You do not need to build a polished project portfolio before using it. You also do not need to spend days organizing your historical files.

Your existing work materials are the starting point.

## Current testing status

Career Analysis Skill is currently in **Public Beta**.

The current version has completed end-to-end testing across the main workflow, including:

* Skill installation
* historical work-file screening
* Career Evidence Package construction
* career evidence identification
* capability analysis
* career direction analysis
* career positioning

The full workflow has been tested using real work materials.

However, the current real-world test samples mainly come from backgrounds related to **marketing, public relations, and event planning**.

For that reason, **cross-industry generalization still needs validation from real users**.

Engineering, product, HR, finance, sales, supply chain, design, and other professional fields are important areas for further testing. English-language work materials and English-language workflows also require more validation.

The purpose of the Public Beta is not to prove that the Skill works equally well for every profession. It is to gradually discover where this evidence-based approach works well, where it performs poorly, and what its real boundaries are.

## Installation

Download the complete repository and keep the directory structure intact:

```text
career-analysis-skill/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── evidence-framework.md
    └── report-outline.md
```

Do not copy only `SKILL.md`. The files under `references` are part of the full analysis workflow.

The current version has been installed and tested successfully in **Codex and WorkBuddy**.

Other environments that support Agent Skills still require further validation.

## Privacy

Real work files may contain sensitive information such as client data, internal company information, commercial data, budgets, contracts, or confidential project materials.

Please decide what files are appropriate to use based on your AI environment and your organization's policies, and redact sensitive information where necessary.

**Do not upload your resume or work files to this GitHub repository.**

If you participate in the Public Beta, you do not need to send any original files to the project author. Run the Skill in your own environment and share only your feedback.

## Feedback

Career Analysis Skill is still undergoing cross-industry validation. If you are willing to test it, feedback through GitHub Issues is very welcome.

Useful feedback includes:

* your industry, role, and approximate years of experience
* whether the Skill understood your work correctly
* whether the selected files were actually relevant
* whether the Career Evidence Package missed important projects
* whether team outcomes were incorrectly attributed to you personally
* whether the Skill uncovered capabilities you had previously overlooked or underestimated
* whether the identified strengths, gaps, and career positioning felt accurate
* whether any conclusions were made without sufficient evidence
* which parts of the final report were most useful
* which parts clearly need improvement

**You do not need to submit your resume, work files, or complete analysis report.**

If you come from a profession that has not yet been tested, even a poor result is useful. One goal of the Public Beta is to understand where this approach works — and where it does not.

## License

This project does not currently include an open-source license.

Until a license is explicitly added, please do not assume that the project may be freely copied, modified, redistributed, or used commercially.

---

**Career Analysis Skill — Public Beta**
