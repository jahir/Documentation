# ${IsWin8}.1

Checks if the installer is running on Windows 8.1 exactly as specified.

## Syntax

    logic_lib_statement ${IsWin8.1}

## Example

    ${If} ${IsWin8.1}
        DetailPrint "Windows 8.1 or higher"
    ${Else}
        DetailPrint "Older than Windows 8.1"
    ${EndIf}

## Credits

*unknown*
