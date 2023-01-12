# Better default settings for VS Code

_This is part of the [Mastery for VS Code](https://andrecasal.com/courses/mastery-for-vs-code) course._

These are my refined settings for VS Code.

If you don't have the Operator Mono Font with ligatures enabled, you should probably delete these three lines:
```json
"editor.fontFamily": "OperatorMonoLig-Light, Menlo, Monaco, 'Courier New', monospace",
"editor.fontSize": 13,
"editor.fontWeight": "600",
```

The line:
```json
"C_Cpp.clang_format_style": "{ BasedOnStyle: Chromium, IndentWidth: 3, TabWidth: 3, UseTab: Always, ColumnLimit: 0}"
```
pertains to the [C/C++ extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools), but I found the default formatting so annoying I had to keep that in my settings.json file. If you don't code in C, feel free to delete this line.
