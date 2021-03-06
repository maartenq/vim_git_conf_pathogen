deploy_vim_conf_git
===================

A simple role for deploying a .vim config from a Git repository. It can use
Pathogen to install plugins.

Requirements
------------

* git>=1.7.1 (the command line tool)

* A git repository with your .vim configuration.

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.)
should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables
that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

.. code-block:: yaml

    - hosts: localhost
      roles:
         - role: maartenq.deploy_vim_conf_git


License
-------

MIT

pathogen.vim_ is copyrighted by Tim Pope. Distributed under the same terms as Vim
itself. See :help license.

Author Information
------------------

An optional section for the role authors to include contact information, or a
website (HTML is not allowed).


.. _pathogen.vim: https://github.com/tpope/vim-pathogen
