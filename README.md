# SupportDesk E2E Testing

Playwright end-to-end framework for a customer-support ticketing application.

## Tech stack
TypeScript · Playwright · Retry handling · HTML reporting · GitHub Actions

## Test coverage
- Ticket creation and assignment
- Priority and SLA validation
- Agent comments and workflow transitions
- Ticket resolution and closure

## Run
```bash
npm ci
npx playwright install
npm test
```