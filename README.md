# Hugo in Action

Exercises from the book *Hugo in Action - Static sites and dynamic Jamstack apps* by Atishay Jain.

## ACME Corporation

```bash
hugo new site acme-corporation --format yaml
```

Never used the format option before and I am used doing as much as possible with TOML.

WARNING: the subchapters of chapter 2.2 all have number 1

Theme changes are not always displayed in *live reload* mode. Use:

```bash
hugo server --noHTTPCache --disableFastRender
```

WARNING: Exercise 2.5 should be moved from before chapter 2.3.1 to before chapter 2.3

WARNING: the subchapters or list in chapter 2.4 all have number 1

INFO: Will have to come back to chapter 2.4 beause I don't understand how to push this site to GitHub Pages. is it because I have never used GitHub Actions before?

Chapter 2.6: The changes to the `config.yaml` are not explained for the second theme.

Mixed feelings about chapter 2. Learned some new stuff, but was unable to push site to GitHub Pages with information provided in the book (maybe because I have never used GitHub Actions before) and I don't understand the changes to the `config.yaml` for the second theme. Learning about GitHub Actions and Pages and reading some blog post might help me to push this site to GitHub Pages. Having a closer look to the themes might explain the changes. The `config.toml` seem to be more structured so this might help too.