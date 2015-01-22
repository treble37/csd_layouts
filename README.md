# csd_layouts
experimental layouts with the clinical studies directory

##Gemfile needs to look like this:
````
gem 'compass', '~> 1.0.3'
gem 'susy', '~> 2.2.1'
````

compass create --using susy <project_name>


*********************************************************************
Congratulations! Your compass project has been created.

You may now add and edit sass stylesheets in the sass subdirectory of
your project.

Sass files beginning with an underscore are called partials and won't be
compiled to CSS, but they can be imported into other sass stylesheets.

You can configure your project by editing the config.rb configuration
file.

You must compile your sass stylesheets into CSS when they change.
This can be done in one of the following ways:
  1. To compile on demand:
     compass compile [path/to/project]
  2. To monitor your project for changes and automatically recompile:
     compass watch [path/to/project]

More Resources:
  * Website: http://compass-style.org/
  * Sass: http://sass-lang.com
  * Community: http://groups.google.com/group/compass-users/


Welcome to Susy! Check out the full documentation online:

    http://susy.oddbird.net/

To import your new stylesheets add the following lines of HTML (or
equivalent) to your webpage:
<head>
  <link href="/stylesheets/style.css" rel="stylesheet" type="text/css"
/>
</head>

