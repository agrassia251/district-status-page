# Specification

## Summary
**Goal:** Redeploy the stopped backend Motoko canister so it returns to a running state and all calls are accepted without IC0508/Reject code 5 errors.

**Planned changes:**
- Redeploy the backend Motoko canister (tgggy-siaaa-aaaag-auegq-cai) to transition it from stopped to running state
- Ensure query calls (e.g., `getAllIncidents`) and update calls (`createIncident`, `addUpdate`, `changeStatus`, `deleteIncident`) are accepted without rejection

**User-visible outcome:** The Dashboard and Admin Panel load incidents successfully, with no "canister is stopped" errors appearing.
