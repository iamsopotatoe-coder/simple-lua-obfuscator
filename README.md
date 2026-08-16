# simple-lua-obfuscator
A html weekend project of a lua obfuscator, does not provide alot of protection and may break some of your code.

What it does:
- Strips comments and extra whitespace
- Renames local variables to random junk
- Encodes string literals as string.char(...) calls
- Encodes number literals as small arithmetic expressions
- Inserts junk statements
