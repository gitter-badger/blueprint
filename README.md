# blueprint

Ansible playbook for my osx configuration.

# Usage

1. Install ansible
2. Clone blueprint:
    ```sh
    $ git clone https://github.com/andystanton/blueprint.git --recursive
    $ cd blueprint
    ```

3. Execute the following ```ansible-playbook``` command:
    ```sh
    $ ansible-playbook -i "local," blueprint.yml
    ```

# Caveats

This will ultimately make use of the playbook ```hnakamur.osx-defaults``` from Ansible Galaxy pending my [pull request to add support for OSX Defaults with Integer Type](https://github.com/hnakamur/ansible-role-osx-defaults/pull/1). In the meantime, I'm making use of my fork via a git submodule.
