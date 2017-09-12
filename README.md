# LaTeXSusbstitutionsPlist
Replace LaTeX math escape strings with unicode characters in Mac OS by building Text Subsitutions.plist. 

This takes more than 2400 LaTeX math escape strings (e.g. \alpha) from a built-in dictionary in the Julia language and formats them as the Mac OS file "Text Substitutions.plist"

# Instructions

1. Get a recent version of [Julia](https://github.com/JuliaLang/julia). Downloadable at https://julialang.org/downloads/
2. Run `your/path/to/julia latex_symbols_to_plist.jl` in a working directory to generate `Text Substitutions.plist`.
3. Navigate Finder to the working directory.
4. Open `System Preferences > Keyboard > Text pane`
5. Save your existing text substitutions by selecting them from the list in the pane and dragging them to the desktop. This will create `Text Substitutions.plist`.
6. Drag the new `Text Substitutions.plist` with LaTeX symbols into the list.
7. Check Correct spelling automatically
