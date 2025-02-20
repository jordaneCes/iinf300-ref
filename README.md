# Mise en place d'un déploiement continu d'une application docker sur Harbor
## Présentation du repo

Ce repo possède un dossier `docker` , dans celui-ci on retrouve un fichier `Dockerfile` qui créé une application basée sur les sources dans le dossier `docker/app`.

Nous retrouvons également le dossier `.github/workflows`. Dans celui-ci nous retrouvons le fichier build-demo qui sert pour la mise en place d'une pipeline qui permet de déployer une image sur harbor. Plus d'info "https://docs.github.com/en/actions/writing-workflows/quickstart"

## Consignes d'amélioration 

Par groupe clonez ce repo et vérifiez que le workflow fonctionne bien. 

Attention, placez le mot de passe habituel qui va bien dans https://github.com/___urldevotrerepo___/settings/secrets/actions et changez `harbor.kakor.ovh/ipi/correction` par `harbor.kakor.ovh/ipi/groupe-x`.
