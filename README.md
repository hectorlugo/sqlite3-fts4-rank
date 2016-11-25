Daplie is Taking Back the Internet!
--------------

[![](https://daplie.github.com/igg/images/ad-developer-rpi-white-890x275.jpg?v2)](https://daplie.com/preorder/)

Stop serving the empire and join the rebel alliance!

* [Invest in Daplie on Wefunder](https://daplie.com/invest/)
* [Pre-order Cloud](https://daplie.com/preorder/), The World's First Home Server for Everyone

Loadable Extensions in SQLite
===

There is a wonderful [example of a rank extension](http://www.sqlite.org/fts3.html#appendix_a) provided in the sqlite3 documentation for full-text search.
However, the example requires building an extension which is not explicitly detailed in the example.
This repository is for the sole purpose of building the un-adulterated* example from the docs.

    git clone http://github.com/coolaj86/sqlite3-fts4-rank.git
    cd sqlite3-fts4-rank
    make linux # or darwin (OSX) or win32 (Visual Studio)

    sqlite3 --init test-fts4.sql ':memory:'
    
Note: *There were a few typos / errors in the example function. They have been corrected to behave as documented.

See Also
===

  * <http://www.sqlite.org/cvstrac/wiki?p=LoadableExtensions>
  * <http://www.mail-archive.com/sqlite-users@sqlite.org/msg71730.html>
  * <http://www.sqlite.org/c3ref/create_function.html>
  * <http://www.sqlite.org/fts3.html#appendix_a>
  * <http://www.sqlite.org/c3ref/load_extension.html>
