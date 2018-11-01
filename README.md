# H3xGitStandards

## Files to include:
.gitignore
libraries-list
readme

## Branching:
### Master branch [stable version]
- Branch from:
    - Pre-release
- Merge with: 
    - Do not merge
  ### Hotfix [fix production side bugs -> delete after merge]
- Branch from:
    - Master
- Merge with: 
    - Master
 ### Pre-release branch [test stability]
- Branch from:
    - Development
- Merge with: 
    - Master or Pre-release(if not stable)
 ### Development branch [working in progress]
- Branch from:
    - Development
- Merge with: 
    - Pre-release(if you consider stable) or Development(if working in progress)

### Testing branch [testing very breakable features -> delete after merge]
- Branch from:
    - Development
- Merge with: 
    - Development(if a feature is working) or Testing(if working in progress)
