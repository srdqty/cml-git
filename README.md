# Concurrent ML

I cloned the svn repo from here:
https://smlnj-gforge.cs.uchicago.edu/svn/smlnj/cml

See http://www.smlnj.org/svn.html

I tried to keep history. I used the following command:
```
git svn clone --prefix=upstream/ -T trunk -b branches -t releases https://smlnj-gforge.cs.uchicago.edu/svn/smlnj/cml cml-git
```

Original README
--------------------------------------------------------------------------------

This is an "beta" release of a completely new implementation of CML.
It has been in use since the Fall'96, and seems to be robust.
The doc/HTML directory has partial HTML documentation for this version.

In keeping with the migration of SML/NJ to the SML'97 standard, this version
of CML has a number of changes in the API.  See the file doc/HTML/porting.html
for more information.

- John Reppy
  Bell Labs, Lucent Technologies
  jhr@research.bell-labs.com
