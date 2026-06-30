# Automation Workflow Design

Designed by Chrome Labs — the workflows that run the business with minimal staff:
• Lead capture → enrich → CRM record → owner alert
• Onboarding drip (welcome → activation nudges → first-value check-in)
• Support triage + overnight auto-replies, escalate edge cases
• Billing lifecycle: trial → convert → dunning on failed payment
• Weekly KPI digest auto-posted to the dashboard
Tooling: webhooks between the app, CRM, ESP and analytics; a queue for retries.
