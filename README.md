# paranoia
`c` version of William M. Kahan's `paranoia` program to check CPU floating-point math for correctness

William M. Kahan is the father of the IEEE-754 standard for floating-point arithmetic in modern
computers. On the 19th of April, 1983, (41 days before my birth) Kahan released a `MS BASIC` 
program to check for the corectness of the floating-point arithmetic implementation on any given
machine. This original program was translated into `Pascal` by B. A. Wichmann on 18 Jan. 1985 and
subsequently into `c` by David M. Gay (AT&T Bell Labs) & Thos Sumner (UCSF) between 1985 and 1986.
This is the version provided here along with a convenient makerfile (adapted from one written by 
Andrey Vladimirov of Colfax Intl.) to compile and run the program.

To make and run `paranoia` on the CPU, type `run-cpu`.
To make and run `paranoia` on an Intel Xeon Phi, type `run-mic`.

Read the original Kahan article in the 1985 issue of [BYTE](https://archive.org/stream/byte-magazine-1985-02/1985_02_BYTE_10-02_Computing_and_the_Sciences#page/n222/mode/1up)
magazine for morte details. Another classic read is David Goldberg's [What Every Computer Scientist
Should Know About Floating-Point Arithmetic](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html).
