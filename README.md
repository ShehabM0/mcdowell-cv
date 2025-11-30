## Font Notice for UNIX-Based Users (macOS / Linux)
- This project does **not** include the `Calibri` font.
> [!WARNING]
> Since `Calibri` is owned by Microsoft and is not open-source. Its source files are not publicly available and cannot legally be modified or - redistributed without permission.
- The PDF will fail to compile If you attempt to compile the document using `LuaLaTeX` on macOS or Linux.
- Instead you can use any freely available alternative such as `Carlito` or `FreeSerif` which is already being used in this project.

## Build Instructions
- Make sure `lualatex` (see https://www.luatex.org/download.html) is installed on your machine and is available in the terminal or a command line client of your choice.
- In the terminal or a command line client of your choice, go to the folder containing `McDowell_CV_Template.tex` and `mcdowellcv.cls`, and run the following command: `lualatex McDowell_CV_Template.tex`.
> [!WARNING]
> `lualatex` may suspend the compilation process and waiting for an input which you may want to run without stopping by pressing `R`.
```sh
Type <return> to proceed, S to scroll future error messages,
R to run without stopping, Q to run quietly,
I to insert something, E to edit your file,
1 or ... or 9 to ignore the next 1 to 9 tokens of input,
H for help, X to quit.
```
- Alternatively you can just run `lualatex -interaction=nonstopmode McDowell_CV_Template.tex`.
