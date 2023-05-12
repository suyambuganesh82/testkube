## testkube completion fish

Generate the autocompletion script for fish

### Synopsis

Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	testkube completion fish | source

To load completions for every new session, execute once:

	testkube completion fish > ~/.config/fish/completions/testkube.fish

You will need to start a new shell for this setup to take effect.


```
testkube completion fish [flags]
```

### Options

```
  -h, --help              help for fish
      --no-descriptions   disable completion descriptions
```

### Options inherited from parent commands

```
  -a, --api-uri string     api uri, default value read from config if set (default "https://demo.testkube.io/results/v1")
  -c, --client string      client used for connecting to Testkube API one of proxy|direct (default "proxy")
      --namespace string   Kubernetes namespace, default value read from config if set (default "testkube")
      --oauth-enabled      enable oauth
      --verbose            show additional debug messages
```

### SEE ALSO

* [testkube completion](testkube_completion.md)	 - Generate the autocompletion script for the specified shell
