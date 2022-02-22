# OSMT Project Site

Hello, welcome to the OSMT documentation site repo, here you'll find the steps needed to get you setup locally.

# Installation
Latest Ruby and gems need to be installed first.

### Ruby install
1. If you do not have ruby locally do so by using Homebrew `brew install ruby` or rvm, your choice.
2. Once installed you will need to add it to your `$PATH`.
Easiest way is to run this command `echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> "shell rc or profile of choice"`.

### Update Ruby to new version
You need latest Ruby installed. Use `ruby -v` to verify. Anything under 3.0.2 should be updated.


### Once Ruby is installed and up-to-date, the following steps are needed:
**While on the project root directory**
1. Install bundler. Use gem to install it `gem install bundler`.
2. Next add webrick with bundler `bundle add webrick`.
3. Run `bundle install` to install the libraries.
4. to serve it you will need to run `bundle exec jekyll serve`.

# Deploying to Github Pages

We are currently deploying this static site to Github pages. To deploy is quite simple, just follow these steps:

1. From the project repository go to `Settings`.
2. Click on `Pages`.
3. Under *Source* choose the branch you want the source code to deploy from and select `root` folder.

Once done, github will give you url to view the published site.
