---
title: "Helm 补全"
---

## helm completion

为指定的shell生成自动补全脚本

### 简介

为Helm生成针对于指定shell的自动补全脚本

### 可选项

```shell
  -h, --help   help for completion
```

### 从父命令继承的命令

```shell
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         Username to impersonate for the operation
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### 请参阅

- [helm](helm.md) - 针对Kubernetes的Helm包管理器
- [helm completion bash](helm_completion_bash.md) - 为bash生成自动补全脚本
- [helm completion fish](helm_completion_fish.md) - 为fish生成自动补全脚本
- [helm completion zsh](helm_completion_zsh.md) - 为zsh生成自动补全脚本