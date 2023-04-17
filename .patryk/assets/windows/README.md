# Console Host

This directory contains a copy of built artifacts from the Microsoft
Terminal project which is provided by Microsoft under the terms
of the MIT license.

Why are they here?  At the time of writing, the conpty implementation
that ships with windows is lacking support for mouse reporting but
that support is available in the opensource project so it is desirable
to point to that so that we can enable mouse reporting in alacritty.

It looks like we'll eventually be able to drop this once Windows
and/or the build for the terminal project make some more progress.

It's possible that you'll need to download this runtime support package
from MS in order for this to work:
https://www.microsoft.com/en-us/download/details.aspx?id=53175
