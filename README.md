# PHP pre-commit hook

A nice pre-commit hook for PHP developers.

It:
1) Validates the change set against an "allownonasci" configuration flag that decides whether non-ASCII characters are allowed in commit names or not
1) Prevents `var_dump()` calls from being committed (to save you from yourself!)
1) Prevents `TODO` comments without a JIRA-style ticket reference (e.g. JIRA-1234) in the same line (to ensure tech debt items are captured and not just left to rot in the forgotten TODO pile...

