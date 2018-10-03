# Assembly-OS-X

Assemble the above source to an object file, hello_world.o, in the Mach-O format.

`$ nasm -f macho hello_world.asm`

Link the object file to produce the hello_world executable.

```$ ld -o hello_world -e main hello_world.o```

Run the executable.

```$ ./hello_world```

hello, world!
