![Travis CI Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)

_s
===

Hi. I'm a starter theme called `_s`, or `underscores`, if you like. I'm a theme meant for hacking so don't use me as a Parent Theme. Instead try turning me into the next, most awesome, WordPress theme out there. That's what I'm here for.

My ultra-minimal CSS might make me look like theme tartare but that means less stuff to get in your way when you're designing your awesome theme. Here are some of the other more interesting things you'll find here:

* A just right amount of lean, well-commented, modern, HTML5 templates.
* A helpful 404 template.
* A sample custom header implementation in `inc/custom-header.php` that can be activated by uncommenting one line in `functions.php` and adding the code snippet found in the comments of `inc/custom-header.php` to your `header.php` template.
* Custom template tags in `inc/template-tags.php` that keep your templates clean and neat and prevent code duplication.
* Some small tweaks in `inc/extras.php` that can improve your theming experience.
* A script at `js/navigation.js` that makes your menu a toggled dropdown on small screens (like your phone), ready for CSS artistry. It's enqueued in `functions.php`.
* 2 sample CSS layouts in `layouts/` for a sidebar on either side of your content.
* Smartly organized starter CSS in `style.css` that will help you to quickly get your design off the ground.
* Licensed under GPLv2 or later. :) Use it to make something cool.

Getting Started
---------------

If you want to keep it simple, head over to http://underscores.me and generate your `_s` based theme from there. You just input the name of the theme you want to create, click the "Generate" button, and you get your ready-to-awesomize starter theme.

If you want to set things up manually, download `_s` from GitHub. The first thing you want to do is copy the `_s` directory and change the name to something else (like, say, `megatherium`), and then you'll need to do a five-step find and replace on the name in all the templates.

1. Search for `'_s'` (inside single quotations) to capture the text domain.
2. Search for `_s_` to capture all the function names.
3. Search for `Text Domain: _s` in style.css.
4. Search for <code>&nbsp;_s</code> (with a space before it) to capture DocBlocks.
5. Search for `_s-` to capture prefixed handles.

OR

* Search for: `'_s'` and replace with: `'megatherium'`
* Search for: `_s_` and replace with: `megatherium_`
* Search for: `Text Domain: _s` and replace with: `Text Domain: megatherium` in style.css.
* Search for: <code>&nbsp;_s</code> and replace with: <code>&nbsp;Megatherium</code>
* Search for: `_s-` and replace with: `megatherium-`

Then, update the stylesheet header in `style.css` and the links in `footer.php` with your own information. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say, but harder to do: make an awesome WordPress theme. :)

Good luck!


<hr>
**Warning:** I plumbed this together for my own personal use. Don't yell at me.
<hr>

![wp_smithett-screenshot](https://f.cloud.github.com/assets/436120/2468396/4b92cd2e-afd7-11e3-9964-2863731e0ee5.jpg)

WP Smithett
===========

**WP Smithett** is a mobile-first, responsive WordPress starter template made with Automattic's [Underscores](http://underscores.me) and Ben Smithett's [Style](https://github.com/bensmithett/style). It's named after [Ben](http://bensmithett.com/) because I stole all his work.

You'll need to be somewhat familiar with [Compass](http://compass-style.org/), [Sass](http://sass-lang.com/), and [Susy](http://susy.oddbird.net/) to get the most out of WP Smithett. [Ruby](https://www.ruby-lang.org/en/) is required for developing with this framework — if you're using a Mac though, it should Just Work™.

Oh — knowing about [SMACSS](http://smacss.com/) is also really good.

### Getting started
* Clone this repository or download the archive and put it in your `/wp-content/themes/` directory (don't forget to unzip it).
* Open a new Terminal window and: `$ cd wherever/you/put/it/wp-content/themes/wp_smithett`.
* All the dependencies are included in `Gemfile`, so go ahead and `$ gem install bundler && bundle install`.
* Use `$ compass watch` or `$ compass compile` while you work inside the `stylesheets` directory — everything gets compiled into `style.css`.
* Make something great!


### With WP Smithett you can...
* Make a website for your favourite client!
* Start a blog!
* (Probably) make a theme to sell on [ThemeForest](http://themeforest.net)!
* Print it out to impress friends!
* And many more!