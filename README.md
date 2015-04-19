# blueprint

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
    $ ansible-galaxy install hnakamur.osx-defaults
    ```

4. Execute the playbook:
    ```sh
    $ ansible-playbook -i "local," blueprint.yml
    ```
