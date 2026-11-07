# Template for a new project repository (scifbar/project-<name>)

Private repository, one per project. Copy this file as the README of the new repository and
fill it in. Add the project as a row in `README.md` of this catalogue once the people involved
agree to be listed.

```
# <working name>

For: <organization or person this is built for>
Started: <YYYY-MM-DD>, after <event or meeting>
Owner: <GitHub login>
People with access: <logins>

## What it shows
First page: <the inputs the user gives>
Last page: <the outputs the user gets>
In between: <mocked | real> calculations

## Current round
<what the last correction said, what this version changes>

## Not in this version
<the list of things deliberately left out>
```

Conventions:
- Repository name `project-<name>`, lower case, working name is fine.
- One self-contained `index.html` is the deliverable; a `make check` target must exist.
- No em dashes in any text. No confidential data of the organization in the repository
  unless its owner has agreed in writing.
