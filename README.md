# Arc

Minimalistic Kernel for Learning

### Todo

- [x] Bootloader
  - [x] Real Mode
  - [x] Protected Mode
  - [x] Long Mode
  - [x] Give control to Kernel
- [ ] Includes
  - [x] Ample
    - [x] Printing Utilities (`<arc/print.h>` - `printk`)
  - [ ] LibC
    - [x] Stdio
      - [x] `sprintf` - format string
    - [ ] Stdlib
      - [x] `intlen` - return length of an integer
      - [ ] `malloc` - allocate memory
      - [ ] `free` - free memory
    - [x] String
      - [x] `strlen` - give length of a string
    - [x] Stdarg
      - [x] Variadic Functions (`va_start`, `va_arg`)
- [ ] Kernel
  - [ ] Interrupts
  - [ ] Processes
  - [ ] Scheduler
  - [ ] Memory Allocation (`lib/stdlib.h`)
    - [ ] `malloc`
    - [ ] `free`
  - [ ] User Mode
    - [ ] Switch to user mode
    - [ ] Virtual File System (VFS)
    - [ ] Stdin
    - [ ] Stdout
  - [ ] System Calls
  - [ ] Console Interface
    - [x] Logs
    - [ ] Initialize keyboard input
    - [ ] Commands
      - [ ] `pwd`
      - [ ] `ls`
      - [ ] `cd`
      - [ ] `mkdir`
      - [ ] `touch`
      - [ ] `cat`
      - [ ] `echo`
