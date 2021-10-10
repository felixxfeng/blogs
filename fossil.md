## Fossil Syntax

#### General Work Flow

```markdown
fossil init REPOSITORY-DIR/new-repository
fossil open REPOSITORY-DIR/new-repository
fossil changes/diff/info/status/ls
fossil timeline
fossil add/rm files-or-directories
fossil commit -m "commit message"
fossil ui
```

#### Branch and Merge
```markdown
fossil commit –branch "brach-name"
fossil update trunk
fossil merge featureX
fossil commit
```

#### Share changes (autosync is off)
```markdown
fossil push URL
fossil pull URL
fossil sync URL
fossil update VERSION
```
See more details at Fossil [Quick Start](https://fossil-scm.org/home/doc/trunk/www/quickstart.wiki).
