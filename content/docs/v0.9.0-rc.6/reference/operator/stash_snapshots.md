---
title: Snapshots
menu:
  docs_v0.9.0-rc.6:
    identifier: stash-snapshots
    name: Snapshots
    parent: operator
product_name: stash
section_menu_id: reference
menu_name: docs_v0.9.0-rc.6
info:
  catalog: v0.3.0
  cli: v0.3.1
  version: v0.9.0-rc.6
---

## stash snapshots

Get snapshots of restic repo

### Synopsis

Get snapshots of restic repo

```
stash snapshots [snapshotID ...] [flags]
```

### Options

```
  -h, --help                help for snapshots
      --kubeconfig string   Path to kubeconfig file with authorization information (the master location is set by the master flag).
      --master string       The address of the Kubernetes API server (overrides any value in kubeconfig)
      --repo-name string    Name of the Repository CRD.
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --bypass-validating-webhook-xray   if true, bypasses validating webhook xray checks
      --enable-analytics                 Send analytical events to Google Analytics (default true)
      --log-flush-frequency duration     Maximum number of seconds between log flushes (default 5s)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default true)
      --service-name string              Stash service name. (default "stash-operator")
      --stderrthreshold severity         logs at or above this threshold go to stderr
      --use-kubeapiserver-fqdn-for-aks   if true, uses kube-apiserver FQDN for AKS cluster to workaround https://github.com/Azure/AKS/issues/522 (default true)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [stash](/docs/v0.9.0-rc.6/reference/operator/stash)	 - Stash by AppsCode - Backup your Kubernetes Volumes

