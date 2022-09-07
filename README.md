 ME 701 -- Homework 1 -- Your Name Here

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

I use soldiworks a lot of modeling parts that I 3d print at home.  An open
source alternative is FreeCAD.  It is visually fairly similar and has all
of the core functionality that I use solidworks for at home.  It does not
have some of the fancier features that I use at work but would be a great
free alternative to replace my need for solidworks at home.

## Problem 3 -- Your CPU

### Statement
Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following command:

```
cat /proc/cpuinfo
```
this command produced a frankly excessive amount of information that did
include my cpu speed in mhz and core count.  The core count listed was
physical cores and not logical cores.

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution

use the command

```
top
```
then press the M key to sort by memory usage.
you may then press the P key to sort by processor usage.
when finished you may press the q key to return to the command line

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution
using the command

```
which bash
```
shows that bash is located at
```
/usr/bin/bash
```

Using the command
```
bash -version
```
shows that bash version 5.0.16 is installed
