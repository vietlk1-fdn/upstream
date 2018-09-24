git clone https://github.com/vietlk1-fdn/upstream.git

cd upstream

git remote add upstream https://github.com/huutoannht/upstream.git

git fetch upstream

git checkout --track origin/master-bug-fixes-18.39

git pull upstream master-bug-fixes-18.39

git checkout -b FPTD-3

git rebase master-bug-fixes-18.39

git log --oneline