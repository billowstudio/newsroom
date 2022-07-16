# The newsroom theme

Newsroom is a Jekyll theme. You can preview the theme to see what it looks like, or even use it today.


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "newsroom"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: newsroom
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install newsroom

### Customizing

### Configuration variables

Newsroom will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Customizing Google Analytics code

Google has released several iterations to their Google Analytics code over the years since this theme was first created. If you would like to take advantage of the latest code, paste it into `_includes/google-analytics.html` in your Jekyll site.

## Project philosophy

Newsroom theme is intended to make it quick and easy for Jekyll users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

