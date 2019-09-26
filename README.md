# ReproNOGO
```
bazel build src/demo/...
bazel test src/demo/...
```
both succeed

```
bazel coverage src/demo/...
```
failed with nogo check

The nogo analyze is excluded in the config file (nogo.json)
