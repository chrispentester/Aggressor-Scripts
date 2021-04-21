# VBA Payload Generator
Create a stageless VBA array with parameters exitfunc (thread or process), architecture (x86 or x64), and Listener

# Usage

NOTE: The stageless version is too long for a VBA Macro!
Load the CNA script in Cobalt Strike, then the following command will be included:

`vba_create [exitfunc] [x86/x64] [listener]` - Create a stageless VBA array for the listener, thread, and architecture
