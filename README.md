# Ansible Role: Binbash Jenkins BitBucket OAuth

Ansible role for installing and configuring BitBucket OAuth on Jenkins

## Requirements
* Jenkins with BitBucket OAuth plugin installed => https://plugins.jenkins.io/bitbucket-oauth/
* Also make sure you read the docs in the plugin repo => https://github.com/jenkinsci/bitbucket-oauth-plugin

## Examples
```
  - role: binbash_inc.jenkins-bitbucket-oauth
    jenkins_bitbucket_oauth_client_id: "your-bitbucket-oauth-client-id"
    jenkins_bitbucket_oauth_client_secret: "your-bitbucket-oauth-client-secret"

```
