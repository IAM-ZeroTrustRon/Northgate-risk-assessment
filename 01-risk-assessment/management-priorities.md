# Five Management Priorities

**Northgate Behavioral Health Clinic — fictional assessment**
Prepared by Ron Richardson | October 6, 2026
**Decision status:** Proposed; no controls implemented or independently tested.

Northgate's twelve-risk register is the detailed assessment. This view groups those risks into five management decisions without deleting, rescoring or replacing them. Group ratings show the highest existing score in the group; they are not additional risks, averages or estimates of combined loss.

## Decisions and accountability

| Priority | Management decision / business exposure | Register links and highest score | Existing safeguards described in the scenario | Recommended treatment | Proposed accountable owner | Proposed target from approval |
|---|---|---|---|---|---|---|
| P1 — Protect staff identities | A stolen or shared login could expose patient information and prevent attribution of access | R-01: 20 Very High; R-03: 16 High; R-08/R-09: 12 High | Login and EHR activity records exist in the scenario; MFA, named-account coverage, leaver controls and review effectiveness are unverified | Mitigate: enforce MFA, named identities, role-based access, HR-triggered account removal and documented EHR access review | Practice administrator, supported by IT and HR | MFA and account inventory within 30 days; named-account/lifecycle and review evidence within 90 days |
| P1 — Establish accountable risk governance | Outdated assessment and unresolved legal/vendor scope could leave patient-data handling decisions unsupported | R-02: 20 Very High; R-06: 15 High; R-12: 9 Moderate | Older assessment and some agreements are described; completeness and applicability are unresolved | Mitigate: validate assessment scope, approve a treatment plan, resolve Part 2 applicability, inventory vendors and review applicable agreements | Practice administrator, supported by clinical director and legal/privacy reviewer | Scope, ownership and applicability decision within 30 days; vendor gaps tracked to approved dates |
| P2 — Protect clinical information in daily work | Endpoint loss, visible screens and misdirected disclosures could expose sensitive information | R-04: 15 High; R-07: 12 High; R-11: 9 Moderate | Existing devices and release workflow are described; encryption, privacy safeguards and recipient checks are insufficient or unverified | Mitigate: encrypt approved endpoints/media, improve front-desk privacy, require verified recipients and track authorized releases | Privacy officer or designated privacy lead, supported by IT and office manager | Immediate workflow changes within 30 days; endpoint evidence within 90 days; release controls within 180 days |
| P2 — Separate clinical systems from other devices | A compromised guest or facilities device could create a route into clinical operations | R-05: 15 High | A network exists; separation and approved vendor remote paths are not established | Mitigate: inventory paths, isolate guest access, segment facilities technology, and restrict remote administration | IT service owner | Design and dependencies within 30 days; authorized implementation and validation within 180 days |
| P2 — Prove service recovery | Backups may not restore scheduling and documentation when clinical operations depend on them | R-10: 12 High | Nightly backups report success in the scenario; no restore evidence | Mitigate: agree clinical recovery requirements, test isolated restoration, and exercise manual continuity/reconciliation | Practice administrator, supported by IT, backup vendor and clinical lead | Agree requirements within 30 days; restore test and clinical sign-off within 90 days |

T0 is approval of this proposed plan, not the document date. Targets are planning assumptions, not commitments accepted by real staff. P1 means sponsor attention first; P2 means sequenced treatment with dependencies. A group containing a Moderate risk still retains that risk's original rating.

## Evidence required before reporting improvement

| Priority | Evidence to request | Closure / reassessment decision | Current residual position |
|---|---|---|---|
| Staff identities | MFA enforcement export and negative login test; approved access inventory; sample departure/role-change ticket; dated EHR review with exceptions resolved | Reviewer confirms approved access works, disallowed access fails, changes occur within the approved SLA and review actions are evidenced | Unassessed; existing projected scores are conditional targets only |
| Risk governance | Current data-flow/inventory scope; approved risk analysis and owner-assigned treatment plan; documented Part 2 determination and resulting actions; vendor/BAA register | Signatures alone do not close the risk: confirm scope is accurate and required management activities and applicable safeguards operate | Unassessed |
| Daily information handling | Encryption/key-recovery status; privacy walkthrough; synthetic recipient-verification test; release log and authorization review | Validate safeguards during normal clinical work; assess remaining disclosure pathways and exceptions | Unassessed |
| Network separation | Approved zones/flows; rules and owners; authorized denial tests from guest/facilities networks; legitimate clinical connectivity checks | Confirm unauthorized routes fail and clinical/vendor workflows retain only necessary access | Unassessed |
| Recovery | Agreed recovery objectives; restore logs; data-integrity and usability checks; timed clinical tabletop and reconciliation results | Clinical and IT owners accept measured recovery against agreed objectives; failed tests remain open | Unassessed |

## Sponsor approval record

**Requested decision:** approve the scope, proposed accountable functions, treatment sequence and evidence requirements; validate costs and actual implementation effort before funding authorization. The roadmap's $4,000–7,000 figure is a scenario estimate, not a quote or demonstrated budget sufficiency.

Record an accountable person's name, approval date, actual due date, evidence location and review decision for each approved action. Exceptions require a rationale, compensating safeguards, expiry and risk-owner acceptance. Reassess after implementation, significant service changes and incidents. No decline in risk score is credited solely because a policy was drafted, a document signed or a ticket opened.

The five scenarios in the wider portfolio plan are illustrative. This summary uses the existing Northgate evidence assumptions: it does not invent confirmed endpoint patch gaps, unsanctioned-cloud use or unauthorized physical entry.

[Detailed twelve-risk register](risk-register.md) · [Treatment roadmap](../05-remediation/remediation-roadmap.md) · [Assessment basis](assessment-basis.md)
