### Git Advanced Exercise
## Part 1

```bash
cd theGym_Git_Advanced_Exercise_Solutions/
75  clear
76  ls
77  ls -la
78  clear
79  git add test4.md && git commit --amend --no-edit
80  git rebase -i HEAD~2
81  git --amend
82  git commit --amend
83  git rebase --continue
84  git rebase -i HEAD~3
85*
86  git rebase -i HEAD~2
87  git rebase -i HEAD~3
88  git rebase -i 180b64336c06d9bdd57035da3cd8c217fcdf78ca
89  git rebase -i 180b64336c06d9bdd57035da3cd8c217fcdf78ca
90  git rebase --abort
91  git log
92  git rebase -i HEAD~2
93  git rebase -i --root
94  git rebase --abort
95  git rebase -i --root
96  git log
97  git status
98  git reset HEAD~
99  git commit -m "chore: Create third file"
100  git add test3.md && git commit -m "chore: Create third file"
101  git add test4.md && git commit -m "chore: Create fourth  file"
102  git rebase HEAD~2
103  git rebase -i HEAD~2
104  git rebase --continue
105  touch unwanted.txt
106  git add unwanted.txt
107  git commit -m "chore: Unwanted commit"
108  git rebase -i HEAD~1
109   git log --oneline
110  git rebase -i
111  git rebase -i root
112  git rebase -i --root
113  git log --oneline
114  git show
115  git checkout -b ft/branch
116  git status
117  touch test5.md
118  git add test5.md
119  git commit -m "feat: Implemented test 5"
120  git log --oneline
121  git checkout main
122  git show 8bee2e7
123  git cherry-pick --no-commit 8bee2e7
124  git status
125  git commit -m "chore: Implemented test 5"
126  git remote -v
127  git log --graph
128  git reflog
129  touch README.md
130  history
```

## Part 2

```bash
140  git checkout -b ft/new-feature
141  touch feature.txt
142  git add feature.txt
143  git commit -m "feat: Implemented core functionality for new feature"
144  git checkout  main
145  touch readme.txt
146  git add readme.txt
147  git commit -m "chore: Updated projects readme"
148  clear
149  git branch -r
150  git merge ft/new-feature
151  git log --oneline
152  git reset HEAD~
153  git commit -m "feat: Merge ft/new-feature to main"
154  git add feature.txt && git commit -m "feat: Merge ft/new-feature to main"
155  clear
156  git remove --help
157  git branch -d ft/new-feature
158  git merge ft/new-feature
159  git branch -d ft/new-feature
160  clear
161  git log --oneline
162  git checkout -b ft/new-branch HEAD~2
163  git switch main
164  git log --oneline
165  git merge ft/new-branch
166  git rebase ft/new-branch
167  git log --oneline
168  git branch -m ft/new-branch ft/improved-branch-name
169  git branch
170  git checkout 0c432c9
172  git log --oneline
173  git switch main
174  git log --oneline
```