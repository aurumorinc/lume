# Changelog v3.0.0

## Breaking Changes

* **Project Namespace Migration**
  The project has been renamed from `lume` to `worldline`. This change affects all package imports, module paths, and configuration keys.
  * **Migration Guide:**
    * Update all import statements in your codebase from `lume/...` to `worldline/...`.
    * Update any configuration files or environment variables that previously referenced `lume` to use the new `worldline` namespace.
  * **Commits:** [d2e265a](https://github.com/aurumorinc/lume-python/commit/d2e265ae), [2c52b6a](https://github.com/aurumorinc/lume-python/commit/2c52b6ae)
