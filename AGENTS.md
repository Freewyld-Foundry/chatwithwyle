<!-- proportionate-delivery:start -->
## Minimum delivery policy

**EDIT -> BUILD -> DEPLOY -> AFFECTED LIVE CHECK.**

- This is the standing policy for this repository, its apps, services, scripts and future templates. It replaces older procedural delivery requirements below.
- Forced plans, GO approvals, reviewer handoffs, tracker gates, repeated checks and unrelated waits are not prerequisites. Security, access, financial and data protections remain.
- Existing authorization carries through commit, push, required PR, merge, deployment and live verification. Ask only for missing authority or a consequential decision outside that scope.
- Use one existing delivery owner. No duplicate writers, reviewer relays, routine extra agents, repeated branch extraction or unnecessary machine hops. Preserve business and approved-machine boundaries.
- Default predeployment verification is one build with compilation/type checking where applicable. Reuse the checked artifact for the same target and configuration. Documentation-only repositories have no application deployment step.
- Add only the affected behavior checks. Changes affecting money, authentication, permissions, data integrity or migrations require the relevant invariants and recovery checks. Group these in one focused risk job, never an unrelated full suite. Determine scope from changed code and affected dependencies.
- Remove unrelated suites, whole-account sweeps, proof bundles and procedural approvals from executable release dependencies. Useful extended tests may run separately without holding unrelated releases. Do not hide a full suite inside the build or live check.
- Preserve actor authorization, credential protection, tenant isolation, exact commit/artifact identity, and necessary rollback/data safeguards. Never weaken an assertion, fabricate data or conceal a material defect to obtain a pass.
- Run each necessary check once. Reuse valid results while inputs are unchanged. Repair the exact failure and rerun only invalidated checks. Never repeat a known failing baseline before applying its established fix.
- Cache dependencies and runtime assets. Cancel only superseded runs that no active release needs. Do not duplicate a hosting build in CI when the existing hosting build provides the same verification.
- Ship independent ready changes without waiting for unrelated defects, source refreshes or historical recovery. Preserve the full remaining scope and keep genuine dependencies together.
- Read only what changes the next decision. Batch independent reads, use bounded waits and prefer completion events. Keep one existing task/release record; documentation and tracker updates never hold delivery.
- Verify the deployed revision and affected real behavior. Build success, an uploaded artifact or a created deployment alone does not establish live success. For non-web services, verify the affected installed command or scheduled runtime instead.
- Report what shipped, commit, destination, actual live result and remaining blocker. Measure a slow stage rather than inventing more process. Stop expanding checks after the requested outcome and required safeguards pass.
- Do not add blocking suites, approval stages, evidence documents or repeated verification without explicit authorization to change this policy. Apply this policy to new workflow templates and reconcile contradictory instructions.
- Never use em dashes. Close agent-opened helpers and windows; preserve user-owned sessions.
<!-- proportionate-delivery:end -->
