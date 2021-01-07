# BootAMP

[BootAMP](https://www.jssaints.com/bootamp) is a Bootstrap-like framework or styling solution for AMP-HTML.

## Why?

If you already use Bootstrap, you may easily adopt AMP-HTML by using BootAMP as it provides almost all necessary Bootstrap components. It also comes with the [migration guide for converting Bootstrap based websites to AMP-HTML](https://www.jssaints.com/bootamp/migration).

AMP-HTML is from Google for good website speed. It also helps in SEO.

## How?

BootAMP is based on the AMP Start starter kit, but organized in such a way that anyone using Bootstrap framework can easily migrate to AMP HTML.

In BootAMP, color and themes change are possible using CSS variables. For better browser support, compiling through postcss is recommended.

## AMP-HTML Themes

BootAMP comes with [boilerplate or AMP-HTML themes](https://www.jssaints.com/bootamp/boilerplate):

1. [AMP-HTML Agency Theme 1](https://www.jssaints.com/bootamp/boilerplate/agency-amp-theme1)
2. [AMP-HTML Agency Theme 2](https://www.jssaints.com/bootamp/boilerplate/agency-amp-theme2)
3. [AMP-HTML Agency Theme 3](https://www.jssaints.com/bootamp/boilerplate/agency-amp-theme3)

## Building `bootamp.min.css`

For better browser support, compiling the CSS variable based `bootamp.src.css` is necessary. Here are the build instructions:

* `npm install` - for setting up dependencies 
* `npm run build` - for building `bootamp.css` from `bootamp.src.css`
* `npm run minify` - for minifying `bootamp.css` to `bootamp.min.css`