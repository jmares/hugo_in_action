# Hugo in Action

Exercises from the book *Hugo in Action - Static sites and dynamic Jamstack apps* by Atishay Jain.

## ACME Corporation

```bash
hugo new site acme-corporation --format yaml
```

Never used the format option before and I am used doing as much as possible with TOML.

Error: the subchapters of chapter 2.2 all have number 1

Theme changes are not always displayed in *live reload* mode. Use:

```bash
hugo server --noHTTPCache --disableFastRender
```

Error: Exercise 2.5 should be moved from before chapter 2.3.1 to before chapter 2.3