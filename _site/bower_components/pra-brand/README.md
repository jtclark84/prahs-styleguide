# PRA Web Branding 

## Dependencies

The pra-brand theme depends on these other project:

* [bootstrap-scss](https://github.com/twbs/bootstrap-sass)
* [jquery](https://github.com/jquery/jquery)

If you install pra-brand using Bower, you will get these dependencies at
the same time. If not using Bower, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

The recommended installation method is Bower, but you can install the project via a Git Submodule, or copy and paste.

### Install using Bower:

If you already have an existing `bower.json` file, run the following command:

    $ bower install --save pra-brand

Otherwise, create a bower project. If you are not sure what to enter in the prompts, use the default values (by hitting return):

    $ bower init

After installing the project, install crubrand as a dependency:

    $ bower install --save pra-brand
    
You can change the release number to meet your needs. For more information about release numbers see [this project](https://github.com/npm/node-semver)

When needed you can update pra-brand using Bower. You may need to change the release number in the `bower.json` file
if you are updating to a new version. 

    bower update

Once installed, `@import` into your project's main scss file:

    @import "bower_components/main";
    
You can [see a sample project](https://github.com/jtclark84/prahs/prahs)
