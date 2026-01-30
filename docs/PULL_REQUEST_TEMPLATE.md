# Pull Request Template

## Change Description
_Check PR Sanitization for a good description_

## What Changed
Detailed explanation of the modifications made. Include:
- Type of change: Bug fix, feature implementation, breaking changes, decoration, configuration, version change, refactoring etc.
- What logic changed and why
- Any significant implementation decisions

## Why
Explain the motivation and rationale for these changes:
- What problem does this solve?
- What requirements does this fulfill?
- Why is this the right approach?

## Testing
How should reviewers test these changes?
Add steps here if manual, or ignore if automated tests are added or planned in future.
1. Step 1
2. Step 2
3. Step 3

## Deployment & Breaking Changes
List any breaking changes and migration instructions:
- Breaking change 1: Migration steps
- Breaking change 2: Migration steps

Refer this checklist:
- [ ] This change requires a database migration
- [ ] This change requires environment variable updates
- [ ] This change requires a new dependency installation
- [ ] This changes needs a new feature flag to be added
- [ ] No deployment steps required
- [ ] Other (please describe)



## Checklists

Run through below lists to check if you have gone through these steps.

### PR Sanitization
Based on the code change, check if these steps are followed wherever relevant

#### Checks before requesting a code review
- [ ] PR title accurately summarised the change in this PR
- [ ] PR title or PR description includes ticket number `JIRA-1234` or `NO-JIRA`
- [ ] PR description properly explains what the change is and why it is needed
- [ ] If it needs any update in documentation like in confluence or in repository, are they updated ?
- [ ] Does it mention what type of change it is: Bug fix, feature implementation, breaking changes, decoration, configuration, version change, refactoring etc.?
- [ ] If relevant, proper testing is added: Unit tests added/updated, Integration tests added/updated, Manual testing steps (provide steps in description)
- [ ] Added any extra steps or breaking changes important for deployment

## Reviewer Checklist
- [ ] Code changes are clear and follow project conventions
- [ ] Changes include appropriate tests
- [ ] Documentation is updated
- [ ] Backwards compatibility is maintained (or breaking changes are documented)
- [ ] Performance impact has been considered

