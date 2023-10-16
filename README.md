# antiprism_files

Here is a collection of input files for the 3D model polyhedra used to demonstrate three dimensional point groups in class. To view them, download the Antiprism software from here: 
https://www.antiprism.com/download/index.html
You can directly download Windows executables from that page. There is no MacOS version pre-compiled, but if you know how to compile source code, you can download the source and compile it yourself. (I don't know how that works on the Mac so please don't ask.)
Using the Windows version:
You should put acopy of the antiprism.bat file into the same folder as the files you want to view. Start the Antiprism command window by double clicking the antiprism.bat file.
For best results, try viewing a file by typing 
       antiview -xv -e 0.005 -E black filename
If the filename ends in ".off" make sure you type that as well. The necessary part is
       antiview filename
but the other options hide the vertices and give you nice black edges. Other commands you might want to explore are outlined on the https://www.antiprism.com/ website, as well as commands for some built-in models. Try using J## as a filename where ## is a number from 1 to 90 and see what you get!
