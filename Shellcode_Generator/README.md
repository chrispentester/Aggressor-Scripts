# Shellcode Generator

Create stageless shellcode for the listener, with an exitfunc, and architecture, of type array, hex, powershell-base64, vba, vbs, or veil


# Usage

NOTE: VBA array is too large for a VBA Macro

Load the CNA script in Cobalt Strike, then the following command will be included:

`shellcode_generator [shell_type] [exitfunc] [x86/x64] [listener]` - Create stageless shellcode for the listener, thread, and architecture
