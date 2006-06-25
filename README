This is a mirror of http://www.vim.org/scripts/script.php?script_id=1520

This script is for vim 7.0 or higher it provides an omnifunc cppcomplete function.
You can use the omni completion (intellisense) in C and C++ files.
This is a full vim script and you only need a ctags database.

It's not finished yet but now you can :

    -   Complete namespaces, classes, structs and union members.
    -   Complete inherited members for classes and structs (single and multiple inheritance).
    -   Complete attribute members eg: myObject->_child->_child etc...
    -   Complete type returned by a function eg: myObject->get()->_child.
    -   Complete the "this" pointer.
    -   Complete a typedef.
    -   Complete the current scope (global and class scope).
    -   Complete an object after a cast (C and C++ cast).
    -   Complete anonymous types (eg: struct {int a; int b;}g_Var; g_Var.???). It also works for a typedef of an anonymous type.


Notes :
    -   The script manage cached datas for optimization.
    -   Ambiguous namespaces are detected and are not included in the context stack.
    -   The parsed code is tokenized so you can run a completion even if the current 
        instruction has bad indentation, spaces, comments or carriage returns between words
        (even if it is not realistic).

ScreenShots :

    http://vissale.neang.free.fr/Vim/OmniCppComplete/ScreenShots/screenshots.htm



