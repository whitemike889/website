---
title: Kubectl-Stash
menu:
  docs_v0.9.0-rc.4:
    identifier: kubectl-stash-v0.3.0
    name: Kubectl-Stash
    parent: stash-cli-references-v0.3.0
    weight: 0
product_name: stash
section_menu_id: guides
menu_name: docs_v0.9.0-rc.4
aliases:
- /docs/v0.9.0-rc.4/guides/latest/cli/reference/v0.3.0
info:
  catalog: v0.2.0
  cli: v0.3.0
  subproject_version: v0.3.0
  version: v0.9.0-rc.4
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
      --cache-dir string                 Default HTTP cache directory (default "/home/tamal/.kube/http-cache")
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
      --token string                     Bearer token for authentication to the API server
      --use-kubeapiserver-fqdn-for-aks   if true, uses kube-apiserver FQDN for AKS cluster to workaround https://github.com/Azure/AKS/issues/522 (default true)
      --user string                      The name of the kubeconfig user to use
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [kubectl-stash clone](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_clone)	 - Clone Kubernetes resources
* [kubectl-stash cp](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_cp)	 - Copy stash resources from one namespace to another namespace
* [kubectl-stash create](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_create)	 - create stash resources
* [kubectl-stash delete](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_delete)	 - Delete stash resources
* [kubectl-stash download](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_download)	 - Download snapshots
* [kubectl-stash trigger](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_trigger)	 - Trigger a backup
* [kubectl-stash unlock](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_unlock)	 - Unlock Restic Repository
* [kubectl-stash version](/docs/v0.9.0-rc.4/guides/latest/cli/reference/{{< param "info.subproject_version" >}}/kubectl-stash_version)	 - Prints binary version number.
