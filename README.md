This repository demonstrates a common error when using Tcl's `expr` command.  The `badproc` procedure fails when passed non-numeric arguments because `expr` performs direct substitution without type checking. The solution shows how to properly handle variable substitution.