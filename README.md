# ESLint glob pattern issue

I'd like to ignore files that contains `[` and `]` characters but since they
are special characters they need to be ignored. It seems like ESLint can't
ignore `]` for some reason.

This is an example repository for the issue. Use `npm run lint` to check.