heroku-html-website-rackup
==========================

In this repository I uploaded an example of html, css, javascript
website ready to be deploy in heroku.com using rack gem and with
multiple routes

### Testing the website locally
##### If you want to test this website in your local machine just
##### follow the next steps in your command line terminal:

```shell
git clone git@github.com:heridev/heroku-html-website-rackup.git
cd heroku-html-website-rackup
bundle install
rackup
```

#### Open your browser
##### Visit http://0.0.0.0:9292

### Uploading to heroku
##### if you want to deploy in heroku.com just

```shell
cd heroku-html-website-rackup
heroku create //if you already has installed heroku toolbet
git push heroku master
```
