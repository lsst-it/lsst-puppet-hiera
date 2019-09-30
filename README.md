lsst-puppet-hiera
===

[![Build Status](https://travis-ci.org/lsst-it/lsst-puppet-hiera.png)](https://travis-ci.org/lsst-it/lsst-puppet-hiera)

This repo contains lsst "site" specific hieradata. It is intended to be
public and should *never* contain any secrets.

hierarchy
---

```sh
node/%{fqdn}.yaml
datacenter/%{datacenter}/cluster/%{cluster}/role/%{role}.yaml
cluster/%{cluster}/role/%{role}.yaml
cluster/%{cluster}.yaml
datacenter/%{datacenter}/role/%{role}.yaml
datacenter/%{datacenter}.yaml
site/%{site}.yaml
role/%{role}.yaml
type/%{virtual}.yaml
type/default.yaml
common.yaml
```
