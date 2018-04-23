# sprout-sprout

My version of a [Sprout](https://github.com/carrot/sprout) template to create sprout templates.

## Overview

This template provides a good starting point for a Sprout template. The templates generated from
this template supports creating a git repository, adding a license, and is pre-configured for
dumping some basic files into the target repository (like .editorconfig and .gitignore files). Other
files can simply be added to the "root" folder as needed. Other customizations can be done by
editing the provided init.js file.

## GitHub use

During execution of this template it can automatically pull some information to assist with the
information needed. In order for this to work you should have an environment variable called
GITHUB_TOKEN that has a token to be used to authenticate to the GitHub API. Without that the
template will still work but you will likely need to fill in more of the prompts than would
otherwise be necessary.

## License

Apache-2.0 © 2018 [Brennan Fee](https://github.com/brennanfee)
