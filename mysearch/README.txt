You are using custom Mysearch module.

1) This module implements custom caching scheme to avoid overwhelming of
default cache tables. All results are cached on time defined in cache_lifetime
variable, you can change it's value on page
http://yoursite.com/admin/config/development/performance.

2) if Minimum cache lifetime setting is not defined then all results will
be cached one hour.

3) This module provides two pages mysearch and mysearch/%. Results are
displayed 20 per page using default pager decorator.

4) Using this pages you can find any node which contains search word
inside body value or node title.

5) All inserted values are properly trimmed, decoded and sanitized.
