django-otp-notify
=================

⚠️ Failsafe copy of
`PierrePaul/django-otp-notify <https://github.com/PierrePaul/django-otp-notify>`__
⚠️

While `Pierre-Paul <https://github.com/PierrePaul>`__ worked on the
`COVID Alert Portal
team <https://github.com/cds-snc/covid-alert-portal>`__, he created this
package to integrate with `GC
Notify <https://notification.alpha.canada.ca/>`__ and we've been using
it ever since. He is the auther/notional maintainer of
`django-otp-notify on PyPi <https://pypi.org/project/django-otp-notify/>`__,
which is one of our `Pipfile dependencies <https://github.com/cds-snc/covid-alert-portal/blob/878be36bbaccd662f695d328186136b9c7508efb/Pipfile#L36>`__.

In the unlikely event that the original library disappears, we can
unarchive this repo and pull it into the Portal as a local dependency.

------------

.. image:: https://img.shields.io/pypi/v/django-otp-notify?color=blue
   :target: https://pypi.org/project/django-otp-notify/
   :alt: PyPI
.. image:: https://img.shields.io/readthedocs/django-otp-notify
   :target: https://django-otp-notify.readthedocs.io/
   :alt: Documentation
.. image:: https://img.shields.io/badge/github-django--otp--notify-green
   :target: https://github.com/django-otp/django-otp-notify
   :alt: Source

This is a django-otp plugin that delivers tokens via Notify's `SMS
<https://www.notifications.service.gov.uk>`_ service.

See `django-otp <https://pypi.org/project/django-otp>`_ for more information
on the OTP framework.

This project is heavily inspired by `django-otp-twilio <https://pypi.org/project/django-otp-twilio/>`_.
