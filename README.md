# Todu API
This project is a RestFul interface of the **TODU** application.


## Not familiar git? Do this

1. Fork the repo by visiting this [link](https://github.com/danielokoronkwo-coder/todu-api/fork) or clicking on the **Fork** button at the top right corner
2. Go to your Terminal(Linux and Mac users), Git Bash(Windows), Termux(Android) and `cd` to the directory you'd like to work from. If you're using Termux, do `termux-setup-storage` and then `cd storage/downloads` and work from there.
3. Run `git clone https://github.com/danielokoronkwo-coder/todu-api` to clone the repo on your machine.
4. Run `cd Todu` to enter into the cloned repo.
5. Run `git remote add upstream https://github.com/danielokoronkwo-coder/todu-api` to create an alias for the repository
6. Go to your forked repository, there is a **clone or download** button, click on it and copy the url displayed.
7. Go back to your terminal and add an alias for your repo by running `git remote add task <paste the url here>`, without the angled brackets. You can replace **task** with an alias of your choice, just make sure you remember it.
8. Run `git checkout master` to ensure you're in the correct branch.
9. Make your changes to the file, make your contributions and smile a lot while doing that. We don't want angry code in the repo.
10. Run `git add .` to stage all your changes to be committed. Do not spill anything on your PC at this point.
11. Run `git commit -m "<your username>:<Feature>: <Your commit message>"`
12. Run `git pull --rebase upstream master` to apply possible changes that might have happened on the online repo while you were making your own changes.
13. Run `git push task master`. Remember to replace the alias if you changed it.
14. Visit the URL of your forked repo. You'll see a button **Compare and pull request**. Click on it, type the appropriate messages and then make the pull request.
15. Take a nap, you earned it no matter how little your change.

## To contribute:

* Ensure you do not edit the .gitignore file for any reason. 
* Whatever extension to the User model is done through a database relationship and not by OOP inheritance.
* Ensure code works before pushing. Don't push breaking code.


#### Note: This README will be updated as often as possible to ensure we know how to set things up


## To get Laravel part up and running
1. Proceed to the Laravel project directory by: `cd Laravel_APIs`
2. Run `composer install` to install composer dependencies.
3. Run `npm install` to install npm dependencies.
4. Run `cp .env.example .env` to create a copy of your **.env** file.
5. Run `php artisan key:generate` to generate an app encyrption key.
6. Run `php artisan serve` or `php -S localhost:8000 -t public/` to run the development server.
