---
# This page has been generated by pkgdocs. Do not edit by hand.
# Edit documentation in crane/R/login.R
title: Login to a Crane repository
linkTitle: login
type: docs
github_repo: https://github.com/openanalytics/crane-r
github_subdir: ''
github_branch: master
path_base_for_github_subdir:
  from: content/.*
  to: crane/R/login.R

---
 


## Description

Login to a Crane repository

## Usage

```r
login(repo, verbose = FALSE)
```

## Arguments

* `repo`: crane repo url
* `verbose`: print info during the login process

## Details

Find or negiotate an access token. In order of preference:

1. load a valid access token from cache
1. refreshing a cached access token
1. negotiate a new access token using the device authorization flow

## Value

access token

