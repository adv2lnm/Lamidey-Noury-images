<<<<<<< HEAD
# [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll.svg)](https://rubygems.org/gems/minimal-mistakes-jekyll)
[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-green.svg?logo=paypal)](https://www.paypal.me/mmistakes)
[![Donate to this project using Buy Me A Coffee](https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg)](https://www.buymeacoffee.com/mmistakes)

Minimal Mistakes is a flexible two-column Jekyll theme, perfect for building personal sites, blogs, and portfolios. As the name implies, styling is purposely minimalistic to be enhanced and customized by you :smile:.

:sparkles: See what's new in the [CHANGELOG](CHANGELOG.md).

**If you enjoy this theme, please consider sponsoring:**

[!["Buy Me A Coffee"](https://user-images.githubusercontent.com/1376749/120938564-50c59780-c6e1-11eb-814f-22a0399623c5.png)](https://www.buymeacoffee.com/mmistakes)
 [![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://www.paypal.me/mmistakes)

**Note:** The theme uses the [jekyll-include-cache](https://github.com/benbalter/jekyll-include-cache) plugin which will need to be installed in your `Gemfile` and must be retained in the `plugins` array of `_config.yml`. Otherwise you'll encounter `Unknown tag 'include_cached'` errors at build.

[![Minimal Mistakes live preview][2]][1]

[1]: https://mmistakes.github.io/minimal-mistakes/
[2]: screenshot.png (live preview)

![layout examples](screenshot-layouts.png)

## Notable features

- Bundled as a "theme gem" for easier installation/upgrading.
- Compatible with GitHub Pages.
- Support for Jekyll's built-in Sass/SCSS preprocessor.
- Nine different skins (color variations).
- Several responsive layout options (single, archive index, search, splash, and paginated home page).
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data.
- Optional [header images](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#headers), [custom sidebars](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#sidebars), [table of contents](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#table-of-contents), [galleries](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#gallery), related posts, [breadcrumb links](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#breadcrumb-navigation-beta), [navigation lists](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#navigation-list), and more.
- Commenting support (powered by [Disqus](https://disqus.com/), [Facebook](https://developers.facebook.com/docs/plugins/comments), Google+, [Discourse](https://www.discourse.org/), static-based via [Staticman](https://staticman.net/), [utterances](https://utteranc.es/), and [giscus](https://giscus.app/)).
- [Google Analytics](https://www.google.com/analytics/) support.
- UI localized text in English (default), Arabic (عربي), Brazilian Portuguese (Português brasileiro), Catalan, Chinese, Danish, Dutch, Finnish, French (Français), German (Deutsch), Greek, Hebrew, Hindi (हिंदी), Hungarian, Indonesian, Irish (Gaeilge), Italian (Italiano), Japanese, Kiswahili, Korean, Malayalam, Myanmar (Burmese), Nepali (Nepalese), Norwegian (Norsk), Persian (فارسی), Polish, Punjabi (ਪੰਜਾਬੀ), Romanian, Russian, Slovak, Spanish (Español), Swedish, Thai, Turkish (Türkçe), and Vietnamese.

## Skins (color variations)

This theme comes in nine different skins (in addition to the default one).

| `air` | `contrast` | `dark` |
| --- | --- | --- |
| [![air skin](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive-large.png) | [![contrast skin](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive-large.png) | [![dark skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive-large.png) |

| `dirt` | `mint` | `sunrise` |
| --- | --- | --- |
| [![dirt skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive-large.png) | [![mint skin](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive-large.png) | [![sunrise skin](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive-large.png) |

| `aqua` | `neon` | `plum` |
| --- | --- | --- |
| [![aqua skin](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive-large.png) | [![neon skin](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive-large.png) | [![plum skin](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive-large.png) |

## Demo pages

| Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |

Additional sample posts are available under [posts archive][year-archive] on the demo site. Source files for these (and the entire demo site) can be found in [`/docs`](docs).

[header-image-post]: https://mmistakes.github.io/minimal-mistakes/layout-header-image-text-readability/
[gallery-post]: https://mmistakes.github.io/minimal-mistakes/post%20formats/post-gallery/
[html-tags-post]: https://mmistakes.github.io/minimal-mistakes/markup/markup-html-tags-and-formatting/
[syntax-post]: https://mmistakes.github.io/minimal-mistakes/markup-syntax-highlighting/
[sample-collection]: https://mmistakes.github.io/minimal-mistakes/recipes/chocolate-chip-cookies/
[categories-archive]: https://mmistakes.github.io/minimal-mistakes/categories/
[tags-archive]: https://mmistakes.github.io/minimal-mistakes/tags/
[year-archive]: https://mmistakes.github.io/minimal-mistakes/year-archive/

## Installation

There are three ways to install: as a [gem-based theme](https://jekyllrb.com/docs/themes/#understanding-gem-based-themes), as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) (GitHub Pages compatible), or forking/directly copying all of the theme files into your project.

### Gem-based method

With Gem-based themes, directories such as the `assets`, `_layouts`, `_includes`, and `_sass` are stored in the theme’s gem, hidden from your immediate view. Yet all of the necessary directories will be read and processed during Jekyll’s build process.

This allows for easier installation and updating as you don't have to manage any of the theme files. To install:

1. Add the following to your `Gemfile`:

   ```ruby
   gem "minimal-mistakes-jekyll"
   ```

2. Fetch and update bundled gems by running the following [Bundler](http://bundler.io/) command:

   ```bash
   bundle
   ```

3. Set the `theme` in your project's Jekyll `_config.yml` file:

   ```yaml
   theme: minimal-mistakes-jekyll
   ```

To update the theme run `bundle update`.

### Remote theme method

Remote themes are similar to Gem-based themes, but do not require `Gemfile` changes or whitelisting making them ideal for sites hosted with GitHub Pages.

To install:

1. Create/replace the contents of your `Gemfile` with the following:

   ```ruby
   source "https://rubygems.org"

   gem "github-pages", group: :jekyll_plugins
   gem "jekyll-include-cache", group: :jekyll_plugins
   ```

2. Add `jekyll-include-cache` to the `plugins` array of your `_config.yml`.

3. Fetch and update bundled gems by running the following [Bundler](http://bundler.io/) command:

   ```bash
   bundle
   ```

4. Add `remote_theme: "mmistakes/minimal-mistakes@4.24.0"` to your `_config.yml` file. Remove any other `theme:` or `remote_theme:` entry.

**Looking for an example?** Use the [Minimal Mistakes remote theme starter](https://github.com/mmistakes/mm-github-pages-starter/generate) for the quickest method of getting a GitHub Pages hosted site up and running. Generate a new repository from the starter, replace sample content with your own, and configure as needed.

## Usage

For detailed instructions on how to configure, customize, add/migrate content, and more read the [theme's documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

---

## Contributing

Found a typo in the documentation or interested in [fixing a bug](https://github.com/mmistakes/minimal-mistakes/issues)? Then by all means [submit an issue](https://github.com/mmistakes/minimal-mistakes/issues/new) or [pull request](https://help.github.com/articles/using-pull-requests/). If this is your first pull request, it may be helpful to read up on the [GitHub Flow](https://guides.github.com/introduction/flow/) first.

For help with using the theme or general Jekyll support questions, please use the [Jekyll Talk forums](https://talk.jekyllrb.com/).

### Pull Requests

When submitting a pull request:

1. Clone the repo.
2. Create a branch off of `master` and give it a meaningful name (e.g. `my-awesome-new-feature`).
3. Open a pull request on GitHub and describe the feature or fix.

Theme documentation and demo pages can be found in the [`/docs`](docs) if submitting improvements, typo corrections, etc.

## Development

To set up your environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000/test/`. This starts a Jekyll server using content in the `test/` directory. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.

---

## Credits

### Creator

**Michael Rose**

- <https://mademistakes.com>
- <https://twitter.com/mmistakes>
- <https://github.com/mmistakes>

### Icons + Demo Images:

- [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain, and [tracy tam](https://thenounproject.com/tracytam)
- [Font Awesome](http://fontawesome.io/)
- [Unsplash](https://unsplash.com/)

### Other:

- [Jekyll](http://jekyllrb.com/)
- [jQuery](http://jquery.com/)
- [Susy](http://susy.oddbird.net/)
- [Breakpoint](http://breakpoint-sass.com/)
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
- [FitVids.JS](http://fitvidsjs.com/)
- [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Gumshoe](https://github.com/cferdinandi/gumshoe)
- [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/)
- [Lunr](http://lunrjs.com)

---

## License

The MIT License (MIT)

Copyright (c) 2013-2020 Michael Rose and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Minimal Mistakes incorporates icons from [The Noun Project](https://thenounproject.com/) 
creators Garrett Knoll, Arthur Shlain, and tracy tam.
Icons are distributed under Creative Commons Attribution 3.0 United States (CC BY 3.0 US).

Minimal Mistakes incorporates [Font Awesome](http://fontawesome.io/),
Copyright (c) 2017 Dave Gandy.
Font Awesome is distributed under the terms of the [SIL OFL 1.1](http://scripts.sil.org/OFL) 
and [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates photographs from [Unsplash](https://unsplash.com).

Minimal Mistakes incorporates [Susy](http://susy.oddbird.net/),
Copyright (c) 2017, Miriam Eric Suzanne.
Susy is distributed under the terms of the [BSD 3-clause "New" or "Revised" License](https://opensource.org/licenses/BSD-3-Clause).

Minimal Mistakes incorporates [Breakpoint](http://breakpoint-sass.com/).
Breakpoint is distributed under the terms of the [MIT/GPL Licenses](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [FitVids.js](https://github.com/davatron5000/FitVids.js/),
Copyright (c) 2013 Dave Rubert and Chris Coyier.
FitVids is distributed under the terms of the [WTFPL License](http://www.wtfpl.net/).

Minimal Mistakes incorporates [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/),
Copyright (c) 2014-2016 Dmitry Semenov, http://dimsemenov.com.
Magnific Popup is distributed under the terms of the MIT License.

Minimal Mistakes incorporates [Smooth Scroll](http://github.com/cferdinandi/smooth-scroll),
Copyright (c) 2019 Chris Ferdinandi.
Smooth Scroll is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Gumshoejs](http://github.com/cferdinandi/gumshoe),
Copyright (c) 2019 Chris Ferdinandi.
Gumshoejs is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/),
Copyright (c) 2010 "Cowboy" Ben Alman.
jQuery throttle / debounce is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav),
Copyright (c) 2015 Luke Jackson.
GreedyNav.js is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Jekyll Group-By-Array](https://github.com/mushishi78/jekyll-group-by-array),
Copyright (c) 2015 Max White <mushishi78@gmail.com>.
Jekyll Group-By-Array is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [@allejo's Pure Liquid Jekyll Table of Contents](https://allejo.io/blog/a-jekyll-toc-in-liquid-only/),
Copyright (c) 2017 Vladimir Jimenez.
Pure Liquid Jekyll Table of Contents is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Lunr](http://lunrjs.com),
Copyright (c) 2018 Oliver Nightingale.
Lunr is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).
=======

**<span style="color:blue;">Bienvenue dans le référentiel d'images Lamidey Noury Medical, mettant en vedette une variété d'outils médicaux de haute qualité. Explorez les différentes catégories ci-dessous pour découvrir les produits disponibles.</span>**


## Table des Matières
<details>
  <summary>Cliquez pour afficher</summary>

- [Adaptateurs](#adaptateurs)
- [Argons](#argons)
- [Câbles](#câbles)
- [Electrodes de Résection](#electrodes-de-résection)
- [Guéridon](#guéridon)
- [Manches](#manches)
- [Pédales](#pédales)
- [Pinces Monopolaires](#pinces-monopolaires)
- [Pinces Bipolaires](#pinces-bipolaires)
- [Plaques](#plaques)
- [Thermoclamp](#thermoclamp)
- [Thermocut](#thermocut)

</details>



## Adaptateurs
***Adaptateurs polyvalents pour différentes applications.***

- **<span class="blue-text">Adaptateur V11KA88</span>**
   
   <img src="V11KA88.jpg" alt="Adaptateur V11KA88" width="200"/>
   
- **<span class="blue-text">Adaptateur V11KA89</span>**
   
   <img src="V11KA89.jpg" alt="Adaptateur V11KA89" width="200"/>
   
- **<span class="blue-text">Adaptateur V11KA91</span>**
   
   <img src="V11KA91.jpg" alt="Adaptateur V11KA91" width="200"/>
   
- **<span class="blue-text">Adaptateur V11KA92</span>**
   
   <img src="V11KA92.jpg" alt="Adaptateur V11KA92" width="200"/>
   
- **<span class="blue-text">Adaptateur V11KA94</span>**
    
   <img src="V11KA94.jpg" alt="Adaptateur V11KA94" width="200"/>
   
- **<span class="blue-text">Adaptateur V11KA98</span>**
    
   <img src="V11KA98.JPG" alt="Adaptateur V11KA98" width="75"/>



## Argons
***Conçu pour une administration efficace d'argon médical.***

- **<span class="blue-text">Argon V11A201</span>**
   
   <img src="V11A201.jpg" alt="Argon V11A201" width="200"/>

- **<span class="blue-text">Argon V11A301</span>**
   
   <img src="V11A301.JPG" alt="Argon V11A301" width="200"/>

- **<span class="blue-text">Argon V11A302</span>**
   
   <img src="V11A302.JPG" alt="Argon V11A302" width="200"/>

- **<span class="blue-text">Argon V11A303</span>**
   
   <img src="V11A303.jpg" alt="Argon V11A303" width="200"/>

- **<span class="blue-text">Argon V11A312</span>**
   
   <img src="V11A312.jpg" alt="Argon V11A312" width="200"/>

- **<span class="blue-text">Argon V11A313</span>**
   
   <img src="V11A313.JPG" alt="Argon V11A313" width="200"/>

- **<span class="blue-text">Argon V11A400</span>**
   
   <img src="V11A400.jpg" alt="Argon V11A400" width="200"/>

- **<span class="blue-text">Argon V11A401</span>**
   
   <img src="V11A401.jpg" alt="Argon V11A401" width="200"/>

- **<span class="blue-text">Argon V11A402</span>**
   
   <img src="V11A402.jpg" alt="Argon V11A402" width="200"/>

- **<span class="blue-text">Argon V11A403</span>**
    
   <img src="V11A403.jpg" alt="Argon V11A403" width="200"/>



## Câbles
***Câbles dotés de connecteurs de qualité pour une transmission optimale.***

- **<span class="blue-text">Câble V11F242-242TC</span>**
   
   <img src="V11F242-242TC.jpg" alt="Câble V11F242-242TC" width="200"/>

- **<span class="blue-text">Câble V11F242</span>**
   
   <img src="V11F242.jpg" alt="Câble V11F242" width="200"/>

- **<span class="blue-text">Câble V11F242C</span>**
   
   <img src="V11F242C.jpg" alt="Câble V11F242C" width="200"/>

- **<span class="blue-text">Câble V11F242E</span>**
   
   <img src="V11F242E.jpg" alt="Câble V11F242E" width="200"/>

- **<span class="blue-text">Câble V11F242TC</span>**
    
   <img src="V11F242TC.jpg" alt="Câble V11F242TC" width="200"/>

- **<span class="blue-text">Câble V11F342</span>**
    
   <img src="V11F342.jpg" alt="Câble V11F342" width="200"/>

- **<span class="blue-text">Câble V11F343</span>**
    
   <img src="V11F343.jpg" alt="Câble V11F343" width="200"/>

- **<span class="blue-text">Câble V11F345</span>**
    
   <img src="V11F345.jpg" alt="Câble V11F345" width="200"/>

- **<span class="blue-text">Câble V11F3AX</span>**
   
   <img src="V11F3AX.JPG" alt="Câble V11F3AX" width="200"/>

- **<span class="blue-text">Câble V11FM40</span>**
    
   <img src="V11FM40.jpg" alt="Câble V11FM40" width="200"/>

- **<span class="blue-text">Câble V11FM40P</span>**
    
   <img src="V11FM40P.jpg" alt="Câble V11FM40P" width="200"/>

- **<span class="blue-text">Câble V11FM43</span>**
    
   <img src="V11FM43.jpg" alt="Câble V11FM43" width="200"/>

- **<span class="blue-text">Câble V11FM44</span>**
    
   <img src="V11FM44.JPG" alt="Câble V11FM44" width="200"/>

- **<span class="blue-text">Câble V12PBS25DM</span>**
    
   <img src="V12PBS25DM.jpg" alt="Câble V12PBS25DM" width="200"/>

- **<span class="blue-text">Câble V12PBS25S</span>**
    
   <img src="V12PBS25S.jpg" alt="Câble V12PBS25S" width="200"/>

- **<span class="blue-text">Câble V12PBS26D</span>**
    
   <img src="V12PBS26D.jpg" alt="Câble V12PBS26D" width="200"/>

- **<span class="blue-text">Câble V12PBS26DM</span>**
    
   <img src="V12PBS26DM.jpg" alt="Câble V12PBS26DM" width="200"/>

- **<span class="blue-text">Câble V12PBS26M</span>**
    
   <img src="V12PBS26M.jpg" alt="Câble V12PBS26M" width="200"/>

- **<span class="blue-text">Câble V12PBS26S</span>**
    
   <img src="V12PBS26S.jpg" alt="Câble V12PBS26S" width="200"/>


## Electrodes de Résection
***Performance fiable pour une résection précise.***

- **<span class="blue-text">Électrode VRU01</span>**
   
   <img src="VRU01.jpg" alt="Électrode VRU01" width="200"/>

- **<span class="blue-text">Électrode VRU011</span>**
   
   <img src="VRU011.jpg" alt="Électrode VRU011" width="200"/>

- **<span class="blue-text">Électrode VRU11</span>**
   
   <img src="VRU11.jpg" alt="Électrode VRU11" width="200"/>

- **<span class="blue-text">Électrode VRU21</span>**
   
   <img src="VRU21.jpg" alt="Électrode VRU21" width="200"/>

- **<span class="blue-text">Électrode VRU31</span>**
    
   <img src="VRU31.jpg" alt="Électrode VRU31" width="200"/>

- **<span class="blue-text">Électrode VRU41</span>**
    
   <img src="VRU41.jpg" alt="Électrode VRU41" width="200"/>

- **<span class="blue-text">Électrode VRUB1</span>**
    
   <img src="VRUB1.jpg" alt="Électrode VRUB1" width="200"/>

- **<span class="blue-text">Électrode VRUN1</span>**
    
   <img src="VRUN1.jpg" alt="Électrode VRUN1" width="200"/>

- **<span class="blue-text">Électrode VRUV1</span>**
    
   <img src="VRUV1.jpg" alt="Électrode VRUV1" width="200"/>


## Electrodes Monopolaires 
### Anses
- **<span class="blue-text">Électrode V11A52C</span>**
   
   <img src="V11A52C.jpg" alt="Électrode V11A52C" width="200"/>

- **<span class="blue-text">Électrode V11A52L</span>**
   
   <img src="V11A52L.jpg" alt="Électrode V11A52L" width="200"/>

- **<span class="blue-text">Électrode V11A52M</span>**
   
   <img src="V11A52M.jpg" alt="Électrode V11A52M" width="200"/>

- **<span class="blue-text">Électrode V11A82C</span>**
   
   <img src="V11A82C.jpg" alt="Électrode V11A82C" width="200"/>

- **<span class="blue-text">Électrode V11A82L</span>**
   
   <img src="V11A82L.jpg" alt="Électrode V11A82L" width="200"/>

- **<span class="blue-text">Électrode V11A82M</span>**
   
   <img src="V11A82M.jpg" alt="Électrode V11A82M" width="200"/>

### Boules
- **<span class="blue-text">Électrode V11B32L</span>**
   
   <img src="V11B32L.jpg" alt="Électrode V11B32L" width="200"/>

- **<span class="blue-text">Électrode V11B32M</span>**
   
   <img src="V11B32M.jpg" alt="Électrode V11B32M" width="200"/>

- **<span class="blue-text">Électrode V11B3CI</span>**
    
   <img src="V11B3CI.jpg" alt="Électrode V11B3CI" width="200"/>

- **<span class="blue-text">Électrode V11B42L</span>**
    
   <img src="V11B42L.jpg" alt="Électrode V11B42L" width="200"/>

- **<span class="blue-text">Électrode V11B42M</span>**

   <img src="V11B42M.jpg" alt="Électrode V11B42M" width="200"/>

- **<span class="blue-text">Électrode V11B4CI</span>**

   <img src="V11B4CI.jpg" alt="Électrode V11B4CI" width="200"/>

### Couteaux

- **<span class="blue-text">Électrode V11CC2L</span>**

   <img src="V11CC2L.jpg" alt="Électrode V11CC2L" width="200"/>

- **<span class="blue-text">Électrode V11CC2M</span>**

   <img src="V11CC2M.jpg" alt="Électrode V11CC2M" width="200"/>

- **<span class="blue-text">Électrode V11CCCI</span>**

   <img src="V11CCCI.jpg" alt="Électrode V11CCCI" width="200"/>

- **<span class="blue-text">Électrode V11CCDI</span>**

   <img src="V11CCDI.jpg" alt="Électrode V11CCDI" width="200"/>

- **<span class="blue-text">Électrode V11CCDTC</span>**

   <img src="V11CCDTC.jpg" alt="Électrode V11CCDTC" width="200"/>

- **<span class="blue-text">Électrode V11CCDTC</span>**

   <img src="V11CCDTC.png" alt="Électrode V11CCDTC" width="200"/>

- **<span class="blue-text">Électrode V11CCDX</span>**

   <img src="V11CCDX.png" alt="Électrode V11CCDX" width="200"/>

- **<span class="blue-text">Électrode V11CD2L</span>**

   <img src="V11CD2L.jpg" alt="Électrode V11CD2L" width="200"/>

### Conisation

- **<span class="blue-text">Électrode V11GCT2</span>**

   <img src="V11GCT2.png" alt="Image V11GCT2" width="200"/>

- **<span class="blue-text">Électrode V11GCT3</span>**

   <img src="V11GCT3.png" alt="Image V11GCT3" width="200"/>

- **<span class="blue-text">Électrode V11GCT4</span>**

   <img src="V11GCT4.png" alt="Image V11GCT4" width="200"/>

- **<span class="blue-text">Électrode V11GCT21</span>**

   <img src="V11GCT21.png" alt="Image V11GCT21" width="200"/>

- **<span class="blue-text">Électrode V11GCT22</span>**

   <img src="V11GCT22.png" alt="Image V11GCT22" width="200"/>

- **<span class="blue-text">Électrode V11GCT31</span>**

   <img src="V11GCT31.png" alt="Image V11GCT31" width="200"/>

- **<span class="blue-text">Électrode V11GCT32</span>**

   <img src="V11GCT32.png" alt="Image V11GCT32" width="200"/>

- **<span class="blue-text">Électrode V11GCT41</span>**

   <img src="V11GCT41.png" alt="Image V11GCT41" width="200"/>

- **<span class="blue-text">Électrode V11GCT42</span>**

   <img src="V11GCT42.png" alt="Image V11GCT42" width="200"/>

### UU

- **<span class="blue-text">Électrode VEUC1</span>**

   <img src="VEUC1.jpg" alt="Image VEUC1" width="200"/>

- **<span class="blue-text">Électrode VEUC2-VEUCL2</span>**

   <img src="VEUC2-VEUCL2.png" alt="Image VEUC2-VEUCL2" width="200"/>

- **<span class="blue-text">Électrode VEUCL1</span>**

   <img src="VEUCL1.JPG" alt="Image VEUCL1" width="200"/>

- **<span class="blue-text">Électrode VEUCL2</span>**

   <img src="VEUCL2.jpg" alt="Image VEUCL2" width="200"/>

- **<span class="blue-text">Électrode VEUT1</span>**

   <img src="VEUT1.jpg" alt="Image VEUT1" width="200"/>

## Guéridon

***Le guéridon V10GALP est un équipement médical essentiel, offrant une surface stable et pratique pour le positionnement d'instruments et de fournitures médicales pendant les procédures.***

- **<span class="blue-text">Guéridon V10GALP</span>**

   <img src="V10GALP.jpg" alt="Guéridon V10GALP" width="200"/>

## Manches

***Découvrez notre gamme de manches ergonomiques conçus pour une utilisation confortable et précise lors d'interventions médicales.***

- **<span class="blue-text">Manche VSUC1</span>**

   <img src="VSUC1.jpg" alt="Manche VSUC1" width="200"/>

- **<span class="blue-text">Manche VSUC15</span>**

   <img src="VSUC15.jpg" alt="Manche VSUC15" width="200"/>

- **<span class="blue-text">Manche VSUC2</span>**

   <img src="VSUC2.jpg" alt="Manche VSUC2" width="200"/>

- **<span class="blue-text">Manche VSUCL1</span>**

   <img src="VSUCL1.jpg" alt="Manche VSUCL1" width="200"/>

- **<span class="blue-text">Manche VSUEC1</span>**

   <img src="VSUEC1.jpg" alt="Manche VSUEC1" width="200"/>
   
- **Manche VSUT1**
  
  <img src="VSUT1.JPG" alt="Manche VSUT1" width="200"/>

- **Manche VSUT2**
  
  <img src="VSUT2.jpg" alt="Manche VSUT2" width="200"/>

- **Manche V11MCT14**
  
  <img src="V11MCT14.jpg" alt="Manche V11MCT14" width="200"/>

- **Manche V11MCT9N**
  
  <img src="V11MCT9N.jpg" alt="Manche V11MCT9N" width="200"/>

## Pédales

***Les pédales V11SM1DN et V11SM2FN offrent un contrôle précis et réactif, facilitant l'activation d'instruments médicaux compatibles.***

- **Pédale V11SM1DN**
  
  <img src="V11SM1DN.jpg" alt="Pédale V11SM1DN" width="200"/>

- **Pédale V11SM2FN**
  
  <img src="V11SM2FN.jpg" alt="Pédale V11SM2FN" width="200"/>

## Pinces Monopolaires

***Découvrez notre sélection de pinces monopolaires offrant des performances fiables pour les procédures médicales.***

- **Pince Monopolaire VPM11D03**
  
  <img src="VPM11D03.jpg" alt="Pince Monopolaire VPM11D03" width="200"/>

- **Pince Monopolaire VPM13C10**
  
  <img src="VPM13C10.jpg" alt="Pince Monopolaire VPM13C10" width="200"/>

- **Pince Monopolaire VPM13D08G**
  
  <img src="VPM13D08G.JPG" alt="Pince Monopolaire VPM13D08G" width="200"/>

- **Pince Monopolaire VPM13D10**
  
  <img src="VPM13D10.jpg" alt="Pince Monopolaire VPM13D10" width="200"/>

- **Pince Monopolaire VPM13D12G**
  
  <img src="VPM13D12G.JPG" alt="Pince Monopolaire VPM13D12G" width="200"/>

- **Pince Monopolaire VPM16B10**
  
  <img src="VPM16B10.jpg" alt="Pince Monopolaire VPM16B10" width="200"/>

- **Pince Monopolaire VPM16C10**
  
  <img src="VPM16C10.jpg" alt="Pince Monopolaire VPM16C10" width="200"/>

- **Pince Monopolaire VPM16D08G**
  
  <img src="VPM16D08G.JPG" alt="Pince Monopolaire VPM16D08G" width="200"/>

- **Pince Monopolaire VPM16D10**
  
  <img src="VPM16D10.jpg" alt="Pince Monopolaire VPM16D10" width="200"/>

- **Pince Monopolaire VPM16D12G**
  
  <img src="VPM16D12G.JPG" alt="Pince Monopolaire VPM16D12G" width="200"/>

- **Pince Monopolaire VPM20B10**
  
  <img src="VPM20B10.jpg" alt="Pince Monopolaire VPM20B10" width="200"/>

- **Pince Monopolaire VPM20D08G**
  
  <img src="VPM20D08G.JPG" alt="Pince Monopolaire VPM20D08G" width="200"/>

- **Pince Monopolaire VPM20D10**
  
  <img src="VPM20D10.jpg" alt="Pince Monopolaire VPM20D10" width="200"/>

- **Pince Monopolaire VPM20D12G**
  
  <img src="VPM20D12G.JPG" alt="Pince Monopolaire VPM20D12G" width="200"/>

- **Pince Monopolaire VPM22C10**
  
  <img src="VPM22C10.jpg" alt="Pince Monopolaire VPM22C10" width="200"/>

- **Pince Monopolaire VPM22C20**
  
  <img src="VPM22C20.JPG" alt="Pince Monopolaire VPM22C20" width="200"/>

- **Pince Monopolaire VPM22D10**
  
  <img src="VPM22D10.jpg" alt="Pince Monopolaire VPM22D10" width="200"/>

- **Pince Monopolaire VPM22D25**
  
  <img src="VPM22D25.JPG" alt="Pince Monopolaire VPM22D25" width="200"/>

- **Pince Monopolaire VPMC20C10**
  
  <img src="VPMC20C10.jpg" alt="Pince Monopolaire VPMC20C10" width="200"/>

- **Pince Monopolaire VPMS16D10**
  
  <img src="VPMS16D10.JPG" alt="Pince Monopolaire VPMS16D10" width="200"/>

- **Pince Monopolaire VPMS20D10**
  
  <img src="VPMS20D10.JPG" alt="Pince Monopolaire VPMS20D10" width="200"/>

## Pinces Bipolaires

***Découvrez notre gamme de pinces bipolaires, conçues pour assurer une coagulation efficace avec une précision optimale.***

- **<span class="blue-text">Pince Bipolaire VPB11C05</span>**
  
  <img src="VPB11C05.jpg" alt="Pince Bipolaire VPB11C05" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB11D03</span>**
  
  <img src="VPB11D03.JPG" alt="Pince Bipolaire VPB11D03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB11D05</span>**
  
  <img src="VPB11D05.jpg" alt="Pince Bipolaire VPB11D05" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB11D10</span>**
  
  <img src="VPB11D10.JPG" alt="Pince Bipolaire VPB11D10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB13C03</span>**
  
  <img src="VPB13C03.jpg" alt="Pince Bipolaire VPB13C03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB13D05</span>**
  
  <img src="VPB13D05.jpg" alt="Pince Bipolaire VPB13D05" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB16B05</span>**
  
  <img src="VPB16B05.JPG" alt="Pince Bipolaire VPB16B05" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB16B10</span>**
  
  <img src="VPB16B10.JPG" alt="Pince Bipolaire VPB16B10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB16C10</span>**
  
  <img src="VPB16C10.jpg" alt="Pince Bipolaire VPB16C10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB16D03</span>**
  
  <img src="VPB16D03.jpg" alt="Pince Bipolaire VPB16D03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB18C05</span>**
  
  <img src="VPB18C05.jpg" alt="Pince Bipolaire VPB18C05" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB18C10</span>**
  
  <img src="VPB18C10.JPG" alt="Pince Bipolaire VPB18C10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB18D03</span>**
  
  <img src="VPB18D03.jpg" alt="Pince Bipolaire VPB18D03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB18D10</span>**
  
  <img src="VPB18D10.JPG" alt="Pince Bipolaire VPB18D10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB18D20</span>**
  
  <img src="VPB18D20.JPG" alt="Pince Bipolaire VPB18D20" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20AR10</span>**
  
  <img src="VPB20AR10.jpg" alt="Pince Bipolaire VPB20AR10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20AV10</span>**
  
  <img src="VPB20AV10.jpg" alt="Pince Bipolaire VPB20AV10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20B03</span>**
  
  <img src="VPB20B03.JPG" alt="Pince Bipolaire VPB20B03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20B20</span>**
  
  <img src="VPB20B20.jpg" alt="Pince Bipolaire VPB20B20" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20C10</span>**
  
  <img src="VPB20C10.jpg" alt="Pince Bipolaire VPB20C10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20C20</span>**
  
  <img src="VPB20C20.JPG" alt="Pince Bipolaire VPB20C20" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20D03</span>**
  
  <img src="VPB20D03.JPG" alt="Pince Bipolaire VPB20D03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20D10</span>**
  
  <img src="VPB20D10.jpg" alt="Pince Bipolaire VPB20D10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB20D20</span>**
  
  <img src="VPB20D20.JPG" alt="Pince Bipolaire VPB20D20" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB22B03</span>**
  
  <img src="VPB22B03.JPG" alt="Pince Bipolaire VPB22B03" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB22B10</span>**
  
  <img src="VPB22B10.jpg" alt="Pince Bipolaire VPB22B10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB22C10</span>**
  
  <img src="VPB22C10.jpg" alt="Pince Bipolaire VPB22C10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB22C20</span>**
  
  <img src="VPB22C20.JPG" alt="Pince Bipolaire VPB22C20" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB22D10</span>**
  
  <img src="VPB22D10.jpg" alt="Pince Bipolaire VPB22D10" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB22D20</span>**
  
  <img src="VPB22D20.JPG" alt="Pince Bipolaire VPB22D20" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB25B05-bis</span>**
  
  <img src="VPB25B05-bis.JPG" alt="Pince Bipolaire VPB25B05-bis" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB25B05</span>**
  
  <img src="VPB25B05.jpg" alt="Pince Bipolaire VPB25B05" width="200"/>

- **<span class="blue-text">Pince Bipolaire VPB25D10</span>**
  
  <img src="VPB25D10.JPG" alt="Pince Bipolaire VPB25D10" width="200"/>

## Plaques

***Nos plaques offrent une interface sûre et fiable pour les procédures électrochirurgicales, assurant une dispersion efficace du courant électrique.***

- **<span class="blue-text">Plaque VPLEN2</span>**
  
  <img src="VPLEN2.jpg" alt="Plaque VPLEN2" width="200"/>

- **<span class="blue-text">Plaque VPLAD2</span>**
  
  <img src="VPLAD2.jpg" alt="Plaque VPLAD2" width="200"/>

- **<span class="blue-text">Plaque V11IS1C</span>**
  
  <img src="V11IS1C.png" alt="Plaque V11IS1C" width="200"/>

- **<span class="blue-text">Connecteur V11K250</span>**
  
  <img src="V11K250.jpg" alt="Connecteur V11K250" width="200"/>

## Thermoclamp

   ***Les thermoclamps offrent un contrôle thermique précis lors des interventions chirurgicales, assurant la sécurité du patient et du personnel médical.***

- **<span class="blue-text">Thermoclamp V11CLPBS2</span>**
  
  <img src="V11CLPBS2.jpg" alt="Thermoclamp V11CLPBS2" width="200"/>

- **<span class="blue-text">Thermoclamp V11CLPBS4</span>**
  
  <img src="V11CLPBS4.jpg" alt="Thermoclamp V11CLPBS4" width="200"/>

- **<span class="blue-text">Thermoclamp V11CLPBS6</span>**
  
  <img src="V11CLPBS6.JPG" alt="Thermoclamp V11CLPBS6" width="200"/>

- **<span class="blue-text">Thermoclamp V11CLPBS62</span>**
  
  <img src="V11CLPBS62.JPG" alt="Thermoclamp V11CLPBS62" width="200"/>

## Thermocut

***Le Thermocut est conçu pour fournir des résultats fiables et une coagulation efficace, assurant la sécurité du patient et du personnel médical.***

- **<span class="blue-text">Thermocut V12PBN211</span>**
  
  <img src="V12PBN211.JPG" alt="Thermocut V12PBN211" width="200"/>

- **<span class="blue-text">Thermocut V12PBN21P</span>**
  
  <img src="V12PBN21P.jpg" alt="Thermocut V12PBN21P" width="200"/>

- **<span class="blue-text">Thermocut V12PBN21R</span>**
  
  <img src="V12PBN21R.jpg" alt="Thermocut V12PBN21R" width="200"/>

- **<span class="blue-text">Thermocut V12PBN221</span>**
  
  <img src="V12PBN221.JPG" alt="Thermocut V12PBN221" width="200"/>

- **<span class="blue-text">Thermocut V12PBN22P</span>**
  
  <img src="V12PBN22P.jpg" alt="Thermocut V12PBN22P" width="200"/>

- **<span class="blue-text">Thermocut V12PBN22R</span>**
  
  <img src="V12PBN22R.jpg" alt="Thermocut V12PBN22R" width="200"/>

- **<span class="blue-text">Thermocut V12PBN2S</span>**
  
  <img src="V12PBN2S.jpg" alt="Thermocut V12PBN2S" width="200"/>

- **<span class="blue-text">Thermocut V12PBN52</span>**
  
  <img src="V12PBN52.jpg" alt="Thermocut V12PBN52" width="200"/>

- **<span class="blue-text">Thermocut V12PBN521R</span>**
  
  <img src="V12PBN521R.jpg" alt="Thermocut V12PBN521R" width="200"/>

- **<span class="blue-text">Thermocut V12PBN522R</span>**
  
  <img src="V12PBN522R.JPG" alt="Thermocut V12PBN522R" width="200"/>

- **<span class="blue-text">Thermocut V12PBN523</span>**
  
  <img src="V12PBN523.jpg" alt="Thermocut V12PBN523" width="200"/>

- **<span class="blue-text">Thermocut V12PBN5230</span>**
  
  <img src="V12PBN5230.jpg" alt="Thermocut V12PBN5230" width="200"/>

- **<span class="blue-text">Thermocut V12PBN524</span>**
  
  <img src="V12PBN524.jpg" alt="Thermocut V12PBN524" width="200"/>

- **<span class="blue-text">Thermocut V12PBN5240</span>**
  
  <img src="V12PBN5240.jpg" alt="Thermocut V12PBN5240" width="200"/>

- **<span class="blue-text">Thermocut V12PBS210</span>**
  
  <img src="V12PBS210.JPG" alt="Thermocut V12PBS210" width="200"/>

- **<span class="blue-text">Thermocut V12PBS220</span>**
  
  <img src="V12PBS220.JPG" alt="Thermocut V12PBS220" width="200"/>

- **<span class="blue-text">Thermocut V12PBS25DM</span>**
  
  <img src="V12PBS25DM.jpg" alt="Thermocut V12PBS25DM" width="200"/>

- **<span class="blue-text">Thermocut V12PBS25S</span>**
  
  <img src="V12PBS25S.jpg" alt="Thermocut V12PBS25S" width="200"/>

- **<span class="blue-text">Thermocut V12PBS26D</span>**
  
  <img src="V12PBS26D.jpg" alt="Thermocut V12PBS26D" width="200"/>

- **<span class="blue-text">Thermocut V12PBS26DM</span>**
  
  <img src="V12PBS26DM.jpg" alt="Thermocut V12PBS26DM" width="200"/>

- **<span class="blue-text">Thermocut V12PBS26M</span>**
  
  <img src="V12PBS26M.jpg" alt="Thermocut V12PBS26M" width="200"/>

- **<span class="blue-text">Thermocut V12PBS26S</span>**
  
  <img src="V12PBS26S.jpg" alt="Thermocut V12PBS26S" width="200"/>




## Fiches technique

<details>
  <summary>Cliquez pour afficher</summary>

### Adaptateurs
- [Adaptateurs](FT-Adaptateurs-210521_FR.pdf)

### Argons
- [Argons](FT-module_Argon-0822-FR.pdf)

### Câbles
- [Câbles](FT-Cables-210521_FR.pdf)

### Electrodes de Résection
- [Electrodes de Résection](FT-Electrode_gyneco_conisation-221006_FR.pdf)
- [Electrodes de Résection](FT-Electrode_aiguille_FR-200827.pdf)
- [Electrodes de Résection](FT-Electrode_anses_FR-200827.pdf)
- [Electrodes de Résection](FT-Electrode_boules_FR-201007.pdf)
- [Electrodes de Résection](FT-Electrode_couteaux_FR-201007.pdf)

### Anses
- [Anses](FT-anse_FRONT_LOAD_FR-220623.pdf)
- [Anses](FT-anse_Gynecare_FR-210812.pdf)
- [Anses](FT-anse_Reutilisable_FR-210812.pdf)
- [Anses](FT-anse_SIDE_LOAD_FR-220210.pdf)
- [Anses](FT-anse_Universelle_FR-220210.pdf)

### Manches
- [Manches](FT-manche_Derlec_FR-200720.pdf)
- [Manches](FT-manche_Tactilec_FR-200720.pdf)

### Pédales
- [Pédales](FT-Pédales_04_2019.pdf)

### Pinces Monopolaires
- [Pinces Monopolaires](Pinces_monopolaires_FT_0105_FR.pdf)

### Pinces Bipolaires
- [Pinces Bipolaires](FT-Pince_bipolaire_coudee-210129-FR.pdf)
- [Pinces Bipolaires](FT-Pince_bipolaire_droite-210129-FR.pdf)
- [Pinces Bipolaires](FT-Pinces_bipol_baionnettes-200828-FR.pdf)

### Plaques
- [Plaques](FT_Lames_Thermocut_FR.pdf)
- [Plaques](Thermocut5_FT_0722-FR.pdf)
- [Plaques](Thermocut10_FT-0722-FR.pdf)

### Thermoclamp
- [Thermoclamp](Pince_thermoclamp_et_Thermocision-FT_211116-FR.pdf)

### Thermocut
- [Thermocut](FT-Set_V11ELDI_FR-210202.pdf)
- [Thermocut](FT-Lames_Thermocut_FR.pdf)
- [Thermocut](Thermocut5_FT_0722-FR.pdf)
- [Thermocut](Thermocut10_FT-0722-FR.pdf)

</details>



## Crédits
Nous remercions les contributeurs suivants pour leur précieuse contribution à ce projet :
- [Mathéo NIGAUD CEBRON](https://github.com/adv2lnm)

## Mises à jour
Consultez la section [CHANGELOG.md](CHANGELOG.md) pour les dernières mises à jour et modifications apportées au projet.

## Support
Besoin d'aide ou avez-vous trouvé un problème ? Soumettez une demande d'assistance sur notre [page de support](https://lamidey-noury.com/) ou signalez un problème sur le courriel suivant: [mail de support](adv2@lamidey-noury.fr).
>>>>>>> f8a5c0f33c32d9f19cb03b2404022322a5ddd027
>>>>>>> 9308314e191cb4e9e1b4b6c494a86189615ed2bf
