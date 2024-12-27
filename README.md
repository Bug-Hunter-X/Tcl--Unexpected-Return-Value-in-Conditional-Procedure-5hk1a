This repository demonstrates a subtle bug in a Tcl procedure that involves the use of the `return` command within a conditional statement. The procedure `badproc` attempts to return the larger of two numbers but does so in a manner that leads to unexpected behavior in certain contexts.  The corrected version `goodproc` shows how to avoid this issue.