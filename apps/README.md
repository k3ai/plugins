# K3ai Applications Plugins

Under this folder will be published all the official supported applications

The basic structure of an app is:

- app name (i.e.: pipelines)
  - k3ai.yaml (this logic of the plugin itself. See [docs]("https://docs.k3a.in/1002/build-an-application-plugin))
  - base (this contain the plugin installation logic)
    - app.yaml (contains the application installation references)
  - overlays (this is optional and contain the logic to add specific pre/post requirments, i.e.: install istio before pipelines)
