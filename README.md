## kcd demo

Try it out yourself locally!

```bash
k3d cluster create kcd -s 3
kustomize build env/prod | kubectl apply -f -
```
