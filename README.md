# arbiter-a2-oidc-probe

A throwaway probe for A2 · ARB-440 · PLAN-291 (Q1): it records the claims GitHub puts in an Actions OIDC token for a
`pull_request_target` job that is not inside a reusable workflow. The token is minted for a probe-only audience,
masked and never printed; only its decoded claims are printed. Archived after the run. product-3 (A2)
