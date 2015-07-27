# Meteor Factory
A guide for writing awesome Meteor apps

## Language ##
Languages of choice are CoffeeScript, LESS and HTML.

Use two spaces instead of tabs.

### CoffeeScript ###
* [CoffeeScript style guide](https://github.com/polarmobile/coffeescript-style-guide)

### LESS ###
* Use import files e.g. `profile.import.less` whenever possible and import into a `main.less` file e.g. [meteor-starter](https://github.com/yogiben/meteor-starter/blob/master/client/style/main.less)
* Less files specific to a template should be placed in the same folder as the template named `template_name.import.less`

### HTML ###
* Templates should have `class="template-admin-dashboard"' on the top node. This is for styling and easily finding the right file.
* `{{> profile}}` not `{{>profile}}`
* Use `js-` e.g. `class="js-activate-account"` when a class is just used for a click event OR
* Use `data-ACTION_NAME` e.g. `data-popup-message="Log in to do post a comment"`

## Project Structure ##
Project structure is not fixed, but [meteor-starter](https://github.com/yogiben/meteor-starter) is a good example.

### Naming Conventions ###
* Filenames and folder names `separated_with_underscore.json`
* Code is always written in English e.g. #your-tab instead of #deine-tab
* Links should only be hyphenated e.g. `/edit-profile` not `/editProfile` or `/edit_profile`

## Git ##
* Use Git flow, making feature branches and merging when ready
* The default branch of the repo should be `develop`
* When the app reaches production, `release` branches should be used

## Preferred Approach / Packages ##
* Typically try to use [Collection2](https://github.com/aldeed/meteor-collection2) to add a schema to data
* Use [Collection Helpers](https://github.com/dburles/meteor-collection-helpers) and [Collection Hooks](https://github.com/matb33/meteor-collection-hooks)
