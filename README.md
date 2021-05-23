---
```

├── README.md
├── clusters
│   ├── README.md
│   ├── dev-cluster
│   │   ├── README.md
│   │   ├── kustomization.yaml
│   │   └── operators
│   │       ├── kustomization.yaml
│   │       └── servicemesh-operator.yaml
│   ├── prod-cluster
│   │   ├── README.md
│   │   ├── kustomization.yaml
│   │   └── operators
│   │       ├── kustomization.yaml
│   │       └── servicemesh-operator.yaml
│   └── stg-cluster
│       ├── kustomization.yaml
│       └── operators
│           ├── kustomization.yaml
│           └── servicemesh-operator.yaml
└── namespaces
    ├── project001
    │   ├── baseline
    │   │   ├── compute-quota.yaml
    │   │   ├── kustomization.yaml
    │   │   ├── mem-limit-range.yaml
    │   │   ├── networkpolicy-deny-other-namespaces.yaml
    │   │   ├── object-counts-quota.yaml
    │   │   └── storage-class-quota.yaml
    │   ├── custom
    │   │   ├── custom.yaml
    │   │   └── kustomization.yaml
    │   ├── kustomization.yaml
    │   ├── namespace.yaml
    │   └── rbac
    │       ├── admin.yaml
    │       └── kustomization.yaml
    ├── project002
    │   ├── baseline
    │   │   ├── compute-quota.yaml
    │   │   ├── kustomization.yaml
    │   │   ├── mem-limit-range.yaml
    │   │   ├── networkpolicy-deny-other-namespaces.yaml
    │   │   ├── object-counts-quota.yaml
    │   │   └── storage-class-quota.yaml
    │   ├── custom
    │   │   ├── custom.yaml
    │   │   └── kustomization.yaml
    │   ├── kustomization.yaml
    │   ├── namespace.yaml
    │   └── rbac
    │       ├── admin.yaml
    │       └── kustomization.yaml
    ├── project003
    │   ├── baseline
    │   │   ├── compute-quota.yaml
    │   │   ├── kustomization.yaml
    │   │   ├── mem-limit-range.yaml
    │   │   ├── networkpolicy-deny-other-namespaces.yaml
    │   │   ├── object-counts-quota.yaml
    │   │   └── storage-class-quota.yaml
    │   ├── custom
    │   │   ├── custom.yaml
    │   │   └── kustomization.yaml
    │   ├── kustomization.yaml
    │   ├── namespace.yaml
    │   └── rbac
    │       ├── admin.yaml
    │       └── kustomization.yaml
    └── project004
        ├── baseline
        │   ├── compute-quota.yaml
        │   ├── kustomization.yaml
        │   ├── mem-limit-range.yaml
        │   ├── networkpolicy-deny-other-namespaces.yaml
        │   ├── object-counts-quota.yaml
        │   └── storage-class-quota.yaml
        ├── custom
        │   ├── custom.yaml
        │   └── kustomization.yaml
        ├── kustomization.yaml
        ├── namespace.yaml
        └── rbac
            ├── admin.yaml
            └── kustomization.yaml
```
