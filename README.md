[![build status][2]][3] [![Codacy Badge][8]][9] [![codecov][10]][11]


This is the readme for the Python for Win32 (pywin32) extensions source code.

See CHANGES.txt for recent changes.

'setup.py' is a standard distutils build script.  You probably want to:
```
  % setup.py install
```
or
```
  % setup.py --help
```
These extensions require the same version of MSVC as used for the 
corresponding version of Python itself.  Some extensions require a recent 
"Platform SDK"  from Microsoft, and in general, the latest service packs 
should be  installed, but run 'setup.py' without any arguments to see 
specific information about dependencies.  A vanilla MSVC installation should 
be able to build most extensions and list any extensions that could not be 
built due to missing libraries - if the build actually fails with your 
configuration, please log a bug via http://sourceforge.net/projects/pywin32.


[2]: https://ci.appveyor.com/api/projects/status/github/pywin32/pypiwin32?branch=master&svg=true
[3]: https://ci.appveyor.com/project/pywin32/pypiwin32
[8]: https://api.codacy.com/project/badge/Grade/48214aa9e87d4994a41061b155a94e45
[9]: https://www.codacy.com/app/pywin32/pypiwin32?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pywin32/pypiwin32&amp;utm_campaign=Badge_Grade
[10]: https://codecov.io/gh/pywin32/pypiwin32/branch/master/graph/badge.svg
[11]: https://codecov.io/gh/pywin32/pypiwin32
