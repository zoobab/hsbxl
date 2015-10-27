# hsbxl

Current website is hosted at hackerspace.be/brussels/www/welcome

## Development
Clone this repo.

Make your changes locally, test your changes locally.

Send a pull request to github.

## Deployment

```
git pull origin master
compass compile
git remote add server ssh://hackerspace.be/home/users/hackerspace/brussels/welcome.git
git commit server master
```

The git repo on hackerspace.be has a post-receive hook that updates the welcome folder. 
