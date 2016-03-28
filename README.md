
# middleman-blog
Front-end best practices playground.

## What is demonstrated:
* Naming conventions as per: http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/ (BEM with "type" prefixes)
* NPM as front-end package manager
* Components-and-connectors -> bundles front-end architecture
* CSS scope: **c-cms** scope for editor / web producer authored content
* CSS object: **o-outer-container** wrapper class for Bourbon / Neat's outer-container mixin
* CSS object: **o-grid-equal-cols** responsive grid object based on Bourbon / Neat
    * Automatic columns based on markup
    * Manual columns based on container CSS class name
    * Optionally with row gutters
    * Breakpoint-based column counts (per breakpoint, or breakpoint-and-above, or breakpoint-and-below)
* Theming based on SASS maps (with code-completion-friendly keys)

## Quick start
You will need npm and Ruby installed globally.
```
npm install
bundle install
rake
```
