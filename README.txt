
      _        
 _ __(_)__ ___ 
| '_ \ / _/ _ \
| .__/_\__\___/
|_|            Pico

Copyright (c) 2012 by UT-Battelle, LLC.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

Collection of administrative costs for redistribution of the source code or
binary form is allowed. However, collection of a royalty or other fee in excess
of good faith amount for cost recovery for such redistribution is prohibited.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER, THE DOE, OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


Contents
========
Prerequisites
Building
Testing


README
======
This is the distribution of a pure Java implementation of the Pico library.
At present it includes classes implementing the Pico wrapper format, and little
else.

Visit the Pico web site at:
http://mons-pico.github.com/


Prerequisites
=============
Pico has no external requirements at this time beyond ant (to build) and java
(to build and run).


Building
========
The system can be built with ant.  Run ant from the root folder (the folder
that contains build.xml) to build the library from source.  Other targets are
available: run ant -p for additional target information.


Testing
=======
All functionality that is exposed to the end user must have a corresponding
unit test.  The tests live in "test" packages under the package they are
testing.  Use JUnit to construct tests, where possible.  For a quick
introduction to JUnit, see:
http://www.vogella.com/articles/JUnit/article.html
