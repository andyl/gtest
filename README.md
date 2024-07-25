# gtest

## TODO 

- [x] Conventional Commits 
- [x] Updated Git Workflow 
- [ ] Autogenerate changelog 
- [ ] Auto-gen version tag 
- [ ] Auto-update changelog 

## Resources 

- https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index 

## git_ops 

https://github.com/zachdaniel/git_ops 

## Workflow 

| BRANCH  | UPDATE METHOD | Compile/Test? | ConvCommit? | Release Bump? | Deploy? | Core Activity   |
|---------|---------------|---------------|-------------|---------------|---------|-----------------|
| dev     | Push          | yes           | no          | no            | no      | Write Code      |
| master  | PR            | yes           | yes         | no            | no      | Rewrite Commits |
| release | PR            | yes           | yes         | yes           | yes     | Bump Version    |

