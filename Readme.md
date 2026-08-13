# org.kekikakademi.eFatura

For bug reports and feature requests, see: [eFatura](https://github.com/keyiflerolsun/eFatura)

`SRC/python3-requirements.yaml` is generated from upstream's `pyproject.toml`, resolved against the exact runtime declared in `org.kekikakademi.eFatura.yml` (needed so vendored wheels match the runtime's Python/platform tags, not the host's).

Run upstream's [`flatpakDepsGuncelle.yml`](https://github.com/keyiflerolsun/eFatura/actions/workflows/flatpakDepsGuncelle.yml) workflow (`workflow_dispatch`) and copy the uploaded `python3-requirements.yaml` artifact here — no local flatpak install needed. To run it locally instead, `flatpak install org.gnome.Sdk//<runtime-version>` is required first, then `bash Shared/SRC/guncelle.sh`.
