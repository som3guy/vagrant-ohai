# Vagrant::Ohai

This is a [vagrant](http://vagrantup.com) plugin which installs an Ohai plugin providing network information to Chef.
In particular, the ipaddress is set to the private network defined in vagrant, if one is present.

## Installation

    vagrant plugin install vagrant-ohai


## Usage

The plugin will automatcially activate when using the `:chef_solo` or `:chef_client` provisioners. If you want to disable it, put `config.ohai.enable = false` in your Vagrantfile.

## Compatability

This plugin works with Vagrant 1.2.3 and above.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
