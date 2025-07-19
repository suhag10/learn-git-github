# Essential SVN Commands

### Update package list
`sudo apt-get update`


### Install Subversion (SVN)
`sudo apt-get install subversion`


### Confirm installation
`svn --version`

<br><br>

`sudo svnadmin create svnrepo`


### Submit repository commands
```bash
svn co https://plugins.svn.wordpress.org/<repo>
svn auth
cd trunk
svn add foldername/filename
svn add tags/1.0.0/
svn commit -m "Initial commit"
```


- **Available subcommands:**
   - add
   - auth
   - blame (praise, annotate, ann)
   - cat
   - changelist (cl)
   - checkout (co)
   - cleanup
   - commit (ci)
   - copy (cp)
   - delete (del, remove, rm)
   - diff (di)
   - export
   - help (?, h)
   - import
   - info
   - list (ls)
   - lock
   - log
   - merge
   - mergeinfo
   - mkdir
   - move (mv, rename, ren)
   - patch
   - propdel (pdel, pd)
   - propedit (pedit, pe)
   - propget (pget, pg)
   - proplist (plist, pl)
   - propset (pset, ps)
   - relocate
   - resolve
   - resolved
   - revert
   - status (stat, st)
   - switch (sw)
   - unlock
   - update (up)
   - upgrade
