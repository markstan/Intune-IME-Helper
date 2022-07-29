# Intune-IME-Helper
Tools to convert Intune Management Extension (IME) logs to plain text

##Notepad++ instructions

Macro to convert IME logs to plain text format.  To use this XML file, do the following:
1. Copy the contents of Notepad++_Macro.xml to the clipboard (ctrl-c).
2. Open %AppData%\Notepad++\shortcuts.xml in your editor.  Make a backup copy.
3. Insert the copied XML below the <Macros> tag and save the file.
4. Restart Notepad++.
  
This will create a new Macro named *Convert IME* in Notepad++.  The macro is bound to *CTRL-ALT-P* ("prettify") by default.  Use the *Macro\Modify shortcut/delete macro* command in Notepad++ to modify the hotkey.

Running the macro will convert all text in the currently open file to a standard log format (similar to the view in CMTrace).
