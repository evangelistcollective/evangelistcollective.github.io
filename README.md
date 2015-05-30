# evangelistcollective.github.io
Evangelist Collective Homepage

The Evangelist Collective is a collaborative effort of friendly people who want to empower each other to build a stronger, more inclusive community. For the full schpeel, [read about the project](https://github.com/evangelistcollective/getting-started).

## Contributing

Pull Requests are more than welcome as we coordinate efforts. Here are a few notes to help you along.

### Editing The Site

Some base content lives in `_config.yml` like the data from header and footer. If you want to add or remove a section of the page, you can do so from `_layouts/default.html`. Each section that Jekyll renders is outlined there in a reasonably readable way. You can see the associated content of that section in the `_includes/css/` folder.

For example, this section from `_layouts/default.html`:

     {% include portfolio_grid.html %}

Loads the content defined in `_includes/css/portfolio_grid.html`. Which is pretty nifty. You can edit our site without knowing more than a little HTML. 

Other things you'll want to know: 

* Our fonts are loaded from `head.html`
* The description under our logo is from `header.html`
* The About section loads from `about.html`

The portfolio is a little tricky: images are automatically loaded from the `img/portfolio` folder. The page that loads is in `_posts`. The mapping of image to post happens in the `_posts` markdown. This all renders thanks to the `modals.html` file which I haven't found a good reason to want to edit. 

## Credits 

We rock a [MIT License]([LICENSE]). The Jekyll theme is [Freelancer](http://jekyllthemes.org/themes/freelancer/) and icons are from designers on [The Noun Project](http://thenounproject.com). [Matt Brender](http://github.com/mjbrender) made the site.
