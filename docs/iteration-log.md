# Illustrative iteration log

| Observation in synthetic test | Product hypothesis | Change to try | Regression check |
| --- | --- | --- | --- |
| E02 overstates administrator-only coverage | Generated text drops population qualifiers | Highlight population terms in evidence and require support for `all` claims | E01 should pass; E02 must be rejected |
| E03 has no relevant evidence | A forced answer invites unsupported claims | Allow an explicit `evidence not found` state | E03 should abstain and route to manual completion |
| E04 has two incompatible passages | Selecting one passage hides a conflict | Show both versions and a conflict warning | E04 must remain in manual review |

This is a demonstration of how evaluation can drive product changes. It does not report a deployed experiment.
