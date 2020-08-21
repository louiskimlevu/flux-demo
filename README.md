# flux-demo
sample gitops project for a nodejs deployment on GKE
1 app folder
1 prod folder
1 dev folder
CI = github actions pushing to Docker Hub on every commit on the path: /paths
CD = flux syncing the dev and prod folders yaml file with a GKE cluster
