# K3ai Bundles Plugins

Under this folder will be published all the official supported bundles.
A bundle is a combination of multiple plugins

The basic structure of an app is:

- bundle name (i.e.: mlfow-kubeflow)
  - k3ai.yaml (this logic of the plugin itself. See [docs]("https://docs.k3a.in/1002/build-an-application-plugin))
  - base (this contain the bundle installation logic)
    - bundle.yaml (contains the application installation references)
  - overlays (this is optional and contain the logic to add specific pre/post requirments, i.e.: install istio before pipelines)
