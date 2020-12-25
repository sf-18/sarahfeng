website

### Social media links
To add links to your social sites (linkedin, twitter, etc) below the bio, create a file named `social.yml` in your `_data` folder (which you may not have created yet). Inside it, follow the following format:

```yaml
- title: Twitter
  url: http://twitter.com/lllychen
- title: Github
  url: http://github.com/lllychen/louie
# and so on...
```

### Column names
The names for each column is defaulted to `Title`, `Date`, and `Category`, respectively. However, this can be changed according to use cases. For instance, an archive of classic literature may need to adjust accordingly:

```yaml
post_title: Story
post_date: Year
post_cat: Genre
```

### Date format
The default format for dates is `%b %-d, %Y`, which outputs `Jan 1, 2017`. However, you can customize it according to [this](http://jekyll.tips/jekyll-casts/date-formatting/#date) in `_config.yml` such as follows:

```yaml
date_format: "%m/%d/%Y"
```

### Post variables
You can include the following variables in the front matter for posts:

```yaml
title:  Berry Perfume
category: Narrative
img: [ OPTIONAL: url or path in directory ]
```

The `img` variable is used to produce a randomly placed image associated with this post when you hover over it. If you omit it, there simply won't be a picture and all is still well.

If you prefer not to have the category in your post permalink, follow the guidelines [here](https://jekyllrb.com/docs/permalinks/) to remove it among other configurations.

### Post pagination
To include previous and next links at the bottom of a post page, leave the following setting to `true`. Otherwise, change to `false`.

```yaml
prev-next: true
```

## License
The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Credit
Stories created and collected by [Story Bytes](http://www.storybytes.com/view-length/0256-words/index-0256.html).

Images collected by [Unsplash](https://unsplash.com/)
