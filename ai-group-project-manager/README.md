# AI Group Project Manager (Prototype)
Run: `npm install && npm run dev`

**Real:** React UI, shared state, browser localStorage persistence, human-approval rules (enforced in code).
**Simulated:** the AI Assistant, allocation proposals and risk alerts are local rule-based logic following the `ai-group-project-manager` Skill. No Claude API or backend is connected.
**Demo Data:** all members, the assignment, rubric and evidence are fictional.
**Next step to make AI real:** replace `ask()` and `propose()` in `src/App.jsx` with a backend call that sends the Skill and its six reference files as the system prompt (never call the API from the browser with a key).
