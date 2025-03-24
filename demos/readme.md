### Using Stackable Demos

Stackable provides several pre-configured demos to help you get started with the Stackable Data Platform.

#### Installing Demos

To install a demo, use the `stackablectl demo install` command followed by the demo name and the demos configuration file:

```bash
stackablectl demo install <demo-name> -d demos/demos-v2.yaml
```

For example:
```bash
stackablectl demo install trino-taxi-data -d demos/demos-v2.yaml
```

Options:
  --no-cache: 

#### Available Demos

Here are some of the available demos:

- `trino-taxi-data`: Demonstrates Trino querying capabilities with NYC taxi data
- `spark-k8s`: Showcases Spark on Kubernetes
- `superset-druid`: Analytics dashboard with Apache Superset and Druid

#### List Available Demos

To see all available demos:

```bash
stackablectl demo list -d demos/demos-v2.yaml
```

#### Removing Demos

Currently, there is no support for uninstalling a demo again. However, this functionality will come soon.

For more information, visit the [Stackable documentation](https://docs.stackable.tech/home/stable/demos/).