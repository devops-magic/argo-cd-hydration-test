# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/devops-magic/argo-cd-hydration-test
# cd into the cloned directory
git checkout 427c0a70c8df4375ec25eb97b244fb42c08c22d4
helm template . --name-template my-app --include-crds
```
