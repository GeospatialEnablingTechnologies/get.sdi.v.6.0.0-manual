# get.sdi.v.6.0.0-manual

Manual page for GET SDI v6.0. Built with MkDocs + Material for MkDocs.

## Development (Dev Container)

The repo includes a Dev Container with MkDocs and all dependencies preinstalled.

**Requirements:** Docker, plus one of: VS Code + Dev Containers extension, GitHub Codespaces, or the `devcontainer` CLI.

**Open it:**

- VS Code: open the folder, then *Reopen in Container*.
- CLI:
  ```bash
  devcontainer up --workspace-folder .
  devcontainer exec --workspace-folder . bash
  ```

**Preview (live reload):**

```bash
mkdocs serve --dev-addr 0.0.0.0:8000
```

Open http://127.0.0.1:8000 (port is forwarded automatically).

**Build:**

```bash
mkdocs build --strict
```

## Without the container

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install mkdocs-material
mkdocs serve
```