# 1.0.3 31/05/2019

* Removed redis-namespace dependency
* Improved style

# 1.0.2 8/09/2014

* Some small non-breaking changes


# 1.0.1 08/05/2014

* #14 fix issue with wrong count on bucket_span == count(..interval) - @olgen


# 1.0.0 06/15/2014

* #7 Allow adding more than one to a counter - @Nielsomat
* #8 Add Ruby 2 support and remove Ruby 1.8 support
* #6 Clean up initialization method
* #11 Optimize Redis Commits - @lautis
* #10 Add a return value - @lautis


# 0.0.3 11/08/2011

* Allow non-string subject and key -- Thanks Alexey Noskov
* Fix for bucket_expiry allowed to be larger than bucket_span and causing bad results -- Thanks Alexey Noskov


# 0.0.2 10/29/2011

* Initial Relase
