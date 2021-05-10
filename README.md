# Game of Pods - voting-app solution
*João Martins*

1. Create namespace first using `kubectl apply -f vote.yaml`
1. Switch to namespace: `kubectl config set-context --current --namespace=vote`
1. Apply remaining yaml files: `kubectl apply -f <file>`
1. Check outcome in quiz page, should get resulting chant: *Hen desarrollo, integreiddio. Hen integreiddio, testa. Hen testa, lifa.*
