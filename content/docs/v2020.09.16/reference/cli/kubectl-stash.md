---
title: Kubectl-Stash
menu:
  docs_v2020.09.16:
    identifier: kubectl-stash
    name: Kubectl-Stash
    parent: reference-cli
    weight: 0
menu_name: docs_v2020.09.16
section_menu_id: reference
url: /docs/v2020.09.16/reference/cli/
aliases:
- /docs/v2020.09.16/reference/cli/kubectl-stash/
info:
  catalog: v2020.09.16
  cli: v0.11.0
  community: v0.11.0
  elasticsearch:
  - 5.6.4-v2
  - 6.2.4-v2
  - 6.3.0-v2
  - 6.4.0-v2
  - 6.5.3-v2
  - 6.8.0-v2
  - 7.2.0-v2
  - 7.3.2-v2
  enterprise: v0.11.0
  mongodb:
  - 3.4.17-v2
  - 3.4.22-v2
  - 3.6.13-v2
  - 3.6.8-v2
  - 4.0.11-v2
  - 4.0.3-v2
  - 4.0.5-v2
  - 4.1.13-v2
  - 4.1.4-v2
  - 4.1.7-v2
  - 4.2.3-v2
  mysql:
  - 5.7.25-v2
  - 8.0.14-v2
  - 8.0.3-v2
  percona-xtradb:
  - 5.7-v2
  postgres:
  - 10.14.0
  - 11.9.0
  - 12.4.0
  - 9.6.19
  version: v2020.09.16
---

## kubectl-stash

kubectl plugin for Stash by AppsCode

### Synopsis

kubectl plugin for Stash by AppsCode. For more information, visit here: https://appscode.com/products/stash

### Options

```
      --alsologtostderr                  log to standard error as well as files
      --as string                        Username to impersonate for the operation
      --as-group stringArray             Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --cache-dir string                 Default HTTP cache directory (default "/home/runner/.kube/http-cache")
      --certificate-authority string     Path to a cert file for the certificate authority
      --client-certificate string        Path to a client certificate file for TLS
      --client-key string                Path to a client key file for TLS
      --cluster string                   The name of the kubeconfig cluster to use
      --context string                   The name of the kubeconfig context to use
      --enable-analytics                 Send analytical events to Google Analytics (default true)
  -h, --help                             help for kubectl-stash
      --insecure-skip-tls-verify         If true, the server's certificate will not be checked for validity. This will make your HTTPS connections insecure
      --kubeconfig string                Path to the kubeconfig file to use for CLI requests.
      --log-backtrace-at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log-dir string                   If non-empty, write log files in this directory
      --log-flush-frequency duration     Maximum number of seconds between log flushes (default 5s)
      --logtostderr                      log to standard error instead of files
      --match-server-version             Require server version to match client version
  -n, --namespace string                 If present, the namespace scope for this CLI request
      --request-timeout string           The length of time to wait before giving up on a single server request. Non-zero values should contain a corresponding time unit (e.g. 1s, 2m, 3h). A value of zero means don't timeout requests. (default "0")
  -s, --server string                    The address and port of the Kubernetes API server
      --stderrthreshold severity         logs at or above this threshold go to stderr
      --tls-server-name string           Server name to use for server certificate validation. If it is not provided, the hostname used to contact the server is used
      --token string                     Bearer token for authentication to the API server
      --use-kubeapiserver-fqdn-for-aks   if true, uses kube-apiserver FQDN for AKS cluster to workaround https://github.com/Azure/AKS/issues/522 (default true)
      --user string                      The name of the kubeconfig user to use
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [kubectl-stash clone](/docs/v2020.09.16/reference/cli/kubectl-stash_clone)	 - Clone Kubernetes resources
* [kubectl-stash cp](/docs/v2020.09.16/reference/cli/kubectl-stash_cp)	 - Copy stash resources from one namespace to another namespace
* [kubectl-stash create](/docs/v2020.09.16/reference/cli/kubectl-stash_create)	 - create stash resources
* [kubectl-stash delete](/docs/v2020.09.16/reference/cli/kubectl-stash_delete)	 - Delete stash resources
* [kubectl-stash download](/docs/v2020.09.16/reference/cli/kubectl-stash_download)	 - Download snapshots
* [kubectl-stash trigger](/docs/v2020.09.16/reference/cli/kubectl-stash_trigger)	 - Trigger a backup
* [kubectl-stash unlock](/docs/v2020.09.16/reference/cli/kubectl-stash_unlock)	 - Unlock Restic Repository
* [kubectl-stash version](/docs/v2020.09.16/reference/cli/kubectl-stash_version)	 - Prints binary version number.

