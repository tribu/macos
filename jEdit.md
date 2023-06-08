Install the ARM version of Java 17 from Oracle
Install jEdit 5.6 (Follow instructions to drag and drop to your Applications folder and Ctrl-Click it).
Download the precompiled binary of universalJavaApplicationStub
Unzip it, and overwrite the binary /Applications/jEdit.app/Contents/MacOS/jedit with it i.e
cp ~/Downloads/universalJavaApplicationStub /Applications/jEdit.app/Contents/MacOS/jedit
Update the key JVMVersion in /Applications/jEdit.app/Contents/Info.plist using an editor like TextEdit to be 17.
<key>JVMVersion</key>
<string>17</string>
Launch jEdit
