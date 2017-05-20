# ubuntu-setup

Ansible playbook for setting up blank new Ubuntu Desktop.

## Usage

1. Clone the repository:

    git clone https://github.com/visay/ubuntu-setup.git ~/ubuntu-setup

2. Create your own git configuration for name and email

    touch ~/ubuntu-setup/gitconfig.local

  Add the following lines (replace name and email to your own)

    [user]
      name = Visay Keo
      email = visay@example.com

3. Run the script:

    ansible-playbook playbook.yml

## TODO

- Customize `.profile`, `.zshrc` and `.bashrc`.
