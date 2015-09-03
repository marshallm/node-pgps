# Postgres Pub Sub

[![Join the chat at https://gitter.im/pgps/node-pgps](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/pgps/node-pgps?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
![Postgres Pub Sub](https://s3.amazonaws.com/ghpgps/logo.png)

# Check it out
You can get a copy of the source code by checking out our git repository:

```
git clone https://github.com/pgps/node-pgps.git
```

# Get it

## NPM
```shell
# To install
npm install -g pgps

# To run pgps as a service (Ubuntu/Debian only):
sudo bash <(curl -s https://pgps.io/install-service.sh)
```

## Homebrew
```shell
# To install
brew tap pgps/pgps
brew install pgps

# To run pgps as a service:
brew tap homebrew/services
sudo brew services start pgps

# To disable the pgps service:
sudo brew services stop pgps
```

## Ubuntu/Debian
```shell
sudo add-apt-repository ppa:pgps
sudo apt-get install pgps

# By default pgps will run as a service, to disable this:
sudo update-rc.d pgps disable

# To re-enable it:
sudo update-rc.d pgps enable
```

# Test it
You can't run the tests... because there aren't any (yet). But when they are, it'll go something like this:
```
npm test
```

# Grow it
**Pull requests are welcome!** Please provide unit tests and documentation when relevant. If english is not your first language and you'd like to translate documentation into your language we'd appreciate it and will give you ample credit.

# You love it
If you had a good experience with pgps and want to write a tutorial or blog post detailing your experience we encourage you to do so and let us know when you do!

# You hate it
If you had a bad experience with pgps or decided not to use it [tell it to us how it is](mailto:jeff@pgps.io); we can take it!

# You're using it in production
![One does not simply run PGPS in production](http://i.imgur.com/T7GtsG2.jpg)

Wow, you're brave. We're not even using it in production yet! We will let know as soon as we do. **The safety and reliability of PostgreSQL is not impeded by using pgps.** Any reads, writes or updates going through pgps are subject to any bugs it has. If you're paranoid we encourgae you to install the logical decoding plugin on a slave instance. We will let you know when we're comfortable with the stability of pgps and provide tests you can reproduce in your enviornement.

# Get help
If the documentation fails you go ahead and shout for help on [gitter](https://camo.githubusercontent.com/da2edb525cde1455a622c58c0effc3a90b9a181c/68747470733a2f2f6261646765732e6769747465722e696d2f4a6f696e253230436861742e737667) or tweet [@postgresps](https://twitter.com/postgresps). If you encounter an issue or think that your usecase isn't implemented, documented or have a suggestion or feature request go ahead and [create an issue](https://github.com/pgps/node-pgps/issues/new).

# Who are we?
**Just me right now (@jmealo).** I say "we" throughout the documentation to emphasize that this is a community project. If I get bogged down or otherwise fail in my duties and the community suffers, I welcome any passionate, capable individual to take the reigns or join the project as a mantainer. If this happen speaks up, I want pgps to be awesome and useful for years to come.
