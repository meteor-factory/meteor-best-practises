# Meteor Factory
A guide for writing awesome Meteor apps

## Language ##
Languages of choice are CoffeeScript, LESS and HTML.

### CoffeeScript ###
* [CoffeeScript style guide](https://github.com/polarmobile/coffeescript-style-guide)

### LESS ###
* Use import files e.g. `profile.import.less` whenever possible and import into a `main.less` file e.g. [meteor-starter](https://github.com/yogiben/meteor-starter/blob/master/client/style/main.less)
* Less files specific to a template should be placed in the same folder as the template named `template_name.import.less`

### HTML ###
* Templates should have `class="template-admin-dashboard"' on the top node. This is for styling and easily finding the right file.
* `{{> profile}}` not `{{>profile}}`

## Project Structure ##
Project structure is not fixed, but [meteor-starter](https://github.com/yogiben/meteor-starter) is a good example.

### Naming Conventions ###
* Filenames and folder names `separated_with_underscore.json`
* Code is always written in English e.g. #your-tab instead of #deine-tab
* Links should only be hyphenated e.g. `/edit-profile` not `/editProfile` or `/edit_profile`
