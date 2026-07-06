<!-- mkrol-io/mkrol-io · profile README -->
<!-- hand-written. no cookies · no trackers · no javascript · renders in lynx. -->

```text
MKROL(1)                Operator's Manual                 MKROL(1)

NAME
     mkrol — keeps the lights on

SYNOPSIS
     mkrol [-c] [-r] [--no-guess] escalation
     mkrol --calm < incident

DESCRIPTION
     where escalations end.  reads the logs, does not guess.
     resolution method: boring, mostly.  the machine doesn't
     lie; it only waits to be read.

OPTIONS
     -c, --calm
            calm is a system property, not a mood.  on by
            default.

     -r, --read-first
            read before you write.  always.

     --no-guess
            fix the cause, not the page.

     --obstacle
            treat it as the way.

PRINCIPLES
     read before you write
     fix the cause, not the page
     calm is a system property
     the obstacle is the way
     the machine doesn't lie

ENVIRONMENT
     TZ         somewhere north
     SHELL      /bin/calm
     HOME       mkrol.io   (renders in lynx)

FILES
     /etc/motd            on call, reads first
     ~/.plan              this page

EXIT STATUS
     0      resolved.  boring, mostly.
     >0     does not occur here.  that is the job.

DIAGNOSTICS
     "the machine doesn't lie."  when it seems to, read
     again.

EXAMPLES
     $ mkrol --read-first prod-is-down
     $ mkrol --calm < 3am-page

SEE ALSO
     fortune(6), stoic(7), silence(1)

BUGS
     none that reproduce.

AUTHOR
     mkrol · me@mkrol.io · https://mkrol.io
     no cookies · no trackers · no javascript

mkrol.io                 somewhere north                  MKROL(1)
```
