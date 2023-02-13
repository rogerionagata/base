# base
Basic estructure for project

## Caracteristics

1. Declarative config (https://kubernetes.io/docs/tasks/manage-kubernetes-objects/declarative-config/);
2. Enviroments configuration in specific dir (k8s);
3. Base config dir (k8s/base)
4. Diferents configs for diferents enviroments (env subdirs);
5. Use of jsonpath in kustomization to define specific enviroment configuration (https://kubectl.docs.kubernetes.io/references/kustomize/kustomization/patches/);

## Prerequisites

1. Kubernetes cluster;
2. Argo cd working: https://github.com/argoproj/argo-cd


