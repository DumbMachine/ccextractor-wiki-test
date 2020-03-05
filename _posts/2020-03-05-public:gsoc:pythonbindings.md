**Write Python bindings for CCExtractor**\\

Extend Python to use CCExtractor's library to access subtitles. You should export as much of CCExtractor as possible. At a minimum, it should be able to

- Open and close input video streams.\\
- For an open stream, get the list of programs.\\
- For a selected program, get the subtitles in various easy to use structures. You need to provide access to the original representation (for example, if it's US TV subtitles then a grid for CEA-608, if it's European DVB subtitles then a bitmap) as well as the conversion to usual formats such as .srt.\\

While CCExtractor itself uses its own library (lib_ccx), we are not aware of any other program using the library directly (as opposed to running CCExtractor and getting the generated file). This means - it's likely you will also need to modify the library itself to make it "sane enough" for this project.\\

We will also be prefer to have Cython code written instead of simple Python wrappers during the program as they offer better speed and compatibility with our existing codebase.

__**Related GitHub Issues**__\\
[Make the Python Scripts to run Python3](https://github.com/CCExtractor/ccextractor/issues/912)\\
[Python Bindings don't compile with build_library](https://github.com/CCExtractor/ccextractor/issues/879)

__**Related Github Commits**__\\
[Make Python3 Compatible Code](https://github.com/CCExtractor/ccextractor/commit/6e2ce11b26b28decb8967a43eeb0305e334048a8)\\


**Qualification tasks**\\
Take a look at [this page](https://ccextractor.org/public/gsoc/takehome).


