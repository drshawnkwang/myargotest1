# One-off values files

Helm values for software deployed to **specific clusters**, driven by
`argocd-applicationsets/appset-oneoffs.yaml`.

These live here rather than in `clusters/<cluster>/` because that tree is
reserved for fleet-wide chart overlays, where a file's presence implies the
chart is deployed everywhere.

Naming convention: `<name>-values.yaml`, matching the `name` of the
corresponding element in `appset-oneoffs.yaml`.

Empty for now; `appset-oneoffs.yaml` has no elements yet.
