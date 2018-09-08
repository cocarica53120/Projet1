# Projet1

Modif 2018/09/08


Modif
Modif on master by cocarica35410 (good)
Modif on firstBranch by cocorico35410

step 1 :
  git fetch origin
  git checkout -b master origin/master
  git merge firstBranch
  
  Resolving conflict is keeping modifs from both (master & firstBranch)

step 2 :
  git checkout firstBranch
  git merge --no-ff master
  git push origin firstBranch


Another Modif in firstBranch (Test in local on multiple branches).
Test modif in local on multiple branches. Here master.

Resolving conflict on GitHub. keep both modif (in the order given by GitHub).
