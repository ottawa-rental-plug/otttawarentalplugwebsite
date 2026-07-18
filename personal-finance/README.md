# Personal finance — Freedom Ledger

**Not part of the website.** This folder holds a standalone personal tool.

`freedom-ledger.html` is a self-contained budget, debt-snowball, and savings
planner — no build step, no dependencies. Open it directly in any browser
(double-click the file). All numbers are editable in the page and saved in
your browser's local storage only; nothing is sent anywhere.

What it does:

- Models income from biweekly paychecks (including the two 3-paycheck months
  per year) plus lease commission computed as rate × average rent, driven
  by a slider.
- Deploys starting cash on hand in the first plan month.
- Plans a real estate course as a committed monthly bill, with a
  start-now vs. start-after-debt-free choice.
- Runs a snowball or avalanche payoff month by month (optional APR per
  debt, with interest compounding) and projects the debt-free date.
- Debts and expenses can be renamed, added, and removed.
- Continues the same monthly habit into an emergency fund, then points
  at the next milestones (3-month cushion, TFSA investing).
- Includes a rule-based "smart advisor" that compares scenarios (course
  timing, one more lease, payoff order) and flags budget pressure points.
- Shows a projection chart, a milestone timeline, and a month-by-month
  payoff calendar.
