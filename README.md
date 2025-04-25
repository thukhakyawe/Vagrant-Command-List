# Vagrant Command List

## Basic Vagrant Commands

| Command                        | Function                                                                 |
|--------------------------------|--------------------------------------------------------------------------|
| `vagrant init`                 | Initializes a new Vagrant environment by creating a `Vagrantfile`.        |
| `vagrant up`                   | Starts and provisions the Vagrant machine.                               |
| `vagrant halt`                 | Shuts down the running Vagrant machine.                                  |
| `vagrant reload`               | Restarts the machine and applies any changes in the `Vagrantfile`.       |
| `vagrant destroy`              | Stops and deletes all resources created during the machine's lifecycle.  |
| `vagrant status`               | Shows the status of the current Vagrant environment.                     |
| `vagrant ssh`                  | SSH into the running Vagrant machine.                                    |
| `vagrant suspend`              | Suspends the VM (saves its state).                                       |
| `vagrant resume`               | Resumes a suspended VM.                                                  |

## Box Management

| Command                        | Function                                                                 |
|--------------------------------|--------------------------------------------------------------------------|
| `vagrant box add <name>`       | Adds a new Vagrant box.                                                  |
| `vagrant box list`             | Lists all installed Vagrant boxes.                                       |
| `vagrant box remove <name>`    | Removes a box from local storage.                                        |
| `vagrant box update`           | Updates the box to the latest version.                                   |
| `vagrant box outdated`         | Checks if your box is outdated.                                          |

## Plugin & Environment

| Command                        | Function                                                                 |
|--------------------------------|--------------------------------------------------------------------------|
| `vagrant plugin list`          | Lists installed Vagrant plugins.                                         |
| `vagrant plugin install`       | Installs a plugin.                                                       |
| `vagrant global-status`        | Shows all Vagrant environments on the system.                            |
| `vagrant provision`            | Re-runs the provisioning scripts.                                        |
| `vagrant reload --provision`   | Restarts the machine and reprovisions.                                   |
