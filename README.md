# chef-rbenv-ruby2-unicorn-nginx

1. Get a new node/slice/droplet/instance.
2. Update node.json with SSH credentials and example app name.
3. Update the recipes with:

  bundle exec knife solo init .

4. Bootstrap the machine with:

  bundle exec knife solo bootstrap user@machine-ip node.json

## License

MIT.

## Background
Based on [this Chef tutorial](http://matteodepalo.github.io/blog/2013/03/07/how-i-migrated-from-heroku-to-digital-ocean-with-chef-and-capistrano/).