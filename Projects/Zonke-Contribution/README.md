# Zonke Website — Database and Backend Contribution

## Problem addressed
The website required a database structure and backend connection that could support data retrieval and frontend integration, alongside stronger protection for authentication and API requests.

## My contribution
Based on the WIL logbook, I:
- Planned the database development approach using MySQL and Node.js.
- Created a prototype SQL database and tested it with MySQL Workbench.
- Installed and configured npm dependencies.
- Connected a Node.js backend to MySQL and configured an Express API.
- Updated database tables and fields in response to frontend data requirements.
- Integrated the API with the frontend.
- Worked on password salting, API rate limiting and Helmet security headers.

## Technologies
MySQL, SQL, MySQL Workbench, Node.js, npm, Express, API integration, password salting, Helmet.

## Result
The logbook records an initial Express API server with working database connectivity, frontend/backend integration changes and backend security configuration improvements.

## Source code and contribution history
- Repository: https://github.com/FredrickKcode/zonke
- Commits filtered by the GitHub author account `Shi-ki-is-gone`: https://github.com/FredrickKcode/zonke/commits?author=Shi-ki-is-gone
- Database-related commit history referenced in the logbook: https://github.com/FredrickKcode/zonke/commits/main/database

Each link below opens the commit on GitHub, including its changed files and source diff:

| Date (UTC) | Commit | Source |
|---|---|---|
| 2026-09-27 | Add single to run on MySQL | [View source diff](https://github.com/FredrickKcode/zonke/commit/11c474257562ca566020efe6c9e17e550ceff2e4) |
| 2026-09-27 | Express API server made, Node.js added to project. Connection made and packages add | [View source diff](https://github.com/FredrickKcode/zonke/commit/2d42554c1cd9185a8c0c941f3b496b760a84ebb6) |
| 2026-10-01 | Added API into frontend, removed combined SQL, added missing database values | [View source diff](https://github.com/FredrickKcode/zonke/commit/a7df0ebfdca9d425e6fafced0c862562096bbb0f) |
| 2026-10-01 | Security update | [View source diff](https://github.com/FredrickKcode/zonke/commit/1f0e177aec30e03f081081edea5027a06d8e8eb7) |
| 2026-10-01 | Database able to update | [View source diff](https://github.com/FredrickKcode/zonke/commit/3268ee4b622f7da8f56da165f3a0f5e9cbdafb20) |
| 2026-10-01 | Made API work for frontend and added missing values | [View source diff](https://github.com/FredrickKcode/zonke/commit/83067567b76be00c22e8903372361336c0bcb5e6) |
| 2026-10-01 | Added documentation and small changes | [View source diff](https://github.com/FredrickKcode/zonke/commit/ccd52bdfc18de0343aafb1a115ff681c0a36c115) |

These are the seven public-repository commits attributed to `Shi-ki-is-gone` that were found while checking the account's public repositories. No matching commits were found in the other public repositories checked. Source remains in the original repository; this portfolio links to the commit diffs rather than duplicating source files.

## Evidence
- [Database development screenshots](../../assets/)
- [Daily logs: 21–29 September](../../Daily-Log/)
