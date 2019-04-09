# rapid-crn-input
Script that inputs CRNs almost instantly

**IMPORTANT NOTE:**
 You MUST have AutoHotKey installed for the script to run. Go to https://www.autohotkey.com/download/ to download it if you don't have it. Also, please read through the whole README before using the script.
 To run the script, just double-click on the file.

**HOTKEYS:**
 There are 3 hotkeys associated with this script (see EDITING for more information):
  1) ALT + C will execute the Rapid Input
  2) ALT + X will execute the Rapid Delete
  3) Alt + Esc will terminate the script

**EDITING:**
 Even if you have no idea on how to write script code for AutoHotKey, you will still need to edit the script to plug in your CRNs.
To edit the script, right click on the .ahk file and select "Open With..." -> "Notepad" (or you could use any editor of your choice).

On line 7 there is a statement initializing an empty array called "crn". Add your desired CRNs inside the square brackets on line 7 and make sure the CRNs are separated with commas.
After that, you're good to use the Rapid Input feature of the script. Just be sure to click on the empty text field where you want the Rapid Input to happen and press the associated keybinding (ALT + C). What this will do is 1) quickly type the CRN and 2) press TAB to move to the next text field. This will repeat for as many times as CRNs you typed in the "crn" array on line 7. Essentially, this script is best suited for registering for classes on Banweb.

If you would like to use the Rapid Delete feature, then move down the script to line 18. Line 18 should read "loop, X". Replace "X" with the number of CRNs present in the "crn" array on line 7. For example, if you entered a total of 6 CRNs in the "crn" array, then you should replace the "X" on line 18 with 6. *Note: the number of CRN items on line 7 and the number after "loop" on line 18 MUST be the same, or else the Rapid Delete feature won't work as efficiently as it should.* After replacing the "X" on line 18, the Rapid Delete feature should be ready for use. To use, move your cursor into the text field where the deletion should start, and press the associated keybinding (ALT + X). What this will do is essentially the exact opposite of the Rapid Input feature: it will 1) Select all text in the text field, 2) press BACKSPACE to delete the highlighted text, and 3) press TAB to move to the next field. If you set the "X" on line 18 to the correct number, the Rapid Delete should repeat for as many timmes as CRNs are you have in the "crn" array on line 7.

Finally, if you do know how to write script code for AutoHotKey, then feel free to do whatever with the script. I'm not the script police.

**CONTACT:**
 If you have any questions or encounter any errors / bugs in the scripting, feel free to contact me:
via Email -> nschultz@mtu.edu
via Discord -> nick nack#4668
