= gitchart ChangeLog :author: Sébastien Helleu :email:
flashcode@flashtux.org :lang: en

== Version 1.3 (2016-08-13)

-  fix check of javascript command line argument (issue #3)
-  add argument --all for git log commands

== Version 1.2 (2014-12-06)

-  add option -j/--js to customize javascript files/links
-  fix the working directory for the second git command

== Version 1.1 (2014-04-18)

-  fix PEP8 warnings

== Version 1.0 (2013-11-10)

-  fix parsing of authors

== Version 0.9 (2013-11-10)

-  ignore UTF-8 decoding errors

== Version 0.8 (2013-11-10)

-  add chart "commits\_day"
-  rename chart "commits\_hour" to "commits\_hour\_day" and
   "commits\_day" to "commits\_day\_week"
-  add option -s/--sort-max
-  rename option -m/--max to -d/--max-diff

== Version 0.7 (2013-11-09)

-  fix chart title

== Version 0.6 (2013-11-08)

-  add a main function

== Version 0.5 (2013-11-02)

-  make options title/repository optional
-  add option -m/--max
-  display SVG on standard output if filename is "-"

== Version 0.4 (2013-10-25)

-  add PNG support

== Version 0.3 (2013-03-21)

-  fill months without commits (set value to 0) in chart
   "commits\_year\_month"

== Version 0.2 (2013-03-16)

-  read all data on standard input (no more limit at 1MB)
-  add missing argument "title" in help

== Version 0.1 (2013-03-15)

-  first release
