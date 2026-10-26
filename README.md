# SchoolEveryWhere Automation information pages

This folder contains the standalone static information pages for the personal SchoolEveryWhere Automation project. It is only the public information shell used for OAuth branding. The importer itself remains local and private.

## Free hosting after approval

The proposed host is GitHub Pages on GitHub Free, using the branch-based publishing option described in [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages). The proposed separate public repository is `school-classroom-info`. Publish only the contents of this `public-info/` folder there, after the operator reviews and approves the concrete pages. Do not publish the main application repository. Keep the Pages source on the chosen branch and folder; the `.nojekyll` file is included for static delivery. Relative page and stylesheet links are designed to work under a project subpath.

No custom domain purchase, paid fallback, trial, or billing change is part of this setup. Availability and pricing may change; the operator must make any hosting change explicitly, and no automatic charge-enabling fallback is intended.

A free-hosted website does not by itself establish Google’s acceptance of the host or complete an OAuth publishing configuration. The current Google Console has External/Testing status, Publish app disabled, and empty homepage, privacy, and terms fields. The personal-use verification exception is distinct from app publishing status. Review the current Console and Google requirements after approval; do not assume either outcome.

The pages contain no JavaScript, forms, analytics, external fonts, or tracking scripts. GitHub may process ordinary access metadata under its [general privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
