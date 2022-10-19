# Coding style
## Typing (variables only) :
| Type      | Prefix  |
|-----------|---------|
| const     | cst_    |
| globals   | glb_    |
| locals    | loc_    |
| pointer   | ptr_    |
| string    | str_    |
| struct    | sct_    |
| typedef   | t_      |
| array     | a_      |
| unsigned  | uX_     |
| char      | c_      |
| short     | s_      |
| long      | l_      |
| long long | ll_     |
| float     | f_      |

```c
#define CONST_IN_CAPS
```
Make a common file for global imports and defines.

Use `#ifndef` to segregate the WIN32 and linux platforms.