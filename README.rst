=========
Sassfiles
=========

This repository is to keep hold of my Sass files I use to "feed" my Blueprint directory CSS files. I use Sass to curate, compile and save my stylesheets to Blueprint's /src/ directory. Blueprint then uses compress.rb to strip out all the extra whitespace and drops it into the appropriate app directory.

Each app has its own subdirectory. In addition, there is a "custom" subdirectory where each application's **CUSTOM** sass files are kept. These are for **CUSTOM** attributes that aren't natively in Blueprint's four main files:

1. typography.css
2. forms.css
3. grid.css
4. reset.css

`_buttons.scss` is a special case, a hack, really, and gets compiled by Sass to "blueprint/blueprint/plugins/buttons/screen.css".
