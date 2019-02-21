# Introduction
This is my personal fork of the Grub bootloader. I created this fork so that I could make changes to the source in order to attempt to make Grub compile under Windows using Cygwin, a task that I have found very difficult in the past.
This repo will hopefully contain a version of Grub that compiles at least grub-mkresuce, which is really the only utility that I am interested in. I make no guarantees that this fork of the repo will work, or even compile, for you or any machine other than my own.
# Issues
- The build fails straight up, due to warnings being treated as errors.
- The windows platform layer is completely broken and has issues with creating temporary directories.
- Building anything on Cygwin that wasn't meant to be is a complete nightmare.
# Todo List
- Fix the build.
- Rewrite the windows platform layer.
- Simplify build instructions (dependency list, ect).
# Build Instructions
Coming soon.

# Original README
```
This is GRUB 2, the second version of the GRand Unified Bootloader.
GRUB 2 is rewritten from scratch to make GNU GRUB cleaner, safer, more
robust, more powerful, and more portable.

See the file NEWS for a description of recent changes to GRUB 2.

See the file INSTALL for instructions on how to build and install the
GRUB 2 data and program files.

Please visit the official web page of GRUB 2, for more information.
The URL is <http://www.gnu.org/software/grub/grub.html>.

More extensive documentation is available in the Info manual,
accessible using 'info grub' after building and installing GRUB 2.

There are a number of important user-visible differences from the
first version of GRUB, now known as GRUB Legacy. For a summary, please
see:

  info grub Introduction 'Changes from GRUB Legacy'

```