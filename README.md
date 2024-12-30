BBC BASIC is a dialect of BASIC originating from Acorn computers at the start
of the 1980s. It has received a number of significant updates over the years,
not least with the introduction of RISC OS and 32-bit computer hardware around
1987.

The BBC BASIC language is maintained as a part of the RISC OS operating system
at https://www.riscosopen.org/ and is Open Source. In order to support hosting
the source code to RISC OS and related software in a tool called GitLab, the
maintainers (RISC OS Open) authored a syntax highlighting scheme in the package
used by GitLab, called "Rouge":

https://github.com/rouge-ruby/rouge/blob/master/lib/rouge/lexers/bbcbasic.rb

This Sublime Text syntax highlighting scheme ports the Ruby scheme and fixes a
number of omissions, as well as adding various enhancements.
