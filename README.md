Find Objects:

The executable I wrote scans PNG drawings (AutoCAD/MicroStation exports) for symbols (a library which I have supplied for viewing in the folder "Find Objects - Templates"). The results of the symbol search are in the folder "Find Objects". Each symbol that has been found is highlighted with a red rectangle.

Line Tracing:

The executable goes through all symbols detected by the Find Objects executable and performs a search for all neighboring symbols. The purpose of this is to create an a set of adjacency lists (one for each detected symbol) which is then used to create Boolean logic equations. The line tracing can be visualized in the videos I have supplied. Once the line tracing has completed for a symbol, arrows are drawn on the PNG drawing to display the results. A red arrow indicates that the symbol being pointed to by the arrow is a right-neighbor of the symbol that the arrow originates from. A green arrow means the symbol being pointed to by the arrow is a left-neighbor of the symbol that symbol originates from.
