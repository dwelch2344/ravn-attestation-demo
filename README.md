# ravn-attestation-demo

Throwaway harness for Ravn's OIDC echo endpoint. Deliberately **not** in the
RavnSecurity org: security-004 says profile runs never happen in Ravn's own
repos, and a personal repo is the only way to see a genuine cross-owner
`repository_owner_id`.

`gh workflow run "oidc echo"` — then watch `logs/reputation/output.txt` in
ravn-developer.
