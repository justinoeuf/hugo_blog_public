### Hi! It's time to build your own blog! ###
This reposity was created to share resources for those looking for a blog template. 99% of the code here was taken from [github/luizepra](https://github.com/luizdepra) and his ["Hugo Coder" Repository](https://github.com/luizdepra/hugo-coder). The other 1% are my changes to the html layout, specifically with regard to how Posts are displayed.

Check out the ["Posts"](https://hugo-coder.netlify.app/posts/) section of luizdepra's [Demo](https://hugo-coder.netlify.app/) site and my ["Posts"](https://justinoeuf.github.io/hugo_blog_public/posts/) section for my [Demo](https://justinoeuf.github.io/hugo_blog_public/) site to see the main differences.

This repo can be cloned directly with one small edit-- In the config.toml file, remove the line that says `publishDir: "docs"`. This addition was necessary for me to host the site on github.

For full documentation see the source repository from [Hugo Coder](https://github.com/luizdepra/hugo-coder). Below is the README.md from the page:

---

A simple and clean blog theme for [Hugo](https://gohugo.io/).

![](https://github.com/luizdepra/hugo-coder/blob/master/images/screenshot.png)

## Live Demo

See [here](https://hugo-coder.netlify.app/).

## Quick Start

1. Add the repository into your Hugo Project repository as a submodule, `git submodule add https://github.com/luizdepra/hugo-coder.git themes/hugo-coder`.
2. Configure your `config.toml`. You can either use [this minimal configuration](https://github.com/luizdepra/hugo-coder/wiki/Configurations#complete-example) as a base, or look for a complete explanation about all configurations [here](https://github.com/luizdepra/hugo-coder/wiki/Configurations). The [`config.toml`](https://github.com/luizdepra/hugo-coder/blob/master/exampleSite/config.toml) inside the [`exampleSite`](https://github.com/luizdepra/hugo-coder/tree/master/exampleSite) is also a good reference.
3. Build your site with `hugo serve` and see the result at `http://localhost:1313/`.

## Extra Guides

* [Multilingual Mode](https://github.com/luizdepra/hugo-coder/wiki/Multilingual-Mode)

## Stackbit

This theme is ready to import into Stackbit. This theme can be deployed to Netlify and you can connect any headless CMS including Forestry, NetlifyCMS, DatoCMS or Contentful.

[![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/luizdepra/hugo-coder)

## License

Coder is licensed under the [MIT license](https://github.com/luizdepra/hugo-coder/blob/master/LICENSE.md).

## Maintenance

This theme is maintained by its author [Luiz de Pr??](https://github.com/luizdepra) with the help from these awesome [contributors](CONTRIBUTORS.md).

## Sponsoring

If you like my project or it was useful for you, consider supporting its development. Just:

<a href="https://www.buymeacoffee.com/luizdepra" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-green.png" alt="Buy Me A Coffee" height="41" width="174"></a>

## Special Thanks

- Gleen McComb, for his great [article](https://glennmccomb.com/articles/how-to-build-custom-hugo-pagination/) about custom pagination.
- All contributors, for every PR and Issue reported.
