
## Technical Details

This site is compiled from [Markdown](https://help.github.com/articles/github-flavored-markdown "Link to More Information About Markdown") files using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). To propose a specific change, you can submit a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") with your change to one of these source Markdown files. The Plays from the Playbook are [available in the `_plays` folder](https://github.com/WhiteHouse/playbook/tree/gh-pages/_plays "Link to the Plays Markdown files"), while the [TechFAR is contained in this markdown file](https://github.com/WhiteHouse/playbook/blob/gh-pages/_includes/techfar-online.md "Link to the TechFAR Markdown File").

You can also use Github's in-browser editing feature to make an edit to one of these Markdown files and submit your change for consideration without needing to install any additional software.

### Running the Site Locally

To run the site locally on your own computer (most helpful for previewing your own changes), you will need to install Jekyll and other dependencies:

If you don't already have Ruby and Bundler installed, follow [the first two steps in these Jekyll installation instructions](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll "Installation instructions for Jekyll").

Next, [fork this repository](http://help.github.com/fork-a-repo/ "Instructions for Forking Your Repository") and clone it on your computer.

Navigate to the folder on your computer, and run the command `$ bundle install` at the command line prompt.

To run the site locally, run `jekyll serve --watch`, then visit `http://localhost:4000/` in your browser to preview the site.

### Editing the Stylesheets

This project uses [Sass](http://sass-lang.com/ "Link to Learn More About Sass") for managing its style sheets. If you would like to make changes to the site's styles, you should edit the `assets/sass/styles.css.scss` file. 
**Do not** make changes to the `styles.css` file directly, as this file is auto-generated from the `styles.css.scss` file.

To compile changes in the `styles.css.scss` Sass file into a new `styles.css` file, you can run: `$ sass --watch assets/sass/styles.css.scss:assets/css/styles.css`. This command will watch for any changes you make to the Sass file and automatically update the CSS file, making it easy to check your work when you are running the site locally (see above).

## License
As a work of the United States Government, this project is in the public domain within the United States.

Additionally, we waive copyright and related rights in the work worldwide through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
