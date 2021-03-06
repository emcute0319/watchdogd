Contributing to watchdogd
=========================

We welcome any and all help in the form of bug reports, fixes, patches
for new features -- *preferably as GitHub pull requests*, submitting a
pull request practically guarantees inclusion ... other methods are of
course also possible: emailing the maintainer a patch or even a raw
file, or simply emailing a feature request or an alert of a problem.
For email questions/requests/alerts there is always the risk of memory
exhaustion on the part of the maintainer.


Coding Style
------------

> **Tip:** Always submit code that follows the style of surrounding code!

First of all, lines are allowed to be longer than 72 characters these
days.  In fact, there exist no enforced maximum, but keeping it around
100 chars is OK.

The coding style itself is strictly Linux [KNF][].


Commit Messages
---------------

Commit messages exist to track *why* a change was made.  Try to be as
clear and concise as possible in your commit messages.  Example from
the [Pro Git][gitbook] online book:

    Brief, but clear and concise summary of changes
    
    More detailed explanatory text, if necessary.  Wrap it to about 72
    characters or so.  In some contexts, the first line is treated as
    the subject of an email and the rest of the text as the body.  The
    blank line separating the ummary from the body is critical (unless
    you omit the body entirely); tools like rebase can get confused if
    you run the two together.
    
    Further paragraphs come after blank lines.
    
     - Bullet points are okay, too
    
     - Typically a hyphen or asterisk is used for the bullet, preceded
       by a single space, with blank lines in between, but conventions
       vary here
    
    Signed-off-by: Joachim Nilsson <troglobit@gmail.com>


Another good *counter* example [is this][rambling] ...


Code of Conduct
---------------

It is expected of everyone engaging in the project to, in the words of
Bill & Ted; [be excellent to each other][conduct].


[github]:   https://github.com/troglobit/watchdogd/
[KNF]:      https://en.wikipedia.org/wiki/Kernel_Normal_Form
[gitbook]:  https://git-scm.com/book/ch5-2.html
[rambling]: http://stopwritingramblingcommitmessages.com/
[conduct]:  https://github.com/troglobit/watchdogd/blob/master/CODE-OF-CONDUCT.md

<!--
  -- Local Variables:
  -- mode: markdown
  -- End:
  -->
