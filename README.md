# Sublime Text 3 SourcePawn Syntax Highlighting

Syntax highlighting for the SourcePawn programming language. Everything has been updated to be complete as of SourceMod 1.10 (Build 6364).

## Installing
Extract the files to `C:\Users\YourUsername\AppData\Roaming\Sublime Text 3\Packages\User`.

This package contains two separate highlighting versions: `SourcePawnOld` and `SourcePawnNew`, labelled on your ST3 syntax list as `SourcePawn - 1.6` and `SourcePawn - 1.7+` respectively.

`SourcePawnNew` (*SourcePawn - 1.7+*) contains deprecation highlighting for the older 1.6 syntax variable declaration/usage methods that have since been replaced with the new 1.7+ "transitional" syntax. This will highlight specific things red which comes in handy when working on updating the syntax of older plugins.

`SourcePawnOld` (*SourcePawn - 1.6*)contains no such deprecation highlighting, instead opting to highlight 1.6 syntax usage. Use this version if you still make plugins with 1.6 syntax.


## 1.6 syntax deprecation highlighting example
In the code snippet below, both the 'new' variable declaration and the 'GetMaxClients' function will be highlighted:
`for (new i = 0; i < GetMaxClients(); i++)`

*The GetMaxClients function highlight is not part of the 1.6 deprecation highlighting.*

In the new 1.7 transitional syntax, the above code would be done like so:
`for (int i = 0; i < MaxClients; i++)`


## Found a bug?
I've tried to ensure that the highlighting works properly, but there may still be some edge cases I haven't discovered yet. If you happen to find one of these edge cases, please do submit an issue report and I'll get right to fixing it.
