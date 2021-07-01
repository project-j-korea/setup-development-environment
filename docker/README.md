# Docker

- If you haven't done mac os setting, click **[here](../mac-os)**.
- Type the following command string:

  ```bash
    $ brew install --cask docker
    $ brew install docker-machine
    $ brew install virtualbox
    $ #  > System Preference... > Security & Privacy > General
    $ docker-machine create --driver virtualbox default
    $ docker-machine ls
    $ eval $(docker-machine env default)
  ```
