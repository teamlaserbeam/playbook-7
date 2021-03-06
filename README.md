# Hanno's Playbook

##[The wiki](https://github.com/wearehanno/playbook/wiki)

This is the main bit. We're trying to get this to be as comprehensive as possible, and migrate everything away from being inside The Hanno Manual we used to use internlly.


##The [Playbook website](http://playbook.hanno.co).

This is supposed to be a slightly higher general overview, so that clients and potential hires will read through it. It's hosted on Github Pages and is automatically 'deployed' as soon as you commit to the default `gh-pages` branch.

It shows up at [playbook.hanno.co](http://playbook.hanno.co).

DNS hosting is taken care of over at hover.com.

### How to use it

1. Clone this repository
2. Make sure you're on the `gh-pages` branch
2. ` $ bundle`
3. Run `$ jekyll -w serve` inside the directory
4. Visit `http://localhost:4000`

If it fails, you might need to select a specific ruby version. `$ rvm use 2.1.0` might help, if you have Ruby 2.1.0 installed.

All your changes will be deployed to the live Playbook when you push to the repo.


###Deployment 

GitHub pages runs Jekyll natively. 'Deployment' is handled by them, and happens as soon as you push to the `gh-pages` branch.
