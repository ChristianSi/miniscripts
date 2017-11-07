# miniscripts

A collection of small scripts, created for various purposes and written in
Perl or other scripting languages.

## Contents

  * **biasedshuffle:** Randomly shuffle a list of values, preferring values
    from the begin of the list. Values are weighted according to the
    Fibonacci series. Perl script.
  * **cget:** Download a single file using curl. If a file with the
    specified name already exists, it is assumed to be an incomplete
    download; the rest of the file will be downloaded and appended. Bash
    shell script.
  * **dateadd:** Add a number of days to a specific date. Perl script.
  * **depresolve:** Resolve the dependencies of a list of files (in
    Debian-based systems). KornShell (ksh) script.
  * **fehcaptionwriter:** Write captions for the [feh image
    viewer](http://feh.finalrewind.org/) and/or the [bins album
    generator](http://bins.sautret.org/). Perl script.
  * **fixepubchars:** Modify epub documents in place by replacing any small
    caps and old-style numerals with their ASCII equivalents. This is
    useful if your reader cannot render the original characters. Perl
    script.
  * **halftime:** Print half the time between two specified times on the
    same day; by default, the current time is used as start time and 22:00
    (10 pm) is used as end time
  * **listdir:** Create a simple listing of a directory and its
    subdirectories in HTML format. Requires
    [txt2html](http://txt2html.sourceforge.net/). Bash shell script.
  * **multimov:** Move a specified number of files with the same extension
    to another directory. Python 3 script.
  * **odta4:** Change the paper format of one or more ODT (LibreOffice,
    OpenOffice) documents to A4. POSIX shell script.
  * **random:** Return a random number in range 0 to 1 (float), 0 to N
    (integer), or X to Y (integer, with offset). Perl script.
  * **randomletter:** Generate a random letter (from 'a' to 'z'). Lua
    script.
  * **sentcheck:** List all sentences in a text (plain text document) that
    may be overly complex (containing too many words or too many breaks
    such as commas and dashes). Perl script.

## Licenses

All scripts in this directory are either licensed under [ISC
License](https://en.wikipedia.org/wiki/ISC_license) or [MIT
License](https://en.wikipedia.org/wiki/MIT_License) or otherwise placed in
the [public domain](https://en.wikipedia.org/wiki/Public_domain) ("no
rights reserved, use as you like"). Script files in this repository that
don't specify a specific license are herewith placed in the public domain
-- they may be used by anybody for any purpose without requiring
attribution or anything else.
