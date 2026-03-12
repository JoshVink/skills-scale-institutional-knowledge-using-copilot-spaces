# Risk Management Checklist

Use this checklist during project planning and execution to identify, log, assess, and escalate risks systematically. The Risk Manager owns this process; the Project Manager is accountable for ensuring it is followed.

---

## 1. Identify Risks

- [ ] Conduct a risk identification workshop with the core team at project kickoff
- [ ] Interview stakeholders to surface external or dependency-related risks
- [ ] Review previous project retrospectives and known issue logs for recurring risk patterns
- [ ] Analyze project assumptions and constraints for potential failure points
- [ ] Consult the Risk Manager, Team Leads, and Developers for technical and operational risks
- [ ] Review third-party integrations and dependencies for supply-chain or availability risks
- [ ] Consider regulatory, compliance, or security risks relevant to the project scope

---

## 2. Record Risks in the Risk Register

Each risk entry must include the following fields:

| Field | Description |
|---|---|
| **ID** | Unique identifier (e.g., RISK-001) |
| **Title** | Short, descriptive name for the risk |
| **Description** | Clear explanation of what the risk is and what could trigger it |
| **Likelihood** | Probability of occurrence: Low / Medium / High |
| **Impact** | Effect on project if risk occurs: Low / Medium / High |
| **Priority** | Derived from Likelihood × Impact (Low / Medium / High / Critical) |
| **Owner** | Person responsible for monitoring and mitigating this risk |
| **Mitigation** | Planned actions to reduce the likelihood or impact |
| **Contingency** | Actions to take if the risk materializes |
| **Status** | Current state: Open / In Mitigation / Escalated / Closed |

- [ ] All identified risks are logged in the risk register
- [ ] Each risk has an assigned owner
- [ ] Each risk has a documented mitigation and contingency plan
- [ ] Risk register is stored in a shared, version-controlled location

---

## 3. Assess and Prioritize Risks

- [ ] Rate each risk for **Likelihood** (Low / Medium / High)
- [ ] Rate each risk for **Impact** (Low / Medium / High)
- [ ] Calculate or assign a **Priority** level based on Likelihood × Impact
- [ ] Focus mitigation planning on High and Critical priority risks first
- [ ] Review the risk landscape with the Project Manager and relevant Team Leads

---

## 4. Escalation Thresholds and Path

Escalate a risk immediately when any of the following thresholds are met:

| Threshold | Action |
|---|---|
| Risk Priority = **Critical** | Escalate to Project Manager immediately |
| Risk has been **In Mitigation** > 2 weeks with no progress | Escalate to Project Manager |
| Risk may affect **external stakeholders or commitments** | Notify Stakeholder Liaison |
| Risk threatens **release date or project scope** | Escalate to Stakeholder Liaison and Executive Sponsor |
| Risk materializes and becomes an **active issue** | Trigger incident/issue management process |

**Escalation Path:**
```
Risk Manager → Project Manager → Stakeholder Liaison → Executive Sponsor
```

- [ ] Escalation path is documented and communicated to the team
- [ ] All escalated risks have a named escalation contact
- [ ] Escalated risks are tracked until resolution

---

## 5. Monitor and Review

- [ ] Risk register is reviewed at least **bi-weekly** during the project delivery sync
- [ ] Each risk owner provides a status update at every review
- [ ] New risks identified during execution are added to the register immediately
- [ ] Closed or mitigated risks are marked with a resolution date and summary
- [ ] Risk trends are discussed during sprint retrospectives
- [ ] Updated risk register is shared with the Project Manager and Stakeholder Liaison after each review cycle

---

## 6. Pre-Release Risk Review

- [ ] All open risks have been reviewed and accepted, mitigated, or escalated
- [ ] No Critical risks remain unresolved
- [ ] Risk Manager confirms release readiness from a risk perspective
- [ ] Post-release risk monitoring plan is in place for residual risks
