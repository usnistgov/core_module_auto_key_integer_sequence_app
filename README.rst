core_module_auto_key_integer_sequence_app
=========================================

Auto Key (sequence of integers) module for the parser core project.

Quick start
===========

1. Add "core_module_auto_key_integer_sequence_app" to your INSTALLED_APPS setting
---------------------------------------------------------------------------------

.. code:: python

    INSTALLED_APPS = [
      ...
      'core_module_auto_key_integer_sequence_app',
    ]

2. Include the core_module_auto_key_integer_sequence_app URLconf in your project urls.py
----------------------------------------------------------------------------------------

.. code:: python

    url(r'^', include('core_module_auto_key_integer_sequence_app.urls')),