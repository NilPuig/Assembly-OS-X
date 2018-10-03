# Assembly-OS-X

Assemble the above source to an object file, hello_world.o, in the Mach-O format.

`$ nasm -f macho hello_world.asm`

Link the object file to produce the hello_world executable.

```$ ld -o hello -e mystart hello.o```

Run the executable.

```$ ./hello```

hello, world!
