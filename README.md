# 2TPS
Converts Tak Notation into the TPS format

The converted TPS will be appended to a file called "TPS.txt"

If you already have Python 3 installed, you can just run the python file from the Py Only folder from any Python IDE—it doesn't require any modules that are not included with Python by default. You will not need any of the files from the Parser folder if you don't want to use the .exe version of the parser.

If you don't have Python 3 installed, you will need to use the parser.exe from the parser folder. 

When typing out the PTN file name, you will need to write out the entirety of the name, including the extension. I would advise changing your file's name, if temporarily, to avoid this hassle. 

PlyCount is how many moves deep you would like to go, essentially. Ply 3 is considered white's first self-chosen move. Ply 20, for example, is Move 10 after black has moved. You can input a single ply number, or you may input an arbitrary number of ply count positions separated by commas. If you input any number that is higher than the total number of plys in the game, then the final game position will be printed. 
