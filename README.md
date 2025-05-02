# Essential Git Commands Cheat Sheet


### Creating a New Repository
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git init`                                                   | - |
| `git add filename.md`                                        | For multiple files, use `git add-all` &bull; `--all` &bull; `-A` &bull; `.` |
| `git commit -m "Initial commit"`                             | - |
| `git branch -M <branch-name>`                                | - |
| `git remote add origin https://github.com/<user>/<repo>.git` | - |
| `git push -u origin <branch-name>`                           | - |

### Working with Local Changes
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git status`                                                 | - |
| `git add --all`                                              | - |
| `git add -p <file>`                                          | - |
| `git commit -m "Your message here"`                          | - |

### Viewing History
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git log`                                                    | - |
| `git log-p <file>`                                           | - |
| `git blame <file>`                                           | - |

### Branching and Merging
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git branch -av`                                             | - |
| `git branch <new-branch>`                                    | - |
| `git checkout <branch>`                                      | - |
| `git merge <branch>`                                         | - |

### Undoing Changes
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git reset --hard HEAD`                                      | - |
| `git checkout HEAD <file>`                                   | - |
| `git revert <commitId>`                                      | - |

<!-- ### Additional Essential Commands -->

### Cloning a Repository
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git clone https://github.com/<user>/<repo>.git`             | - |

### Pulling Changes from Remote
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git pull origin main`                                       | - |

### Pushing Changes to Remote
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git push origin <branch>`                                   | - |

### Stashing Changes
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git stash`                                                  | Stash changes          |
| `git stash list`                                             | List all stashes       |
| `git stash apply`                                            | Apply the latest stash |
| `git stash drop`                                             | Drop the latest stash  |

### Tagging
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git tag <tag-name>`                                         | Create a new tag       |
| `git tag`                                                    | List all tags          |
| `git push origin <tag-name>`                                 | Push tag to remote     |

### Viewing Differences
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git diff`                                                   | Show changes between working directory and index |
| `git diff HEAD`                                              | Show changes between working directory and last commit |

### Deleting Branches
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git branch -d <branch>`                                     | Delete a local branch (only if merged) |
| `git branch -D <branch>`                                     | Force delete a local branch (even if unmerged) |

### Working with Remotes
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `git remote -v`                                              | List all remote repositories |
| `git remote add <name> <url>`                                | Add a new remote repository |
| `git remote remove <name>`                                   | Remove a remote repository |


### Quick push github
```bash
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main 
```

### PHP Composer init
| Command                                                      | Description            |
| ------------------------------------------------------------ | ---------------------- |
| `composer init`                                              | - |
| `git config --global user.name {your-name}`                  | - |
| `git config --global user.email {your-email}`                | - |
| `git config --global package.name {your-package-name}`       | - |
| `git config --global package.type {your-package-type}`       | - |
| `git config --global license.name {your-package-license}`    | - |

<!--
# Update List

1. Created on Nov 6, 2022 
2. Updated on Sep 24, 2023
2. Updated on May 2, 2025

-->
