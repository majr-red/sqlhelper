# sqlhelper (development version)

## Enhancements

* configs now inherit characteristics from earlier configs with the same name (i.e. site-wide configs may be tweaked by users) (#9)
* renamed `runqueries()` and `runfiles()` as `run_queries()` and `run_files()`
* added `runqueries()` and `runfiles()` as aliases for `run_queries()` and `run_files()`  
* numerous documentation updates
* `read_sql()` now accepts a flag to turn off cascade behaviour (#7)
* `run_files()` no longer requires an explicit `cascade` argument 

## Bug fixes

* read/prep functions now pass dots instead of duplicating default values (#6)
* `not_connected()` no longer errors when passed a missing connection name (#10)

# sqlhelper 0.1.2

## Bug fixes

* `runfiles()` error preparing multiple files (#1)

# sqlhelper 0.1.1

* Added a `NEWS.md` file to track changes to the package.