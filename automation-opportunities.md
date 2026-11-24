# How to identify automation opportunities

Source: [Workflow Field Guide](https://jrefstrupalvear.github.io/workflow-field-guide/)

To identify automation opportunities, follow one recurring task from start to finish. Count how often it happens, time the minutes people actively spend on it, and write down the rule a tool would follow. Subtract the time people would still spend reviewing exceptions. Pilot the task with the strongest measurable benefit and a clear way to catch mistakes.

## What to look for

1. Repeated handling. Look for copying fields, checking a status, sending reminders, or reconciling the same records across tools.
2. A clear trigger. Write down the event that starts the task and what a successful result looks like.
3. Predictable exceptions. Count how often a person must make a judgment. Keep those cases in a review queue.
4. A meaningful baseline. Record weekly volume, active handling time, queue time, and error rates separately.

## Worked example: chasing missing loan documents

Suppose a team handles 80 files per week and spends six minutes per file checking what is missing and sending reminders. The baseline is eight staff hours per week. If a pilot removes half of that work, it frees four hours per week before review. If exception handling takes another hour, the net recovery is three staff hours per week.

Track staff time separately from loan turnaround. Saving three staff hours says little about when a borrower responds. Measure elapsed time and incorrect reminders alongside staff effort.

## Run a one-week workflow audit

[Start with the worked observation sheet](https://jrefstrupalvear.github.io/workflow-field-guide/workflow-observation.html) to see which cases qualify. In its six-case example, three follow the same rule, yet those three account for only 12 of 36 staff minutes. Use the minutes spent on eligible cases to estimate the removable share.

Make one row per task. Record the workflow, trigger, owner, weekly volume, active minutes per item, percentage of work the pilot could remove, and added weekly review time. Sample ordinary cases and exceptions before estimating the removable share.

Net weekly hours recovered = (weekly volume × active minutes per item × removable share ÷ 60) − added weekly review hours.

Rank candidates by net hours recovered, then check rule clarity, error impact and setup effort. Pick a task you can pilot with a human review step. Record the same measures again during the pilot so the comparison uses the same units and workflow boundaries.

## Which task would you automate first?

Suppose the same team is choosing between two pilots. These figures are illustrative. The pilot must reduce staff effort without increasing incorrect decisions.

One week of work under two proposed pilots

| Candidate | Baseline effort | Removable share | Added review | Net hours freed |
| --- | --- | --- | --- | --- |
| Missing-document reminders | 80 files × 6 min = 8 h | 50% | 1 h | 3 h |
| Invoice exception routing | 30 cases × 12 min = 6 h | 75% | 2 h | 2.5 h |

Start with reminders if the missing-document list is reliable and both pilots have similar setup costs. The lead is only 30 minutes a week. If reminder review takes over 90 minutes a week, invoice routing frees more time. Check that assumption on a small batch before investing.

Watch one failure case as well as one ordinary case. If staff send a reminder because two systems disagree about whether a document arrived, fix the status discrepancy first. A faster reminder would amplify the error.

## Choose the first pilot

Pick a workflow with a named owner, measurable volume, and a change you can reverse. Test on a small batch. Check hours recovered, mistakes, and exceptions against the baseline before expanding. If the process has unclear ownership or inconsistent rules, fix those first.
