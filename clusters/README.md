# Clusters Directory

This directory contains cluster definitions managed by the k8s-platform.

## Structure

```
clusters/
├── dev/           # Development environment clusters
├── staging/       # Staging environment clusters
└── production/    # Production environment clusters
```

## Usage

Cluster YAML files are created, updated, and deleted by the k8s-platform UI.
Changes are committed to this repository via GitOps.
