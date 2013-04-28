# QUANTAL64

Veewee Repo for building a Ubuntu 12.10 Server (Quantal) 64-bit Vagrant Base Box.

# REQUIREMENTS

* Latest Vagrant; non-gem version.

# USE

1. bundle install
2. bundle exec veewee vbox build 'quantal64'
3. /opt/vagrant/bin/vagrant package --base quantal64
