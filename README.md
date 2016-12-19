# SmartHome Bot - 1st Prize Winner of Microsoft Botathan 1.0
# Inspiration
Urban areas are increasing worldwide and more than 70% of the world population will be located in urban centers by 2050. This growth leads to an increase in number, and density of buildings. It is also interesting to note that people spend about 87% of their time indoors. In 2014, buildings consume more than 70% of the total electricity consumption in United states. This significant share demonstrates the importance of using automation strategies that result in more energy efficient operation of the service systems in buildings (e.g., lighting systems, appliances, and HVAC).

# What it does
It controls and monitors devices in a smart home via Skype and Kik. Intelligent bot can interact with user users wherever they are. In contrast to existing automation technologies that offer fixed template to control home devices or require the user access to control devices, our project is capable of naturally understanding the users' needs wherever they are.

# How we built it
First, we made the base framework using Microsoft Bot. Next, we started with LUIS, as it is critical to the whole idea of using Natural Language. After building the language module independently, we integrated the bot with the LUIS module. Then we used the Skype channel, so the interaction with the bot can be done over Skype instead of the console window.

# What's next for Smart HomeBot
We are planning to extend are project to include more control capabilities, such as HVAC control, window blinds control, and door control. Also the Smart HomeBot will provide the user with information about the electricity consumption of the devices, indoor temperature and occupancy status. Finally, the Smart HomeBot will offer the user with recommendations for saving more energy.

# The Modernist theme

[![Build Status](https://travis-ci.org/pages-themes/modernist.svg?branch=master)](https://travis-ci.org/pages-themes/modernist) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-modernist.svg)](https://badge.fury.io/rb/jekyll-theme-modernist)

*Modernist is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/modernist), or even [use it today](#usage).*

![Thumbnail of modernist](thumbnail.png)

## Usage

To use the Modernist theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-modernist
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```



## Customizing

### Configuration variables

Modernist will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.css` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/modernist/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

## Roadmap

See the [open issues](https://github.com/pagse-themes/modernist/issues) for a list of proposed features (and known issues).

## Project philosophy

The Modernist theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Modernist? We'd love your help. Modernist is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/modernist`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
