# Governance

This document describes the current governance state of the verify-anchoring
reference verifier and the Anchoring Specification it implements.

## Current state

The reference verifier (`verify-anchoring.org`) and the Anchoring Specification
(`anchoring-spec.org`) are currently maintained by the Umarise team under the
AnchoringTrust namespace.

This is a single-maintainer project. There is no foundation, consortium, or
multi-stakeholder governance body. The "AnchoringTrust" GitHub organisation is
a publishing namespace, not a legal entity.

## What is and is not claimed

**The verifier is technically independent.** It makes no API calls to Umarise,
anchoring.app, or any other service. All cryptographic libraries are bundled.
Verification works entirely client-side and against the public Bitcoin network
via OpenTimestamps. The verifier continues to function if Umarise ceases to
exist.

**The verifier is not institutionally governed.** There is no steering committee,
no voting policy, no external co-maintainers at this time. Decisions about the
specification and the reference implementation are made by the Umarise team.

These two properties are independent. Technical independence does not require
institutional governance, and institutional governance does not by itself
guarantee technical independence.

## License and forking

The reference verifier is released into the public domain under the Unlicense.
Any party may fork, mirror, modify, or self-host this code without permission
or attribution. This is the strongest form of independence the project can
offer at its current stage: anyone who wishes to verify anchoring proofs may
do so using their own copy of the verifier, indefinitely.

## Future governance

External co-maintainers are welcome. Multi-stakeholder governance, a foundation,
or a standards-track route may be considered if and when adoption warrants it.
At present, none of these structures exist for this project, and no such claim
is made.

## Contact

Security and governance questions: security@umarise.com

## Disclosure

This document exists because clarity about governance is itself a form of
trust. Overstating governance independence damages credibility more than
honest single-maintainer disclosure does.
