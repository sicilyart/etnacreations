# Etna Creations Website Instructions

## Requirement if on a new computer
- Install hugo from http://gohugo.io
- Install git from http://git-scm.com
- Run git bash
- Get source code with command `git clone https://github.com/sicilyart/etnacreations.git`
- Enter the site folder with command `cd etnacreations`
- Checkout the theme with command `git submodule init`
- and them `git submodule update`


## To Make changes
- Full sized images go into folder `static/images/fulls` and should be maximum 840px
- Thumbnail images go into folder `static/images/thumbs` and should be maximum 320px
- Update english and italian text and configuration in `config.toml` file
- Etsy store code should be put into file `layouts/partials/recent-posts.html`

## To Test changes
- Run command `hugo server`
- In a web browser visit http://localhost:1313/ and check your changes

## To deploy
- Run command `hugo` to generate the static site
- Save the changes with `git commit -am "Description of changes"`
- Deploy live with `git push`