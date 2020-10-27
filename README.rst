==========================
encrypted-django-reversion
==========================

This is a forked version of https://github.com/etianen/django-reversion

If you are using encrypted value for your models while using django-reversion the effect will be negated
since anyone can read the json representation of the object from reversion.
This package fixes this problem.
It provides a super simple modification to the reversion.Version model changing the field type of:

- serialized_data
- object_repr

from a TextField into a EncryptedTextField (from django-searchable-encrypted-fields).


Requirements
============
- django-searchable-encrypted-fields>=0.1

Installation
============
add this line to your requirement.txt
- git+git://github.com/HealperDK/encrypted-django-reversion.git#egg=encrypted-django-reversion
