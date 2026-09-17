# Hugo Module - Theme Test

This Hugo theme provides a shortcode named `git-submodule-test` to test that a project can import this repository as a Git submodule.

To add this theme to your project as a Git submodule:

```sh
git submodule add https://github.com/jmooring/hugo-theme-example themes/hugo-theme-example
```

Then add this to your project configuration:

```toml
[[module.imports]]
  path = 'hugo-theme-example'
```
