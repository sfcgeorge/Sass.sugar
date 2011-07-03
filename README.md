# SCSS (Sass) Sugar for Espresso 2

## Features (Work in progress)

This Sugar is nowhere near complete. It's better than nothing, but barely. Here is what is currently supported:

* Use of .scss file extension or .css.scss extension to trigger the Sugar
* CSS (plain and simple) - this is inherited from the default CSS Sugar
* @include selector
* $variables

## Instalation

1. Download the zip
2. Extract said zip
3. Rename folder to .sugar
4. Double click the .sugar file
5. Restart Espresso - voila!

## What Why Who?

I'm just a programmer and designer who loves Espresso and Sass. There [was] no Sass Sugar for Espresso in active development, and the one/two I found were incomplete. This Sugar is arguably more incomplete, but I aim to change that.

## Can I help?

If you want to help, that would be great. I have no experience with collaborative development or GitHub, but lets give it a shot!

### Implementation

Basic CSS structure and functionality is already implemented by the Default CSS Sugar, so why reinvent the wheel? We include the default CSS Syntax, then build on it using SyntaxInjections. We shouldn't need to touch the Syntax file often, use SyntaxInjections where possible. I have left some of the original CSS Sugar commented out purely for reference.

### Direction

Aim to get the Syntax complete first, then work on Itemizers to get the Navigator working right. Once these core basics are done, finally we can add the fancy stuff like CodeSense.

### Contact

* Try the Espresso IRC room -  ##espresso
* Message me on GitHub
* Tweet to me @sibrow
* Email me... actually I have enough Russian brides as it is, sorry