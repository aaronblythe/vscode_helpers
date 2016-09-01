# vscode_helpers
Files for Visual Studio setup

# Files

* rvm_launch.json
* rvm_chef_launch.json

# Usage

For these to work on a Ruby project you must first run these commands on the project:

    bundle install –binstubs --path binstubs
    bundle install --path vendor

A .gitignore is provided for the resultant files.

A Gemfile is also provided for gems you will need to include for debugging.

Since vendoring is used, it may be useful to run:

    bundle clean
