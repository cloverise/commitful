commitful
=========
commitful a simple script that help you review git status of all your local working directories.

- detect automatically all git repo location
- build 1 line report per repo with:
 - status: UNCOMMITED, UNTRACKED, AHEAD,CLEAN
 - number of files impacted
 - path to repo

Usage
=====
```bash
$ cd <my big folder containing all git repos>
$ curl https://raw.githubusercontent.com/cloverise/commitful/master/commitful > commitful
$ chmod +x commitful
$ commitful
```

Roadmap
=======
- 0.1 polish layout and code
- 0.2 report directories outside of git subtrees
- 0.3 slow features: e.g. git fetch

Contribute
==========
I am a developer, I want to help
--------------------------------
Please check our github issue tracker for feature requests, pick any and don't forget to commit !
I am a developer, I need help
-----------------------------
Please check our github issue tracker for feature requests, add more !
