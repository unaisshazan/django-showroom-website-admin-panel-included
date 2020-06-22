===========
Development
===========

Release Notes
=============
**Changes in version 0.4.0** (2017-04-27)

* ``Python 3.4+`` support, ``Python 2.7`` support dropped
* Updated ``Django`` requirement version from 1.8 to 1.11
* Updated ``Haystack`` dependency to 2.6, ``Whoosh`` dependency to 2.7

**Changes in version 0.3.1** (2015-08-25)

* Added more entries to the example project (see: :ref:`example_project`)
* Switched back to 3-column layout for large screens
* Layout improvements
* Removed not-used library files
* Fixed bug when using same category URL name for different editions

**Changes in version 0.3** (2015-08-24)

* Responsive design
* Bug fixes

**Changes in version 0.2** (2015-08-20)

* New organized development structure with new separate docs (this one), branch-based development
* Made ``Haystack`` work again, fixed requirements to ``django-haystack==2.0.0`` and ``Whoosh==2.4.1`` (new
  setting HAYSTACK_SIGNAL_PROCESSOR = 'haystack.signals.RealtimeSignalProcessor' in ``settings.py`` necessary)
* Replaced ``PIL`` requirement with ``Pillow``
* Support for ``Django 1.8`` (older versions dropped), coming from ``1.4`` following adoptions are necessary:

  * ``ALLOWED_HOSTS`` has to be added to ``settings.py`` of Django project
  * ``python manage.py migrate`` has to be run to apply/recognize the new ``Django`` migrations

* Replaced ``South`` migrations with re-generated ``Django`` internal migrations
* Setup instructions in docs
* New ``example_project`` Django project with basic Color Website Showroom example
* Section in docs describing how to create a showroom website
* Fixed some bugs

**Changes in version 0.1** (A long time ago...)

* Initial version, just existing in ``master`` branch, no dedicated ``tags`` or ``pip`` releases yet
