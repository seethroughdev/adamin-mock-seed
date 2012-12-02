# My Mocking Seed

This is just a simple configuration I like to work with when building mocks for someone.  It includes a codekit-config file so you can have it automatically set up any project.

Although i do plan to switch this over to Grunt and maybe even create a Yeoman generator for it when I can.

This version uses:

- Sass for CSS
- Jade for Templating
- Coffee for Javascript
- Bower for package management

.gitignore is same as my ~/.gitignore, but i put this in, in case anyone else wants to download the folder.

to use this repo:

1. Clone the repo:

        git clone repo

2. Rename the repo:

        mv seed projName

3. Install dependencies:

        bower install

4. Install Neat if you don't have it already

        gem install neat

5. Open Codekit / Add the folder