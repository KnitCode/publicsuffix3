Changelog
---------

2019-06-09    publicsuffix3 3.20190609

    * created new publicsuffix3 package (pull request to publicsuffix2 stalled)
    * incorporated test changes from PR on 6/5/19

2019-02-05    publicsuffix2 2.201902051213

    * Updated publicsuffix.file to the latest version from Mozilla.
    * Restored a fetch() function by popular demand


2018-12-13    publicsuffix2 2.20181213

    * Updated publicsuffix.file to the latest version from Mozilla.


2018-10-01    publicsuffix2 2.20180921.2

    * Updated publicsuffix.file to the latest version from Mozilla.
    * Breaking API change: publicsuffix module renamed to publicsuffix2


2016-08-18    publicsuffix2 2.20160818

    * Updated publicsuffix.file to the latest version from Mozilla.


2016-06-21    publicsuffix2 2.20160621

    * Updated publicsuffix.file to the latest version from Mozilla.
    * new version scheme: major.<publisiffix list date>


2016-06-21    publicsuffix2 2.20160621

    * Updated publicsuffix.file to the latest version from Mozilla.
    * new version scheme: major.<publisiffix list date>


2015-10-12    publicsuffix2 2.1.0

    * Merged latest updates from publicsuffix
    * Added new convenience top level get_public_suffix_function caching
      a loaded list if needed.
    * Updated publicsuffix.file to the latest version from Mozilla.
    * Added an update_psl setup command to fetch and vendor the latest list
      Use as: python setup.py update_psl


2015-06-04    publicsuffix2 2.0.0

    * Forked publicsuffix, but kept the same API
    * Updated publicsuffix.file to the latest version from Mozilla.
    * Changed packaging to have the suffix list be package data
      and be wheel friendly.
    * Use spaces indentation, not tabs


2014-01-14    publicsuffix 1.0.5

    * Correctly handle fully qualified domain names (thanks to Matthäus
      Wander).
    * Updated publicsuffix.txt to the latest version from Mozilla.

2013-01-02    publicsuffix 1.0.4

    * Added missing change log.

2013-01-02    publicsuffix 1.0.3

    * Updated publicsuffix.txt to the latest version from Mozilla.
    * Added trove classifiers.
    * Minor update of the README.

2011-10-10    publicsuffix 1.0.2

    * Compatibility with Python 3.x (thanks to Joern
      Koerner) and Python 2.5

2011-09-22    publicsuffix 1.0.1

    * Fixed installation issue under virtualenv (thanks to
      Mark McClain)

2011-07-29    publicsuffix 1.0.0

    * First release
