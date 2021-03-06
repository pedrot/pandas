=============
Release Notes
=============

pandas 0.3.0
============

**Release date:** Under development

**New features / modules**

* pandas.stats
 * `pandas.stats.covest` module for covariance matrix estimation

* `pandas.io`: IO utilities
  * `pandas.io.sql` module
    * Convenience functions for accessing SQL-like databases
  * `pandas.io.pytables`

**Improvements**

* Unit test coverage
  * Vastly increased for data structures, core code
* Speed enhancement to rolling_{median, max, min}

**API Changes**

* Exponentially-weighted moment functions in `pandas.stats.moments`
  have a more consistent API and accept a min_periods argument like
  their regular moving counterparts.

**Bug fixes**

* Fixed bug in IndexableSkiplist Cython code that was breaking
  rolling_max function

