## Test Catalog

A currated collection of xiliangMa enhanced Helm charts. Charts are curated application definitions for Helm. For more information about installing and using Helm, see its
[README.md](https://github.com/helm/helm/tree/master/README.md). To get a quick introduction to Charts see this [chart document](https://github.com/helm/helm/blob/master/docs/charts.md).


## How do I install?

Just `helm install stable/<chart>`. This is the default repository for Helm which is located at https://kubernetes-charts.storage.googleapis.com/ and is installed by default.

For more information on using Helm, refer to the [Helm's documentation](https://github.com/kubernetes/helm#docs).

## How do I enable the Incubator repository?

To add the Incubator charts for your local client, run `helm repo add`:

```
to do
```

You can then run `helm search xiliangma` to see the charts.


## Chart Format

Take a look at the [alpine example chart](https://github.com/helm/helm/tree/master/docs/examples/alpine) and the [nginx example chart](https://github.com/helm/helm/tree/master/docs/examples/nginx) for reference when you're writing your first few charts.

Before contributing a Chart, become familiar with the format. Note that the project is still under active development and the format may still evolve a bit.