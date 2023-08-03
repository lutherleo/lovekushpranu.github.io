# Love Kush Pranu's Personal Website

## Theme Updation

Warning: Do not manually git clone theme into the themes directory. The theme is added as a submodule and submodule commands should be used to download and update the theme.

First, clone the repository along with the submodule files recursively:

- SSH based Git Clone
    ```bash
    git clone --recurse-submodules git@github.com:lutherleo/lovekushpranu.github.io.git
    ```

Or

- HTTPS based Git Clone
    ```bash
    git clone --recurse-submodules https://github.com/lutherleo/lovekushpranu.github.io.git
    ```

To update theme:
```bash
git submodule update --remote --merge
```
