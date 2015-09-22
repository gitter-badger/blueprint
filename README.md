# blueprint

[![Join the chat at https://gitter.im/andystanton/blueprint](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/andystanton/blueprint?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Ansible playbook for my osx configuration.

# Usage

1. Install ansible
2. Clone blueprint:
    ```sh
    $ git clone https://github.com/andystanton/blueprint.git
    $ cd blueprint
    ```

3.  Install role dependencies:
    ```sh
    $ ansible-galaxy install hnakamur.osx-defaults hnakamur.atom-packages
    ```

4. Execute the playbook:
    ```sh
    $ ansible-playbook -i "local," blueprint.yml
    ```

    or if using my bbc profile:

    ```sh
    $ ansible-playbook -i "local," blueprint.yml --extra-vars is_bbc=true
    ```
