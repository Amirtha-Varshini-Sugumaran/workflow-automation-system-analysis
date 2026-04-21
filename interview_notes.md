# Interview Notes: Vendor Onboarding Workflow Automation System

## 90-Second Project Explanation

This project is about vendor onboarding for a growing facilities and maintenance company in Dublin.

The company works with different vendors for cleaning supplies, electrical work, repairs, uniforms, and equipment servicing. As the company grows, it needs to bring vendors on quickly, but the current process is handled through email chains, Excel trackers, attachments, and shared folders.

The problem is that nobody has one clear view of where a request stands. Documents are missed, finance and operations sometimes work from different information, and approvals are hard to prove later.

I mapped the current process, identified the main gaps, and designed a simple future-state workflow. The proposed system includes a vendor request form, document checklist, approval stages, status tracking, comments, audit history, and a small dashboard.

The project shows how I would approach a Business Systems Analyst problem: understand the business pain, map the workflow, define requirements, and describe how the system should behave.

## Why This Project Is Relevant

This is relevant because many companies still run important processes through email and spreadsheets.

Vendor onboarding is a good BSA example because it touches operations, finance, admin, vendors, documents, approvals, and system visibility. It is not just one person clicking approve.

It shows that I can think about both the business process and the system behavior needed to support it.

## Key Problems Identified

- Onboarding requests are started through email, so they are easy to lose or delay.
- Documents arrive in different threads and are not always tied clearly to the request.
- Ownership is unclear at each stage.
- Finance and operations may not have the same vendor details.
- Approvals are hard to audit because they sit inside email chains.
- Managers do not have a simple view of pending, overdue, or blocked requests.

## How I Approached the Analysis

I started by thinking through the current journey from the moment an operations coordinator needs a new vendor.

Then I looked at where handoffs happen: operations, vendor admin, finance, manager approval, and the external vendor.

From there, I turned the pain points into requirements. For example, if documents are missed, the system needs a checklist. If ownership is unclear, the system needs a current owner and stage. If approvals are hard to prove, the system needs approval history.

## How I Would Explain the Future-State Workflow

The future process starts with a structured request form instead of an email.

The system checks required fields, stores uploaded documents, and routes the request through vendor admin, operations approval, and finance review.

At each stage, the request has an owner, status, due date, and comments. If something is missing, the reviewer can send it back with a clear reason.

Once approved, the system keeps the history so the business can see who approved what and when.

## What Makes This Different From a Generic Approval-Flow Project

This is not just "submit, approve, done."

The project includes document checks, finance review, duplicate vendor risk, current owner visibility, missing information loops, SLA tracking, audit history, and dashboard thinking.

That makes it closer to a real operational workflow, where the problem is usually not one approval step. It is all the little handoffs around it.

## Likely Interview Questions and Answers

### 1. Why did you choose vendor onboarding?

Because it is a realistic process that many growing companies struggle with. It involves several teams, documents, approvals, and handoffs, so it is a good way to show workflow and systems thinking.

### 2. What was the biggest issue in the current process?

The biggest issue was lack of visibility. Requests moved through emails and trackers, but there was no single place showing status, owner, missing documents, and approval history.

### 3. What was your recommended solution?

I recommended a lightweight workflow system with a request form, document checklist, approval routing, status tracking, comments, audit history, and a basic dashboard.

### 4. Why not suggest a full procurement platform?

For an SME, that would probably be too much at this stage. The business needs control and visibility first. A simpler workflow tool would solve most of the current pain without overcomplicating the process.

### 5. What requirements did you define?

I defined functional requirements like request submission, document upload, approval routing, status tracking, comments, rejection reasons, audit history, search, and reporting. I also included non-functional requirements around access control, usability, auditability, and data validation.

### 6. How did you think about stakeholders?

I looked at who touches the process: operations coordinator, operations manager, finance reviewer, vendor admin, IT/system owner, and the external vendor. Each group has a different need, so the system has to support more than just approval.

### 7. What KPIs would show improvement?

Average onboarding turnaround time, overdue requests, requests blocked by missing documents, first-time completion rate, backlog by owner, and requests completed without rework.

### 8. What does this project show about your BSA skills?

It shows that I can take a messy manual workflow, understand the business impact, define system requirements, create process flows, write business rules, and explain a practical solution clearly.
