VDF
===

Sublime Text syntax for Visual Dataflex language

##Usage

###VDF Build
- The build configuration is in VDF.sublime-build
	- You will need to manually setup the path to your DFComp.exe (Visual DataFlex Compiler)
- The build system assumes that your project name is the name of your workspace and the main source file. You can adjust this manually as needed.
- You can use build variants to configure specific and unique build situations without overwriting the main build functionality.
	- When using variants be sure to include the VDF-Build.exe at the start of your cmd as it will output any errors generated into Sublime.
