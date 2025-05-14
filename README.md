[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/bPoO8GTw)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19527756&assignment_repo_type=AssignmentRepo)
Gujarati Language Compiler 👤 Devansh Oad 🎓 EN ID: 22000773

Project Overview This is a simple compiler created using Flex (Lex) and Bison (Yacc) for a custom programming language that uses Gujarati transliterated keywords. The compiler reads code from an input.txt file, parses it, and generates intermediate code or parsing validation through defined grammar rules.

📁 Files Included File Name Description 1.l Lex (Flex) source file for lexical analysis 1.y Yacc (Bison) source file for parsing rules input.txt Sample program written in the custom language

🛠 How to Compile & Run ⿡ Generate parser and lexer files: bison -d 1.y flex 1.l gcc 1.tab.c lex.yy.c -o a

⿢ Run the compiler: a.exe

📦 Dependencies Flex Bison GC
