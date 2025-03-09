# Libft - 42 Wolfsburg project about reinventing the wheel for educational purposes!

Usualy I recommend reading [the subject](en.subject.pdf) for better understanding the project but.. Like I said, this project is about reinventing the wheel which is pretty straight forward. I recreated standard libc functions like `strlen`, `bzero`, `memset`, `atoi`... After which I created some subject-specific functions like `ft_itoa` (reverse atoi) and learned how to use linked lists.

## Usage

After cloning the repository and creating your main file include `libft.h` in it and run:

```bash
make
cc my_program.c -L. -lft -o my_program
```

### Additional make rules

```bash
make clean    # cleanup object files
make fclean   # cleanup all output files
make re       # clean all output files and run make again
```
The project resulted in a solid understanding of C language fundamentals, manual memory management and linked lists. It also introduced me to tools such as `GDB` and `Valgrind`.
