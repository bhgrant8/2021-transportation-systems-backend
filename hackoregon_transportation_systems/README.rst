=============================
hackoregon_transportation_systems
=============================

.. image:: https://badge.fury.io/py/2021-transportation-systems-backend.svg
    :target: https://badge.fury.io/py/2021-transportation-systems-backend

.. image:: https://travis-ci.org/hackoregon/2021-transportation-systems-backend.svg?branch=master
    :target: https://travis-ci.org/hackoregon/2021-transportation-systems-backend

Your project description goes in here

Documentation
-------------

The full documentation is at http://hackoregon.github.io/2021-transportation-systems-backend

Quickstart
----------

Install hackoregon_transportation_systems::

    pip install hackoregon_transportation_systems

Add subpackages to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'hackoregon_transportation_systems.passenger_census',
        ...
    )

Add hackoregon_transportation_systems's URL patterns:

.. code-block:: python

    from hackoregon_transportation_systems.passenger_census import urls as passenger_census_urls


    urlpatterns = [
        ...
        url(r'^', include(passenger_census_urls)),
        ...
    ]
