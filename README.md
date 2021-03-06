# Our Tech Stack
I've found that it's pretty interesting to see what other people use on their website and how they use it to scale their application. So I decide, why not implement it on my Startup? So here it is, us being transparent about our technologies that we use.

# HTML and CSS

- We use two templates, [Stack](https://themeforest.net/item/stack-multipurpose-html-with-page-builder/19337626) (Themeforest) for Imam.tech and [Velonic](https://shapebootstrap.net/item/1525168-velonic-admin-dashboard-frontend) (Shape Bootstrap) for campus.Imam.tech. It's simply to ease the development process and to be focused on the features rather than focusing on the template.
- [BEM](http://getbem.com/) is heavily used whenever we need custom component from the default ones provided by either Stack or Velonic.
- There is zero to none interest on HTML preprocessor currently. For CSS, we use SASS just to make it easier to maintain BEM methodology.

# Javascript

- We use Webpack.

# PHP

- Yep, we use PHP, but trying really hard to maintain the best practice so it won't be a messy project.
- Heavily used on [Jupeter Clean Code adaption for PHP](https://github.com/jupeter/clean-code-php) (Clean Code is  a programming book about clean coding practice (duh) to read from Robert C. Martin). We want to add some other rules to make our code easier to read and lovely to develop on, might add one specific repo for it.

## Laravel

- For Laravel best practice, nothing better than watching Laracon. What they tell most of them will be our practice to do things, especially talk from Jeffrey Way and Adam Wathan :)

# Git

- We use Github for all of our cloud repository. Why? Because lots of deployment sites (like Heroku) already makes easy integration with Github, and because if I ever want to get a side job in the future, my Github will look more awesome because most of recruiter see your Github, and it's just a nice impression to look that you're spending lots of your time contributing on Github even on your private repository.
- I choose bash over any git client.

## Github

- We use standard Github for public git repo and Developer's plan Github for private repo (With discount for college student)

# Netlify

- Netlify is the best for static hosting, and we use lots of their free plan features, like static site hosting and SSL.

# Heroku

- We use their $7 plan and for now, it's more than enough.
