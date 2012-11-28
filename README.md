src-highlite-unity
==================

gnu source-highlight compatible with Unity

gnu source-highlight( http://www.gnu.org/software/src-highlite/ ) is a syntax hilighting software by GNU.
This project extends source-highlight and gives highlight feature for C# and JavaScript for Unity( http://unity3d.com/ )

How to install:
------------
- install source-highlight
- copy files in src to configuration directory (if you use configure&make, it should be located somewhere in /usr/local/share/source-highlight/ )

How to use:
-----------
Here is an example of how to use:

JavaScript
> $>source-highlight -s javascript -f html -i foo.js -o foo.html

C#
> $>source-highlight -s unitycsharp -f html -i var.cs -o var.html

for further use of source-highlight, please visit http://www.gnu.org/software/src-highlite/

