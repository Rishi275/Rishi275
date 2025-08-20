# how to make brance and then add commits to main branch

## pull the main brnach code

- use

`git clone repo`

` cd folder`

`git checkout main or`

`git switch main`

#
- create new branch from terminal only

```

git -b new-b

```

or

```

git -b feature/new-b

```

##

- go inside this branch

```

git checkout new-b

```

or

```

git checkout feature/new-b
git pull origin main

```

--now you can make any changes to the repo--

-- after changes you can directly commit or push to github then thre you can make mergings--

-- if want to do merge from terminal--
then just

```

git add .

git commit -m "added new code"

```

#

- now come back to main branch

```

git checkout main

```

-- then--
just check updated code by branch = new-b if it ok

-- merge that new-b branch code to main
-- by clicking (ctrl+shif+G) open editor and git insights for checking both side code

--now merge-- if ok--

```

git merge branch new-b
git push -f origin main

```
----------------------end-----------------------