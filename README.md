Summary

PharmaTech's made some real progress with their unified trackers, automated alerts, and structured meetings. But they still struggle to turn info into action. In all three case scenarios, I noticed a similar issue: while systems are in place to report problems, there aren't strong enough mechanisms for ownership, learning, or accountability. So, despite all the reporting, there are still visibility gaps. Root causes stay undocumented too, and meetings end up wasting lots of time. These problems get even worse as the company grows from two to eight CDMO projects.

⸻

PART A – DIAGNOSIS

Situation A – The Alert Nobody Responds To

Stated Problem

The stated problem is that the automated alert system is functioning correctly, but people are not responding to the alerts. Anil and Karthik believe they have done their job by generating and distributing the report, while the CEO believes he still lacks visibility into operations.

What Is Actually Going On?

I don't think this is about visibility. The CEO already gets info every morning. The real problem? The alert system doesn't make anyone accountable.

Sure, the email highlights an existing issue. But it doesn't say who owns it, what actions are being taken, if it's been escalated, or why it stays unresolved. Since accountability is at the department level and not for specific individuals, nobody feels personally responsible when something turns red.

The organization has built a reporting mechanism, but not an execution mechanism.

Evidence

The advisor noted the tracker only lists department names like Purchase, Warehouse, and Quality, not specific owners. Plus, the alert email doesn't include escalation history or ownership info. It also lacks trend visibility.

Most importantly, the same red items keep showing up for days, meaning everyone's aware but nobody takes action.

⸻

Situation B – The Blank Field

Stated Problem

Anil and Karthik believe employees are not disciplined enough to complete the root cause field in deviation reports.

What Is Actually Going On?

This is mainly a psychological safety issue rather than a disciplinary one.

Supervisors' comments show that employees have learned reporting the real root cause often leads to scrutiny, questioning, or public criticism. So, when staff think honesty raises their personal risk, they naturally avoid noting sensitive info. It's about self-protection in that environment.

The issue isn’t that employees don’t know the root cause; it’s that the organization’s response actually discourages transparency.

Evidence

One supervisor said that being honest about the root cause leads to intense grilling in meetings. Another recalled a case where the maintenance head got publicly ripped after an honest document. Plus, with 70% of root cause sections empty or too vague, it looks like this is due to a system-wide problem, not just careless slip-ups.

Why Anil and Karthik Missed It

Anil and Karthik concentrated more on process compliance than human behavior. They spotted incomplete forms and figured employees were lax. Yet, they didn't look into why folks skipped certain fields. So, they fixed the symptom, not the root cause, basically.

⸻

Situation C – The Meeting That Eats the Day

Stated Problem

The team believes meetings become lengthy because technical issues require discussion.

What Is Actually Going On?

I think this is more of a planning issue than a meeting one.

The company doesn't do daily planning or track unscheduled tasks properly. Plus, there's no set way to sort through different activities. Since there's no official system for handling unexpected stuff, every unresolved problem ends up being discussed in the daily meeting.

Now, the meeting is like a catch-all place where everyone talks about status updates, technical stuff, planning, and putting out fires at the same time.

So, the long meetings are actually symptoms of operational issues, not the main problem themselves.

Evidence

The advisor found there are no daily plans. Employees handle weekly and monthly planning, yet not for each day's tasks. Plus, unscheduled work isn’t logged anywhere. Also, a meeting meant to last thirty minutes often goes to an hour or more. This shows the work discussed should actually be dealt with outside that meeting.
⸻

PART C – SCALE THINKING

What Breaks First?

The most dangerous failure point is dependency on individuals for coordination.

Currently, many operational activities depend on Anil, Karthik, and the COO manually following up with departments, reminding people of commitments, and ensuring that tasks move forward. This model may work with two CDMO projects, but it will not scale effectively to eight projects.

As complexity increases, follow-up activities grow exponentially. Eventually, critical tasks will be delayed simply because nobody has the capacity to manually coordinate everything.

Prevention System

I would implement an Execution Ownership Framework.

Every task would contain:

* Named owner
* Due date
* Dependencies
* Escalation path
* Current status
* Next action

The objective is to ensure that work moves through a structured process rather than relying on individual memory and follow-up.

Automation vs Human Judgment

I would automate repetitive administrative activities such as reminders, overdue notifications, escalation triggers, dashboard generation, and trend reporting.

However, I would keep root cause discussions, prioritization decisions, coaching conversations, and conflict resolution human-led.

Automation is most effective when handling information flow. Human intervention remains essential for trust, judgment, and behavioral change.

⸻

Conclusion

The three situations described in this case appear different on the surface, but they are deeply connected. Ignored alerts, blank root cause fields, and excessively long meetings all stem from a common challenge: the organization has invested heavily in reporting mechanisms but has not yet developed equally strong accountability and learning mechanisms. As the company scales its CDMO operations, strengthening ownership, psychological safety, and execution discipline will be far more important than introducing additional dashboards or software tools.

⸻

PART B – INTERVENTION DESIGN

Situation A – The Alert Nobody Responds To

First Conversation

My first conversation would be with the COO and two department heads whose tasks frequently appear in red status.

Instead of asking why the alerts are being ignored, I would ask them to walk me through the life cycle of a red task.

Questions I would ask:

* What happens when you first see a red item?
* Who is expected to take action?
* How do you decide whether to escalate?
* What prevents the task from moving forward?
* At what point do you ask for help?

The purpose of this conversation is to understand whether the problem is lack of ownership, lack of authority, conflicting priorities, or unclear escalation.

⸻

What Changes in the First Two Weeks?

I would not introduce new software immediately.

First, I would introduce three operational rules:

Rule 1: Every task must have a named owner.

Not Purchase Department.

Not Warehouse.

An individual person.

⸻

Rule 2: Every red item must include a next action.

Instead of:

“Pending”

The task must state:

* What is blocking progress?
* What will happen next?
* By when?

⸻

Rule 3: Escalation becomes automatic.

If a task remains red beyond a predefined period, responsibility moves upward.

This prevents problems from sitting unnoticed.

⸻

Tool Design

What the User Sees

A simple dashboard containing:

Task	Owner	Status	Days Overdue	Next Action	Escalation Level

Instead of seeing:

Purchase – Red

The CEO sees:

Dinesh – PO Approval Delayed – 3 Days Overdue – Waiting for Vendor Confirmation

⸻

Workflow

Task assigned

↓

Owner updates status

↓

If overdue, system requests reason

↓

Escalation triggered after predefined period

↓

COO notified

↓

Trend tracked weekly

⸻

Technology Used

* Excel
* Power Automate
* Email

Reason:

The organization already uses Excel successfully.

Previous software adoption attempts failed.

The solution should fit existing behavior rather than force a completely new workflow.

⸻

Buy-In Strategy

For a supervisor with 15 years of experience, I would avoid talking about dashboards.

Instead, I would say:

“Right now people call you repeatedly for updates because nobody knows who owns what. My goal is to reduce those interruptions. If we make ownership visible once, you won’t have to answer the same question multiple times.”

This connects the system to a problem they experience personally.

⸻

Situation B – The Blank Field

First Conversation

My first conversations would be with supervisors and operators, not managers.

I would ask:

* What happens after a deviation is reported?
* What makes people hesitant to write root causes?
* Have you ever regretted documenting a root cause honestly?
* What would make you comfortable reporting issues openly?

The goal is to understand fear before changing the process.

⸻

What Changes in the First Two Weeks?

I would focus on changing review behavior.

For two weeks:

* Root cause reviews would focus on learning rather than blame.
* Discussions would begin with process failures rather than people failures.
* Managers would be encouraged to ask “What allowed this to happen?” instead of “Who caused this?”

I would also review past deviations and identify recurring themes.

This demonstrates that reporting is valuable.

⸻

Tool Design

What the User Sees

A simplified deviation form.

Fields:

* What happened?
* What was the immediate impact?
* What do you think caused it?
* How confident are you?

Confidence Options:

* High
* Medium
* Low

This allows people to report uncertainty honestly.

⸻

Workflow

Deviation reported

↓

Supervisor enters preliminary cause

↓

Investigation team reviews

↓

Final root cause approved

↓

Corrective action assigned

↓

Lessons learned added to knowledge log

⸻

Technology Used

* Excel Form
* Power Automate reminders
* Claude-generated trend summaries

Claude can summarize recurring deviations and identify patterns across departments.

⸻

Buy-In Strategy

I would tell supervisors:

“This form is not designed to find fault. It is designed to prevent the same issue from happening again. If the real cause is hidden, the same problem will come back and create more work for everyone.”

I would also publicly appreciate honest reporting when it leads to improvements.

⸻

Situation C – The Meeting That Eats the Day

First Conversation

I would sit with department heads and ask:

* How much of your day is planned?
* How much is unexpected?
* What typically interrupts your work?
* Which issues repeatedly consume meeting time?

The objective is to understand the sources of unplanned work.

⸻

What Changes in the First Two Weeks?

I would introduce a simple work classification system.

Every activity must be categorized as:

Routine

Recurring operational activities.

Planned

Project-related activities.

Unplanned

Breakdowns, urgent requests, deviations, and emergencies.

For two weeks, the goal would simply be visibility.

No automation.

Just observation.

⸻

I would also redesign the daily meeting.

Daily meeting agenda:

* Yesterday’s commitments
* Today’s blockers
* Escalations

Technical investigations would be moved into separate focused discussions.

⸻

Tool Design

What the User Sees

Daily Planning Sheet

Task	Category	Owner	Planned Time
Vendor Follow-up	Planned	Ravi	1 Hour
Equipment Breakdown	Unplanned	Arun	2 Hours

At the end of the day, teams record how much time went into unplanned activities.

⸻

Workflow

Morning plan created

↓

Work executed

↓

Unplanned activities logged

↓

Weekly review conducted

↓

Patterns identified

↓

Preventive actions assigned

⸻

Technology Used

* Excel
* Power Automate
* WhatsApp reminders

Again, the objective is simplicity and adoption.

⸻

Buy-In Strategy

Many experienced supervisors may see planning as extra paperwork.

I would avoid explaining it as a reporting exercise.

Instead, I would show them:

“Last week your team spent 11 hours on unexpected breakdowns. If we understand why those interruptions happen, we can reduce them and make your day easier.”

The conversation becomes about reducing firefighting rather than increasing administration.

⸻

Key Insight

For all three situations, my approach would follow the same sequence:

Understand behavior → Change habits → Reinforce with tools

I would deliberately avoid introducing new software until people understand why the change matters and experience value from it. Technology should reinforce a better process, not compensate for a broken one.

⸻

PART C – SCALE THINKING

What Breaks First as the Company Scales?

The most dangerous failure point is not the software, meetings, or dashboards. The biggest risk is the organization’s dependence on a few individuals to drive execution.

Today, Anil and Karthik spend a significant portion of their time following up with departments, collecting updates, resolving coordination issues, and ensuring commitments are completed. The COO also plays a major role in connecting information across departments. This model may work when there are only two active CDMO projects, but it becomes increasingly fragile as project volume grows.

When the company scales to eight projects, the number of dependencies, approvals, delays, and cross-functional interactions will increase significantly. If execution continues to depend on a few people manually tracking progress, bottlenecks will form quickly. Tasks will be delayed, important information will be missed, and leaders will spend more time chasing updates than solving problems.

The biggest scaling risk is therefore the absence of a structured ownership and dependency management system.

⸻

What System Would I Build Today to Prevent This?

In the first three months, I would build an Execution Control System that standardizes how work is planned, owned, tracked, and escalated across all departments.

The objective is to ensure that execution happens through a system rather than through individual follow-ups.

Every significant activity would contain:

* Task Name
* Individual Owner
* Department
* Due Date
* Dependency
* Current Status
* Risk Level
* Escalation Level
* Next Action

For example:

Task	Owner	Dependency	Due Date	Status
Raw Material Approval	Dinesh	Vendor COA	10 Jun	Amber

Instead of asking:

“Purchase Department, what’s the update?”

the organization asks:

“Dinesh, your dependency is still pending. What support do you need?”

This system creates accountability at the individual level while also exposing bottlenecks before they become delays.

As more analysts join the organization, they can operate using the same framework rather than developing their own tracking methods.

⸻

What Would This Look Like at 8 Projects?

At eight CDMO projects, the system would provide:

Leadership View

* Project health status
* Escalated risks
* Dependency bottlenecks
* Resource conflicts

Department Head View

* Team commitments
* Upcoming deadlines
* Overdue actions
* Escalation alerts

Supervisor View

* Today’s priorities
* Assigned actions
* Pending approvals
* Immediate blockers

This creates visibility at every level without requiring constant manual follow-up.

⸻

Automation vs Human Judgment

As the company grows, not everything should be automated.

The goal should be to automate repetitive information flow while keeping critical decisions human.

Activities I Would Automate

Reminder Notifications

Automatic alerts for:

* upcoming deadlines
* overdue tasks
* pending approvals

Reason:

These activities are repetitive and rule-based.

⸻

Escalation Tracking

If a task remains unresolved beyond a defined period:

* notify HOD
* notify COO
* notify leadership

Reason:

Escalations should not depend on someone remembering to send an email.

⸻

Dashboard Generation

Automated reporting of:

* task status
* overdue actions
* department trends
* project health

Reason:

People should spend time solving problems rather than compiling reports.

⸻

Trend Analysis

Use Claude or AI tools to analyze:

* recurring deviations
* common delays
* repeated bottlenecks

Reason:

AI is effective at identifying patterns across large amounts of operational data.

⸻

Activities I Would Keep Human

Root Cause Analysis

Determining why something happened requires context, judgment, and discussion.

AI can support analysis, but humans must own conclusions.

⸻

Planning and Prioritization

Managers must decide:

* what matters most
* which tasks take priority
* how resources are allocated

These decisions depend on business realities that change daily.

⸻

Coaching and Behavior Change

Building trust with supervisors, encouraging honest reporting, and improving accountability cannot be automated.

These are relationship-driven activities.

⸻

Conflict Resolution

Many operational problems involve disagreements between departments.

For example:

* Production vs Maintenance
* Purchase vs Warehouse
* QA vs Operations

These require human conversations, not automated workflows.

⸻

Why This Balance Matters

The company’s previous software implementation failed because technology was introduced before behavior changed.

If the organization attempts to automate everything, adoption will likely fail again.

If everything remains manual, the company will not scale.

The correct approach is to automate information movement while keeping decision-making and relationship management human.

This allows technology to reduce administrative effort while preserving the judgment, trust, and collaboration required for effective execution.

⸻

Final Insight

The company’s challenge is not a lack of data. It already has trackers, alerts, dashboards, and meetings. The challenge is converting information into consistent action.
