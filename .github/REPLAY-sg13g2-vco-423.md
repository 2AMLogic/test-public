# Replay of the sg13g2-vco friction-upstream drift reporter (2AMLogic/sg13g2-vco#423)

Throwaway setup for verifying the scheduled repair-issue reporter merged in
2AMLogic/sg13g2-vco#424. It carries that repository's workflow and scripts
unchanged, plus a copy of its friction ledger in which entries 5853 and 5867
are set back to `open` (both are closed upstream). The daily comparison at
04:17 UTC therefore exits 1, and `report-drift` opens or refreshes one issue
titled `ci: friction-upstream ledger drift repair` in this repository.

Remove `.github/workflows/friction-upstream.yml` and the rest of this setup
once the two attempts are recorded on the owning issue.
