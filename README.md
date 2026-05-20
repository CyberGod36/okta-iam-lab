okta-iam-lab/
├── README.md                          # This file
├── docs/
│   ├── JML-WORKFLOW.md               # User lifecycle detailed guide
│   ├── RBAC-WORKFLOW.md              # Role-based access control guide
│   ├── ACCESS-REQUESTS.md            # Approval workflow guide
│   ├── MFA-SECURITY.md               # MFA & conditional access guide
│   ├── SYSTEM-LOGS.md                # Log analysis & audit guide
│   └── CERTIFICATION-PREP.md         # Okta certification alignment
├── scenarios/
│   ├── 01-newHire-onboarding.md
│   ├── 02-lateralMove-transition.md
│   ├── 03-offboarding-deprovisioning.md
│   ├── 04-financeRBAC-SoD.md
│   ├── 05-dynamicGroupRules.md
│   ├── 06-accessRequest-approval.md
│   ├── 07-multiLevelApproval.md
│   ├── 08-mfaPolicy-config.md
│   └── 09-locationBasedAccess.md
├── screenshots/
│   ├── jml/
│   │   ├── 01-user-creation.png
│   │   ├── 02-group-assignment.png
│   │   ├── 03-app-provisioning.png
│   │   └── 04-system-log-query.png
│   ├── rbac/
│   │   ├── 01-dynamic-group-rule.png
│   │   ├── 02-sod-conflict-check.png
│   │   └── 03-role-permissions-matrix.png
│   ├── access-requests/
│   │   ├── 01-access-request-policy.png
│   │   ├── 02-approval-workflow.png
│   │   └── 03-request-history.png
│   ├── mfa/
│   │   ├── 01-mfa-policy-config.png
│   │   ├── 02-conditional-access-rule.png
│   │   └── 03-location-zone-setup.png
│   └── logs/
│       ├── 01-system-log-interface.png
│       ├── 02-user-creation-events.png
│       ├── 03-provisioning-chain.png
│       └── 04-audit-report.png
├── logs/
│   ├── audit-trail-sample.json        # Sample System Log exports
│   ├── provisioning-events.log
│   └── access-request-trail.log
└── tools/
    └── log-query-reference.md         # System Log query syntax & examples
