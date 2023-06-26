# R Validation Hub `quarto` Theme

[preview.webm](https://github.com/pharmaR/rvalhub-quarto/assets/18220321/87b4a5e0-c34d-468a-ada5-4edf5db0ec54)

`format: rvalhub-revealjs+light` (or default alias, `rvalhub-revealjs`)
![image](https://github.com/pharmaR/rvalhub-quarto/assets/18220321/dd7aaae5-1a27-40ad-bcea-3906cb71f29b)

`format: rvalhub-revealjs+dark`
![image](https://github.com/pharmaR/rvalhub-quarto/assets/18220321/1d495a2d-f2b2-49d9-89e6-931b3f36c971)

## Getting Started

### Installing

After creating your new quarto presentation, you can add the R Validation Hub
theme by following a simple, two-step installation process.

```bash
quarto add pharmar/rvalhub-quarto
```

<details>
<summary><i>alternatively install from an archive url</i></summary>

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
