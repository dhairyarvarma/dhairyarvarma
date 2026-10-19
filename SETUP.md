# Publish your profile

Create a **public** GitHub repository named **dhairyarvarma** under your own account. Upload this folder's contents to the root of its `main` branch, including the hidden `.github` directory. The path must be `README.md`, not `github-profile/README.md`.

GitHub displays the root README on your profile when the public repository name matches your username. See [GitHub's profile README guide](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

Open **Actions → Contribution snake → Run workflow** to generate the first snake. After that it refreshes daily. It uses the built-in `GITHUB_TOKEN`; no personal access token is needed. The workflow replaces the `output` branch with the two generated SVGs, so reserve that branch for generated assets. It does not change `main`. Repository or organization policies must permit Actions and writes to `output`.

The snake image will appear after the first successful run. Its generator is [Platane/snk](https://github.com/Platane/snk). Typing text and badges use external image services; the local SVG banner and stack graphic remain available if those services are down.

Suggested profile bio (set in GitHub's Edit profile):

> Building durable backend systems with Go, PostgreSQL, and Redis. Interested in failure recovery, delivery semantics, and observability.

Suggested pin: **fault-tolerant-webhook-dispatcher-public**.

The two featured cards describe one public project and its technical write-up. No self-rated skills, unverified performance numbers, education, employer, or private repository details are included. Review the first-person wording before publishing. Your existing avatar and account settings are untouched.
