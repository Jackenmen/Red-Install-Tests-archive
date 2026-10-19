# Old iterations of Red-Install-Tests

Old iterations of Red install tests setup based on (now defunct) Cirrus CI and GH Actions. The instructions in these had to be manually synced with the repo and largely depended on CI's featureset with no way to run locally.

The project had a couple of old iterations:

- First iteration of the project used GitHub Actions
    - This iteration started being used in May 2020, running until June 2022
    - The code for this iteration is in `z_old_setup/V3/install_instructions`
- Second iteration of the project used Cirrus CI for most jobs and GitHub Actions for Intel-based macOS testing
    - This iteration started being used in June 2022 and ran until Cirrus CI closed down in June 2026
    - The code for this iteration is in `dev` and `main`. The branches are mostly equivalent - they only differ in the specific install instructions used since builds on `dev` ran `V3/develop` and build on `main` ran latest stable version from PyPI
    - There's one feature branch for this iteration that was never merged: `single_task_skipping`

The current iteration of the project can be found at:
https://github.com/Cog-Creators/Red-Install-Tests
