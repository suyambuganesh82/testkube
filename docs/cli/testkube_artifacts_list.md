## testkube artifacts list

List artifacts of the given execution ID

```
testkube artifacts list <executionID> [flags]
```

### Options

```
  -e, --execution-id string   ID of the execution
  -h, --help                  help for list
```

### Options inherited from parent commands

```
      --analytics-enabled   should analytics be enabled (default true)
  -c, --client string       Client used for connecting to testkube API one of proxy|direct (default "proxy")
  -s, --namespace string    kubernetes namespace (default "testkube")
  -v, --verbose             should I show additional debug messages
```

### SEE ALSO

* [testkube artifacts](testkube_artifacts.md)	 - Artifacts management commands
