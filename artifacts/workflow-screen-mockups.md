# Low-Fidelity Screen Mockups

These are simple text mockups for the proposed vendor onboarding workflow system.

## 1. Submit Vendor Request Screen

```text
--------------------------------------------------
Submit Vendor Onboarding Request
--------------------------------------------------
Vendor Name:              [_____________________]
Vendor Category:          [Cleaning Supplies v]
Primary Contact Name:     [_____________________]
Contact Email:            [_____________________]
Phone Number:             [_____________________]
Reason for Onboarding:    [_____________________]
Client Site / Area:       [_____________________]

Required Documents
[ ] Insurance Certificate     [Upload]
[ ] Tax Clearance             [Upload]
[ ] Bank Details Form         [Upload]
[ ] Safety Documents / RAMS   [Upload]

[Save Draft]   [Submit Request]
--------------------------------------------------
```

## 2. Review Queue Screen

```text
--------------------------------------------------
Vendor Onboarding Review Queue
--------------------------------------------------
Filters: [Status v] [Owner v] [Category v] [Overdue only]

ID       Vendor Name            Stage              Owner          Due Date     Status
VON-002  Northside Electrical   Document check     Laura Keane    10 Apr      Blocked
VON-003  RapidFix Repairs       Ops approval       Conor Walsh    11 Apr      Pending
VON-004  WorkWear Direct        Finance review     Niamh Kelly    12 Apr      Blocked
VON-006  GreenSafe Pest Control Document check     Laura Keane    15 Apr      Overdue

[Open Selected Request]
--------------------------------------------------
```

## 3. Request Detail / Approval Screen

```text
--------------------------------------------------
Vendor Request: VON-003 - RapidFix Repairs
--------------------------------------------------
Current Stage: Operations Approval
Current Owner: Conor Walsh
SLA Due Date: 11 Apr 2026
Status: Pending

Vendor Details
- Category: Emergency repairs
- Submitted by: Sarah Doyle
- Client site need: New retail site support

Document Checklist
[x] Insurance Certificate
[x] Tax Clearance
[x] Bank Details Form
[x] Safety Documents / RAMS

Comments
- Vendor admin: Documents checked, all complete.

Decision
[Approve]  [Reject]  [Request More Information]
Reason / Comment:
[______________________________________________]
--------------------------------------------------
```

## 4. Dashboard Screen

```text
--------------------------------------------------
Vendor Onboarding Dashboard
--------------------------------------------------
Total Requests: 12
Pending: 5
Overdue: 2
Blocked by Missing Documents: 3
Average Turnaround: 6.4 days

Requests by Stage
- Document Check: 4
- Operations Approval: 2
- Finance Review: 3
- Complete: 3

Backlog by Owner
- Laura Keane: 4
- Niamh Kelly: 3
- Conor Walsh: 2

[View Overdue] [Export Tracker]
--------------------------------------------------
```
