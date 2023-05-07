# Letter Format Template

This is a Quarto template that assists you in creating a manuscript using the letter format.

## Creating a New Letter

You can use this as a template to create a letter.
To do this, use the following command:

```bash
quarto use template compies/quarto-letter
```

This will install the extension and create an example qmd file and bibliography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document.
From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension compies/quarto-letter
```

## Usage

To use the format, you can use the format name `letter-pdf`
For example:

```bash
quarto render template.qmd --to letter-pdf
```

or in your document yaml

```yaml
format: letter-pdf
```

In order to use it easyly you have copy/fork this repository edit the `_extension.yml` with your personal information so you don't have to type it every time in your main qmd-file.

You can view a preview of the rendered template at https://github.com/compies/quarto-letter/blob/main/Example/Example.pdf
