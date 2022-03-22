# Marp template repository

This repository contains a basic template to create slides with [MARP](https://marp.app)

## Structure

This repo contains a set of template `.md` files in the `templates` folder, which can help you to bootstrap your slides. Each of the template has a name which contains the aspect ratio and the theme it uses.

In order to create a slide, copy that template to a `slides` folder where you can store all of your slides.

Once you finished filling the slide with content, you can proceed to generate the output files by taking advantage of the [marp-cli](https://github.com/marp-team/marp-cli)

## Create output slides in .html and .pdf

All output slides will be generated in the `public` directory

Here are reported some useful commands you can run to create the output slides:

```bash
# Convert all slides in the slides folder to .html
npx @marp-team/marp-cli@latest

# Convert all slides in the slides folder to .pdf
npx @marp-team/marp-cli@latest --pdf

# Run the server to present slides
npx @marp-team/marp-cli@latest -s
```

Further details on the commands available can be found [here](https://github.com/marp-team/marp-cli/blob/main/README.md)

## Customization
If you want to create cutsom themes, I would suggest to create them starting from the [slate](./themes/slate.css) theme.