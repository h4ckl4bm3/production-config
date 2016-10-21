This repo contains the official PuPHPet.com config.

It is used to spin up and maintain the server running:

- puphpet.com
- blog.puphpet.com
- repo.puphpet.com (deprecated)

PuPHPet.com runs on Symfony 2.8, so this config is a good
example to get your own SF2 project up and running quickly.

Puppet modules themselves are not tracked in this repo.

For that, you must install librarian-puppet and run the following:

    librarian-puppet install --clean --verbose
    
A tool that automatically does this for you would be a good PR idea!
