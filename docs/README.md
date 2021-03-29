The following lists Azure DevOps similarities and differences:

- Improved source browser
- Kanban board with optional automation (moving tasks), integrated with issues or PRs
- No backlog, no scrum board, etc.
- No concept of epics/stories/sprints, etc.
- Can assign issues, not tasks.
- Git Powered Wikis and Websites
- YML tasks/actions (dotnet core, az cli, powershell, etc.)
- Self-hosted YML task runners are supported 
- Possible to setup release builds
- Built packages can be used as artifacts
- Build code for iOS and use automatic testing with the provided iOS emulator
- Provides warnings for dependencies where security vulnerabilities have been identified
- Run custom handlers (via webhooks) on events, e.g. new issue, new PR, discussion post, etc.
- Can lock main brainch (enforce PRs, enforce CI before PR merge)
- Fork or duplicate repositories (if you want to make someone else's repo private, use duplicate)
- Lacks visual pipeline builder, no variable groups
- Not easy to integrate with Azure keyvault or Azure subscription for actions
- Builds seem much faster than Azure DevOps, small repos can CI in seconds
- Costs approx. $5/developer

Learn to build actions: https://github-actions-hero.now.sh/

Build status

[![.NET](https://github.com/Pixeldyne-Systems/AZ-204-DevelopingSolutionsforMicrosoftAzure/actions/workflows/dotnet.yml/badge.svg)](https://github.com/Pixeldyne-Systems/AZ-204-DevelopingSolutionsforMicrosoftAzure/actions/workflows/dotnet.yml)

Note: because this project was forked, it's public (to keep forked projects private, duplicate them instead)
