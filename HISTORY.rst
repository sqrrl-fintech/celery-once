History
=======

0.1.4
-----

2015-07-29

Bugfixes:

- Fixed an issue where celery beat would crash on graceful enable tasks (#27).
Thanks @PhilipGarnero!

0.1.3
-----

2015-07-14

Features:

- Added option ``unlock_before_run`` to remove the lock before of after the task's execution. Thanks @jcugat!

0.1.2
-----

2015-03-15

Bugfixes:

- Standardized unicode/string handling for the name of a task when generating lock keys.

0.1.1
-----

2015-02-26

Bugfixes:

- Standardized unicode/string handling for keyword arguments when generating lock keys. #11
- Fixed an issue where self bound task (`bind=true`) would not correctly clear locks. #12

Thanks to @brouberol for contributions to both!

0.1
---

-  Initial release of PyPI