# learn.github-actions

The project to learn GitHub Actions.

## Workflows

1. [blank.yml](.github/workflows/blank.yml)

    This is the first workflow which created by GitHub Actions automatically.

2. [echo-messages.yml](.github/workflows/echo-messages.yml)

    Echos some messages on issue operations.
    This also confirms to be able to use Japanese.
    
3. [schedule-for-midnight-in-jst.yml](.github/workflows/schedule-for-midnight-in-jst.yml)

    Checks scheduling function with `cron` syntax of which timezone must be UTC.
    
4. [filter-branches-tags-paths.yaml](.github/workflows/filter-branches-tags-paths.yaml)

    Filter conditions for pushing and `filtered_branch` branch.
