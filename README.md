# OCLC CJK Composer
Converts decomposed Korean Hangul and Japanese Kana to their composed forms in OCLC Connexion client

[Download here](https://github.com/pulibrary/OCLCJamoComposer/releases/latest/download/InstallOCLCJamoComposer.exe)

## Configuration

The macro book contains 3 macros:
- CJKComposer!ComposeSingleField: Convert the field where the cursor is currently located.
- CJKComposer!ComposeAllFields: Convert all fields in the currently open record.

The following can be done for either or both of these macros:

**To add a macro to the toolbar**
- Select "Tools > User Tools > Assign...". At the top of the screen, click "Macros". In the list box on the left side of the window, select the desired macro.
- Under the "Select New User Tool" menu, select a tool that is not yet assigned to another function. Make note of the tool number, then click "Assign Tool", and then "OK".
- Select "Tools > Toolbar Editor...". Scroll down to "ToolsUserToolsX", where X is the tool number that you just assigned to the macro. Drag the icon to the desired location on the toolbar.
  
**To assign a keyboard shortcut**
- Select "Tools > Keymaps...". In the "Select Commands for Category" box at the top of the window, select "Macros". Double-click "ScriptShifter", then click the desired macro.
- Click in "Press New Shortcut Key" and press the keyboard shortcut you would like to assign to this macro.
- Make sure that "Shortcut Key Assigned to:" is blank, then click "Assign" and then "OK".
