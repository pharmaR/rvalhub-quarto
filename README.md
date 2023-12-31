# R Validation Hub `quarto` Theme

[preview.webm](https://github.com/pharmaR/rvalhub-quarto/assets/18220321/cfc056b1-a0d2-411b-be87-aa81f4fdae30)

`format: rvalhub-revealjs+light` (or default alias, `rvalhub-revealjs`)
![image](https://github.com/pharmaR/rvalhub-quarto/assets/18220321/aa4e4790-6ca6-47be-97b5-9b23b2580684)

`format: rvalhub-revealjs+dark`
![image](https://github.com/pharmaR/rvalhub-quarto/assets/18220321/e5185955-97a8-4021-b036-d0a29267cebc)

## Getting Started

### Installing

After creating your new quarto presentation, you can add the R Validation Hub
theme by following a simple, two-step installation process.

```bash
quarto add pharmaR/rvalhub-quarto
```

<details>
<summary><i>alternatively install from an archive url</i></summary>

```bash
quarto add https://github.com/pharmaR/rvalhub-quarto/archive/refs/heads/main.zip
```

</details>

After installing, your project should contain a `_extensions/pharmaR/rvalhub` directory.

> ***Note: GitHub Organization Case Sensitivity***  
> Although `quarto` will gladly install the extension using a case-insensitive
> GitHub org, assets used throughout the extension will use case-sensitive file paths.
> Be sure to use the appropriate casing. 

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

## Starting a new `quarto` project

### Using `quarto` from the command line

1. Create a new `quarto` project

```
quarto create  # follow prompts to start a default project
```

> _change to new project directory_

2. Add `quarto` format extension

```
quarto add pharmaR/rvalhub-quarto
```

3. Update your `_quarto.yml` file

```diff
+ format: rvalhub-revealjs
```

or use the dark variant by using:

```diff
+ format: rvalhub-revealjs+dark
```