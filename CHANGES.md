# Changelog

## v1.2.1 - Jun 10, 2012, 3:41 PM

* Slightly loosen what passes for a one-line description of the app, courtesy @jredville

## v1.2.0 - May 21, 2012, 11:05 PM

* Better handling of `open4` dependency when you don't install it and you don't use it.
* Quoted spaced strings in config files and env var weren't working.  Now they are.
* Use the current version in generated gemspec
* Non-string arguments (such as Regexps for validation and classes for type conversion) were not working.  Now they are.
* `sh` can now be used more safely by passing an array to avoid tokenization (thanks @gchpaco!)

## v1.1.0 - April 21, 2012, 6:00 PM

* Can bootstrap apps using RSpec instead of Test::Unit (thanks @msgehard)

## v1.0.0 - April 1, 2012, 10:31

* Initial official release
