=====================
django_localflavor_jp
=====================

Country-specific Django helpers for Japan.

What's in the Japan localflavor?
================================

* forms.JPPostalCodeField: A form field that validates input as a Japanese
  postcode. It accepts seven digits, with or without a hyphen.

* forms.JPPrefectureSelect: A ``Select`` widget that uses a list of Japanese
  prefectures as its choices.

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
