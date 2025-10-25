# Battery-Testing-Software-NHR
This repo holds the high-level and stable control code for the NHR systems. The ITECH system code can be found [here](https://github.com/ARTS-Laboratory/Battery-Testing-Software-ITECH), and the original and deprecated codebase can be found [here]([https://github.com/ARTS-Laboratory/Battery-Testing-Software-ITECH](https://github.com/ARTS-Laboratory/Battery-Testing-Software)).

## How to Use This Repo (Common Guidance)
These repositories provide building blocks (drivers, device interfaces, and example control apps) for running battery cyclers. They’re meant to be built upon for your lab/project setup.

### Quick start
1. Download this repo (do not generally clone it) to your local machine.
2. Open the example project(s) in `Projects/` and run a demo to verify connectivity.
3. Copy any example VIs and library components you need into your own project/workspace.
4. If the system you are working on is more complex, it may make sense to create a new repository for that system that borrows code from this high-level repository. 

### Recommended workflow
- Copy, then customize: Treat this repo as a reference and source library. Copy code into your local project, then adapt it to your rig.
- Keep upstream clean: When the team agrees on improvements that should benefit everyone, we contribute those changes here (upstream) so they become the new common baseline.

### When to update upstream (this repo)
- Bug fixes that apply broadly (e.g., robust error handling, reconnection strategies).
- New, generally useful features (e.g., improved logging, safer shutdown sequences).
- Documentation and examples that make onboarding faster.



### Staying in sync
- Periodically check this repo’s Releases and CHANGELOG for updates.
- If you need changes from upstream, pull the latest and selectively merge/copy into your local project.
