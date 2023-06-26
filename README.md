# R Validation Hub `quarto` Theme

<screenshots to follow>

## Getting Started

### Installing

After creating your new quarto presentation, you can add the R Validation Hub
theme by following a simple, two-step installation process.

```bash
quarto add pharmar/rvalhub-quarto
```

<details>
<summary>_installing from an archive url_</summary>

```bash
quarto add https://github.com/pharmaR/rvalhub-quarto/archive/refs/heads/main.zip
```

</details>

After installing, your project should contain a `_extensions/rvalhub` directory.

### Using

After you've installed the extension, you need to use one of the provided
formats. This can be provided either in your `_quarto.yml` file or in the front
matter of a standalone `quarto` document.

**_quarto.yml**
```
format: rvalhub-revealjs
```

As well as the provided default, you can specify either a light or dark theme
using the format variants, `rvalhub-revealjs+light` and `rvalhub-revealjs+dark`.

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).

After cloning this repo, you can test it out by running

```
quarto preview example.qmd
```