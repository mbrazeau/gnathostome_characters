# gnathostome_characters
A database and interface for gnathostome characters

All character definitions, taxa, and the data matrix, as well as inclusion/exclusion settings and other character settings
are stored within the MATRIX_MASTER.nex file. This is the file you should use for phylogenetic analyses.

Users who wish to create their own version of the matrix can use this file. However, users are invited to fork this repository and store and maintain their own version of it. Advice below details some best practices for keeping this up to date.

The matrix is constructed and edited in Mesquite, so users should also perform all edits in that same software to ensure maximum and persistent
compatibility.

When the character list and definitions are edited, users should re-generate the HTML file for the character list using Mesquite by exporting as HTML.
Overwrite the old MATRIX_MASTER.html file with this new file. 

Similarly, if the list of references and sources is amended (see the Word file), then this should also be safed as a basic HTML file (which MS Word can export for you). References are maintained in *Systematic Biology* format.
