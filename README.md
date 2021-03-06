# Ansible Role Template

This is an template repo I intend to use for my Ansible roles. It's packed with some default content.

Here is how to use it:

- Clone this repo to your local machine: `$ git clone git@github.com:wahidsadik/ansible-role-template.git <new-role>`. Here _<new-role>_ is the name of your new role.
- Next: `$ cd <new-role>`
- Remove the `.git` directory to have a fresh start: `$ rm -rf .git`
- Replace the word _tbd_ in the following files with _<new-role>_:
  - README-rename-me.md
  - tests/test.yml
- Delete this file (README.md) and rename README-rename-me.md to README.md.
- Done!

Example usages of this: [https://github.com/wahidsadik/git-based-deploy](https://github.com/wahidsadik/git-based-deploy).

# Other thoughts

I understand that the more correct way to create a role is something like this: `$ ansible-galaxy init <new-role>`, and it will always get the latest template recommended by Ansible. My template may fall behind if I don't keep updated.

For now, I am going to accept this shortcoming.

# TODO

Add a `makefile` to automate the manual steps mentioned above.
