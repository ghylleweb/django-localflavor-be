=====================
django_localflavor_be
=====================

Country-specific Django helpers for Belgium.

What's in the Belgium localflavor?
==================================

* forms.BEPhoneNumberField: A form field that validates input as a Belgium
  phone number, with one of the formats 0x xxx xx xx, 0xx xx xx xx,
  04xx xx xx xx, 0x/xxx.xx.xx, 0xx/xx.xx.xx, 04xx/xx.xx.xx, 0x.xxx.xx.xx,
  0xx.xx.xx.xx, 04xx.xx.xx.xx, 0xxxxxxxx or 04xxxxxxxx.

* forms.BEPostalCodeField: A form field that validates input as a Belgium
  postal code, in the range and format 1XXX-9XXX.

* forms.BEProvinceSelect: A ``Select`` widget that uses a list of Belgium
  provinces as its choices.

* forms.BERegionSelect: A ``Select`` widget that uses a list of Belgium regions
  as its choices.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
