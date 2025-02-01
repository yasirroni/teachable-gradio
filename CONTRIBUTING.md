# Contributing Guide

## Git Filter (temporarily deprecated)

We use [`nb-clean`](https://github.com/srstevenson/nb-clean) to clean notebook metadata.

To always clean any notebook on commit,

```shell
nb-clean add-filter --remove-all-notebook-metadata
```

To clean individual notebook, use below examples as reference,

```shell
nb-clean clean "nbs/gradio_tf.ipynb"
nb-clean clean "nbs/teachable_gradio.ipynb"
```
