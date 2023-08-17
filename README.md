# planning-tool-postgres


argocd app create planning-postgres --repo  https://github.com/pdngayan/planning-tool-postgres.git --revision main  --path helm/planning-postgres-chart --dest-server https://kubernetes.default.svc --dest-namespace default




