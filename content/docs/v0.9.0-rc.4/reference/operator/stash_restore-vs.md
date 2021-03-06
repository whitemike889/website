---
title: Restore-Vs
menu:
  docs_v0.9.0-rc.4:
    identifier: stash-restore-vs
    name: Restore-Vs
    parent: operator
product_name: stash
section_menu_id: reference
menu_name: docs_v0.9.0-rc.4
info:
  catalog: v0.2.0
  cli: v0.3.0
  version: v0.9.0-rc.4
---

## stash restore-vs

Restore PVC from VolumeSnapshot

### Synopsis

Restore PVC from VolumeSnapshot

```
stash restore-vs [flags]
```

### Options

```
  -h, --help                     help for restore-vs
      --kubeconfig string        Path to kubeconfig file with authorization information (the master location is set by the master flag).
      --master string            The address of the Kubernetes API server (overrides any value in kubeconfig)
      --metrics-enabled          Specify whether to export Prometheus metrics (default true)
      --pushgateway-url string   Pushgateway URL where the metrics will be pushed
      --restoresession string    Name of the respective RestoreSession object
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

* [stash](/docs/v0.9.0-rc.4/reference/operator/stash)	 - Stash by AppsCode - Backup your Kubernetes Volumes

