Username
========

Automatically generate usernames and page titles based on a token string.

If you don't want users setting their own usernames, generate them automatically
using tokens. They can be based on the user ID, email address, or custom fields
attached to user profiles.

You can also automatically generate page titles for user profile pages using
tokens, allowing for more descriptive or customized titles.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

- Visit the configuration page under Administration > Configuration > User
  Accounts > Account Settings (admin/config/people/settings) to enable automatic
  username generation and set the pattern they're based on.

- Existing usernames can be bulk-updated by blocking and unblocking user
  accounts on the Manage User Accounts (admin/people) page.


Issues
------

Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/username/issues.


Current Maintainers
-------------------

- [Alan Mels](https://github.com/alanmels)


Credits
-------

- Written for Backdrop CMS by [Peter Anderson](https://github.com/BWPanda).
- Inspired by the
  [Automatic User Names](https://www.drupal.org/project/auto_username) Drupal
  module.


License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
