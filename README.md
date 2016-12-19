# CastleCSS Icons Files
![CastleCSS logo @CastleCss.com](https://www.doordarius.nl/castlecss-logo-250.png)
CastleCSS icon set via Font Awesome and Cloudflare.

## CastleCSS Framework
The buttons files are part of the [Full CastleCSS Package](https://github.com/CastleCSS/castlecss), you need this, the [castlecss-core](https://github.com/CastleCSS/castlecss) or create your own variables files in order to make castlecss-icons work.

## How to install
- Install via [NPM](https://www.npmjs.com/): ```npm install castlecss-icons```
- Require it in your own NPMJS package
- Download or clone the package

## Updating files
CastleCSS is built so it's easy to update, you can just download make it your own as long as you don't ovewrite the core files. 

```npm update castlecss-icons```

## Documentation and examples
You can find the documentation and examples at http://www.castlecss.com and [castlecss-docs](https://github.com/CastleCSS/castlecss-icons)

## Setup
Your project should have a setup similair to this (included in the [Full CastleCSS Package](https://github.com/CastleCSS/castlecss)):
With this you make sure your own variables overwrite the castle-core variables and your setup is still updatable.

```
| Your project/
|
|-- scss/ 
| |-- /* Custom project specific scss files here */
| |-- Main.scss
| |
|-- node_modules/
| | 
| | /*	CastleCSS files included automatically here */
| | castlecss-core/
| | castlecss-buttons/
| | castlecss-icons/
| | castlecss-etc ;)/
```

### Main.scss
Your main.scss should have a setup similair to this (included in the [Full CastleCSS Boilerplate](https://github.com/CastleCSS/castlecss-boilerplate)):

```
/*  core variable files */
@import "path/to/castlecss-core/sass/variables";

/*  Your own variables so they overwrite the core */
@import "variables";

/*  rest of core files */
@import "node_modules/castlecss-core/sass/main";
@import "node_modules/castlecss-icons/sass/main";

 
/*  Include your own files below this line
    --------------------------------------
*/
```
## Roadmap
We're currently working hard on making the CastleCSS expansions and improvements. CastleCSS is made to serve as lightweight basis for tailor made software but we do want to give you the option to install a few modules to make your life easier.

Please see the [ROADMAP.MD from the CastleCSS Meta Package](https://github.com/CastleCSS/castlecss/blob/master/ROADMAP.md) for our current plans for the future.

## Contributing
Want to contribute? We'd love your help, please take a look at the roadmap or submit new suggestions.