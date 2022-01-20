# Facilitate widespread Gall agent documentation

[Back](/../../#Q1)

**Owner:** `~tinnus-napbus`

Gall agents need to be documented, but it's not feasible to centralize all agent
documentation, much of which is produced by third parties, on the urbit.org
website. 

## Outcomes

- At least six agents have reference documentation.
- At least three non-Tlon apps are documented in the %docs app.
- Tlon has documented at least one of their own agents using the %docs app.

## Problems

- Most agents are currently undocumented.
- %docs app is not widely used.
- When it exists at all, agent documentation often lags the code over time.

## Plan

- Use a new Urbit application, the %docs app, to enable authors of agents to
  distribute documentation for their agents with their code.
- Document the following agents in the %docs app:
  - %hark-store
  - %settings-store
  - %group-store
  - %metadata-store
  - %contact-store
  - %invite-store
- Using the above as a reference, help other developers document their apps.
- Clean up the %docs app code and make some minor improvements to the
  front-end, such as footers for navigating to the previous/next page.
