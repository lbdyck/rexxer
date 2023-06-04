# REXXER

## What is it?

REXXER is an ISPF Edit macro that will invoke the REXX Compiler
(assuming it is installed) against the active Edit session (member),
capture any generated messages, and insert the messages into the
active member as ISPF Edit messages.

## Why use it?

As a quick way to validate that the REXX code will at least pass the
requirements of the REXX Compiler. If it doesn't then you know what to
fix, and if it does then you know that you have no REXX issues. It does
nothing to fix any logic issues .
