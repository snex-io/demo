Because submodules are not included when using the API, or the UI, this project needs to be deployed using the CLI.

```bash
heroku git:remote -a [heroku app name]
git push heroku master
```

https://devcenter.heroku.com/articles/git
