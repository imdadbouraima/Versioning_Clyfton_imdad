# Réponses — chasse au trésor

<!-- Format imposé, une réponse par ligne :
Q01: <réponse>
commande: <commande(s) utilisée(s)>
-->

Q01: 32
commande: git rev-list --count depart

Q02: Sarah Benali
commande: git blame depart -- src/format.js

Q03: 4459c91
commande: git bisect run node scripts/controle-alertes.js

Q04: sk_live_01de6ba0c9f4d846
commande: git log depart -p -i -G"api[_-]?key"

Q05: 11544ab934db75adbe18115b8c463b52bdb4296a
commande: git log depart --diff-filter=D --name-only --oneline

Q06: 17
commande: git rev-list --count v0.2.0..v1.0.0

Q07: essai-perf
commande: git for-each-ref refs/tags --format='%(refname:short) %(objecttype)'

Q08: experiment/cache-redis
commande: git branch -r --no-merged depart ; git describe --tags $(git merge-base origin/experiment/cache-redis depart)

Q09: src/utils.js
commande: git log depart --follow --name-status --oneline -- src/outils.js

Q10: Nathan Robin
commande: git shortlog -sn depart

Q11: 2026-03-24
commande: git log -1 --format=%cs v1.0.0

Q12: 
commande: 

Q13: 
commande: 

Q14: 
commande: 

Q15: 
commande: 
