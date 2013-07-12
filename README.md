## Setup a Standalone Vagrant box

- Clone hadouknstack in a folder along with the other hadoukn repositories.

- Install ansible into a virtualenv:

  ```bash
  virtualenv env
  env/bin/pip install ansible
  . env/bin/activate
  ```

- Start the vagrant box:

  ```bash
  vagrant up
  ```
