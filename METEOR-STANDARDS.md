# Differential Meteor Coding Styles

## Coding Style

* Use soft-tabs with a two space indent.
* Keep lines fewer than 80 characters.
* Never leave trailing whitespace.
* Use spaces around operators, after commas, colons and semicolons, around ````{```` and before ````}````.

## File Structure

* Break everything into client, server, or collection folders
* Client should have folders: compatibility, helpers, stylesheets, and views
* Views should be broken out by a folder matching a path in the Iron Router mappings

##### Router.coffee
````
  @route 'vlogger',
    path: '/vloggers/:_id'

````

##### Folder structure
````
client
     └── views
             └── vloggers
                        └── vlogger.html

````
