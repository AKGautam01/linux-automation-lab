### Exercise 2: Safe Copy Operation
- **Command:** `cp -iv note1.txt ../artifacts/`
- **Why:** To practice copying files with interactive and verbose flags (avoids overwrites, shows actions).
- **Verification:** Used `ls` to confirm file exists in artifacts, and `diff` to confirm identical content.
- **Outcome:** note1.txt copied into artifacts/ with confirmation.

### Exercise 3: Safe Move Operation
- **Command:** `mv -iv report.md ../artifacts/`
- **Why:** To practice moving files with interactive and verbose flags (prevents accidental overwrite, shows actions).
- **Verification:** Used `ls` to confirm report.md is present in artifacts and no longer in tmp/.
- **Outcome:** report.md successfully moved from tmp/ to artifacts/.
