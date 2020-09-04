# tau-pact-nodejs-course

To spinup your local pact-broker
* Run `git clone git@github.com:pact-foundation/pact_broker.git && cd pact_broker/example`
* Run `bundle install`
* Run `bundle exec rackup -p 8080`

Troubleshooting:
* If you have an issue installing `thin` run this command `gem install thin -- --with-cflags="-Wno-error=implicit-function-declaration"`.
