# The Debugger Rosetta Stone
I use **LLDB** (macOS default). If you are using **GDB** (Linux default), here is some translations.

| Action | LLDB Command (macOS) | GDB Command (Linux/Windows) |
| :--- | :--- | :--- |
| **Start Program** | `lldb ./program` | `gdb ./program` |
| **Run** | `run` (or `r`) | `run` (or `r`) |
| **Set Breakpoint** | `b main` | `b main` |
| **Next Line** (Step Over) | `n` | `n` |
| **Step In** | `s` | `s` |
| **Print Variable** | `p my_var` | `p my_var` |
| **Show Registers** | `register read` | `info registers` |
| **Read Memory** (Hex) | `memory read -f x -c 4 0x7fff...` | `x/4x 0x7fff...` |
| **Disassemble** | `disassemble --name main` | `disassemble main` |
| **Quit** | `q` | `q` |

**Pro Tip:** In LLDB, you can just type `gui` to get a visual interface similar to GDB's TUI!