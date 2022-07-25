# About

Addon that can be used with [microk8s](https://microk8s.io/) to deploy [CloudNativePG](https://cloudnative-pg.io/)

# Install

```
microk8s addons repo add cloudnative-pg https://github.com/sxd/cloudnative-pg-addon
microk8s enable cloudnative-pg
```

# Uninstall

```
microk8s disable cloudnative-pg 
microk8s addons repo remove cloudnative-pg
```

