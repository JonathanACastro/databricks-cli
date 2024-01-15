# Examples using Databricks Stack CLI

Here we provide examples on how to use Databricks Stack CLI commands in a simple manner.
This examples came from https://docs.databricks.com/en/dev-tools/cli/tutorial.html

### Commands:

* Open cmd in windows and type:

```
databricks -v
```

* If everything is working, you will see that: 

```
databricks stack deploy --profile $PROFILE project-stack-config.json -o
```

After the stack is successfully deployed, a stack status file `project-stack-config.deployed.json` will be created in the same directory.
