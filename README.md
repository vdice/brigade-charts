
# Brigade Charts

Helm charts for the [Brigade](https://github.com/brigadecore/brigade) project have been moved to
[brigadecore/charts](https://github.com/brigadecore/charts).

During the transitional phase, we will continue to serve an index file in this repo pointing
to the new chart URL of `https://brigadecore.github.io/charts`.

All subsequent chart releases will be served at this URL.

Please update your local Helm repo:

  ```
  helm repo remove brigade
  helm repo add brigade https://brigadecore.github.io/charts
  ```

This repo will be deleted after the transition is complete.