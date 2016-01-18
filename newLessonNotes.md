# new lesson plan notes

##00-intro
+ what is bash
+ why do we want to use it

##01-moving around and looking at things
+ whoami  
+ pwd  
+ file system overview
+ ls (-l, -a, arguments)
+ man
+ cd
+ .. and .
+ tab completion
+ meaning of ~

##02-file handling

reorganize these
+ mkdir
+ nano text editor (vi instead?)
+ cat
+ less/more
+ rm (doesn't work on directories, files gone forever)
+ rmdir
+ rm -r
+ mv for renaming, moving
+ cp
+ escape characters
get rid of challenge problems at end and replace with something more relevant

##03-pipefilter

+ wildcards
+ wc (-w, -l, -c)
+ ">"
+ sort (-n, add uniq?)
+ head, tail
+ "|"
+ "<" redirects input
+ ">>"

skim down examples, some are good

##05-scripts

+ comments
+ they are running scripts with "bash" first
+ #! in scripts
+ permissions/chmod/sudo
+ shell script arguments - $@ - all arguments
+ use quotes to make things robust vs. spaces

script reading comprehension examples are great

##04-loops

+ introduce shell variables first with echo
+ basic for loops
+ concatenation with shell variables, {} for grouping

use echo as a debugging tools

##06-find

+ grep example is hilarious/great, maybe rewrite with a gtf file
+ find lessons are good
+ shell expansion of *
+ $(command)
+ wget
+ unzipping files
+ awk/sed?
+ file parsing?
+ logfile creation?