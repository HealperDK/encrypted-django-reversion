==========================
encrypted-django-reversion
==========================

This is a forked version of https://github.com/etianen/django-reversion version 3.0.8

It provides a super simple modification to the Version model changing the serialized_data field from a
TextField into a EncryptedTextField.

This package requires

Requirements
============
- django-searchable-encrypted-fields>=0.1

Installation
============
add this line to your requirement.txt
- git+git://github.com/HealperDK/encrypted-django-reversion.git#egg=encrypted-django-reversion
