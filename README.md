# Sandwich script
*Toy language model in development.*

Sandwich(sand) script should be translated into machine code in browser via webassembly module written in Rust. Lately this machine code can be executed in webassembly itself.

Possible architecture:

```
+-----------------+    +----+    +--------+
| Sandwich Script | => | JS | -> | Module |
+-----------------+    +----+    +--------+
```

```
+--------+    +----+     +---------------+
| Module | -> | JS | <-> | Compiled sand |
+--------+    +----+     +---------------+
                ∧
                ∨
           +---------+
           | Web API |
           +---------+
```
# About script language

Sandwich script should be strict typed language with data oriented design concept. 

