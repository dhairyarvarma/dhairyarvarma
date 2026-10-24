# Profile source

This folder backs the public [dhairyarvarma profile](https://github.com/dhairyarvarma). Its README and SVG assets live on the repository's `main` branch.

GitHub displays the root README on your profile when the public repository name matches your username. See [GitHub's profile README guide](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

Open **Actions → Contribution snake → Run workflow** to generate the first snake. After that it refreshes daily. It uses the built-in `GITHUB_TOKEN`; no personal access token is needed. The workflow replaces the `output` branch with the two generated SVGs, so reserve that branch for generated assets. It does not change `main`. Repository or organization policies must permit Actions and writes to `output`.

The snake generator is [Platane/snk](https://github.com/Platane/snk). Its contribution levels use GitHub's green palette, with a purple snake accent. The banner is an SVG scene built from square pixels: Batman idles on the left, Spider-Man swings on the right, and the purple title types one letter at a time. Tool icons use an external image service.

Suggested profile bio (set in GitHub's Edit profile):

> Full Stack Developer building thoughtful interfaces and reliable systems. Currently building RepoScope.

Suggested pin: **fault-tolerant-webhook-dispatcher-public**.

The profile features the current RepoScope project at a high level and the public webhook engine with links to its documentation. RepoScope is private, so the profile does not link to its source or expose implementation evidence beyond its high-level purpose. Review public wording before future changes to that project. Your existing avatar and account settings are untouched.

