# K3ai Common Plugins

Under this folder will be published all the official supported common application.
A common plugin is something to be used in combination with other plugins

The basic structure of an app is:

- common name (i.e.: istio)
  - k3ai.yaml (this logic of the plugin itself. See [docs]("https://docs.k3a.in/1002/build-an-application-plugin))
  - base (this contain the bundle installation logic)
    - bundle.yaml (contains the application installation references)
  - overlays (this is optional and contain the logic to add specific pre/post requirments, i.e.: install istio before pipelines)
