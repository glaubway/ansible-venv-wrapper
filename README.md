# ansible-venv-wrapper

Simple wrapper to launch ansible playbook from python venv

## Preparing

1. Clone repository to your local machine
2. Open repository directory and run prepare-environment.pl, like next

    ```shell
    ./prepare-environment.pl
    ```

3. When environment will be ready you will see *Virtual environment successfully prepeared.* in console
4. Run playbook with run_playbook.sh script, like next

    ```shell
    ./run_playbook.sh -i inventory/<inventory file> <playbook yml file>
    ```

## Requirements

* Debian/RedHat based distro
* Python3
