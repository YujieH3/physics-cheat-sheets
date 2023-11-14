# Physics Cheat Sheets

The plan would be to make a general cheat sheet covering the important parts in physics and mathematics for physicists (which is different to math for mathematicians) to make my life (the life of a cosmology master student) easier without feeling like I have learned nothing in my expensive education every now and then. And it would be great if others also find these useful. 

In the spirit of cheat sheets for quickly looking up facts rather than an encyclopedia, each section will be kept under at most two pages. Some of them might contain unimportant details because I take them to tests. The main.tex file combines all .tex files (except ones in the legacy folder) and each .tex file is also compilable on its own thanks to the `subfiles` package. Because `subfiles` uses the preambles of the main file to compile each "subfiles", you need to compile other .tex files with the main.tex in the same directory. You can either use the main file in one go or check each section individually.