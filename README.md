This is a static site containing a snapshot of the website at cm.buildconf.com shortly after the conference ran in 2010.

It's currently hosted on our server and is available at [cm.buildconf.com][] (which is a CNAME pointing at gofreerange.com).

## Deployment

### Using recap to deploy

    $ cap bootstrap
    $ cap deploy:setup
    $ cap deploy

### Set the caffeine-monitor-static user's shell to bash

    root$ chsh -s /bin/bash caffeine-monitor-static

### Configuring Apache

    $ cap apache:enable_config

[cm.buildconf.com]: http://cm.buildconf.com
