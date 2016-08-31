# vscode_helpers
Files for Visual Studio setup

# Files

* rvm_launch.json
* rvm_chef_launch.json

Logged issue https://github.com/Microsoft/vscode/issues/11337 to see if these can be more reusable.

For these to work on a Ruby project you must first run these commands on the project:

    bundle install –binstubs
    bundle install --path vendor

A .gitignore is provided for the resultant files, however the `bin/` is likely tricky and may not be what you want.

A Gemfile is also provided for gems you will need to include for debugging.

