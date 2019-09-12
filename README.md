# cv - Michael Joshua Ryan (aka. luser droog)
My resume is intended to be as clever as possible, which consequently
required a great deal of debugging.

The resume is written in PostScript to illustrate my fluency with the PostScript
language. It contains its own typesetting engine and allows markup codes to be
embedded in strings or called explicity. 

The resume program is a *quine*, which is a program which produces its own source code. 
When printed or converted to pdf, the first page is the resume content, 
and the reverse side (the program sets duplex mode) is the complete source code.

The source code is divided into the document portion and the quine portion. 
The quine code is *parasitic* in the sense that it re-uses the typesetting code
from the document to do the printing of the source lines. 

The quine portion is also parasitic in the sense that it can be *cut off* and the 
document code will simply produce the first page of the resume content.
