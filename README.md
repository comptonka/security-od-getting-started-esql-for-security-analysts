# Content Outline Proposal
**Purpose of a Content Outline:**  a structured plan that organizes what will be taught in a course and in what order. It acts like a roadmap for course development. The outline, to include LOs, should remain flexible during development. Design is iterative, not linear! 

**Content Development Cycle:** After the content outline has been reviewed and approved by peers, SME, and ISD, the content dev can go straight to developing their track in Instruqt. This eliminates the need for a “Track Plan”.

**Example AI Prompt:**
```Act as a senior instructional designer with expertise in cybersecurity and eLearning course development.
Create a structured content outline (not full content) using the template below for a short, self-paced eLearning course.
The course must align to the Apply level of Bloom’s Revised Taxonomy. Learners must be able to write and execute basic ES|QL queries in realistic security investigation scenarios.
Keep the tone professional, concise, and beginner-friendly. Focus on real-world application rather than theory.
Use this exact structure and headings:
-
Title:
 Getting Started with ES|QL for Security Analysts

Content Description:
 (Write a brief paragraph describing what learners will gain and why it matters to their role.)

Target Audience:
- Security Operations Engineer
- Security Analyst (Network)
- Endpoint Analyst
- Threat Hunter
- Threat Intelligence Analyst

Content Prerequisites (Courses required before taking this course):
Discover: Getting Started with Kibana

Terminal Learning Outcome (TLO):
Write one measurable Apply-level objective describing what learners will be able to do using ES|QL in a security context.

Enabling Learning Outcomes (ELOs):
 For each ELO, include:

- Objective (measurable and scaffolded toward the TLO)
- Topic(s) covered
- Learning Activity (interactive eLearning-based)
- Assessment Type (knowledge check, scenario-based question, hands-on query practice, etc.)

Include 3–5 ELOs that logically build from foundational understanding to applied query execution.

Infrastructure Requirements:
 List any system, lab, data, or platform requirements needed to support hands-on ES|QL practice (e.g., Kibana access, sample datasets, sandbox environment).
-

Ensure strong alignment between the TLO, ELOs, learning activities, and assessments.
Avoid unnecessary Elasticsearch architecture theory unless directly required for writing and executing ES|QL queries.
Design the outline for 45-60 minutes of total seat time, divided into short, bite-sized segments.

```

## Options for creating a content outline:

1. Submit your content outline as a sub-issue of the Track ticket (story) using the [content outline issue template](https://github.com/comptonka/security-od-getting-started-esql-for-security-analysts/issues/templates/edit). REPO: [curriculum-engineering[(https://github.com/elastic/curriculum-engineering/issues)
- Peer and SME reviews - comment on the issue
- Content dev edits the outline based on feedback
- Move the ticket to the "Content Outline Review" column and label the ticket `team:isd`
- ISD reviews content outline in the issue 
