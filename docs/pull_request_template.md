## Description & motivation
Describe your changes, and why you're making them. Is this linked to an open
issue, a Trello card, or another pull request? Link it here.

## Checklist:

This checklist is mostly useful as a reminder of small things that can easily be
forgotten – it is meant as a helpful tool rather than hoops to jump through.
Put an `x` in all the items that apply, make notes next to any that haven't been
addressed, and remove any items that are not relevant to this PR.

- [ ] My pull request represents one logical piece of work.
- [ ] I have added descriptions to all new views and tables
- [ ] I have added column descriptions to all new fields
- [ ] I have thought added uniqueKey assertions and freshness tests where appropriate
- [ ] I have added dependencies on uniqueKey assertions and freshness tests where appropriate
- [ ] My SQL follows the style guide. This includes avoidance of 'SELECT *', used snakecase column names
- [ ] I have not pulled in any new data that may contain PID or health data without checking on #tech-data slack
- [ ] I have executed all models sucessfully
