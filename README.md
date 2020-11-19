# Mixed-language-programming using ALP and C

There are times when programs need to call programs written in other languages referred as mixed language programming. For example, when a particular subprogram is available in a language other than language you are using, or when algorithms are described more naturally in a different language, you need to use more than one language. Mixed-language programming always involves a call to a function, procedure, or subroutine. Mixed-language calls involve calling functions in separate modules. Instead of compiling all source programs with same compiler, different compilers or assemblers are used as per the language used in the programs. Microsoft C supports this mixed language programming. So it can combine assembly code routines in C as a separate language. C program calls assembly language routines that are separately assembled by-MASM (MASM Assembler). These assembled modules are linked with the compiled C modules to get executable file. 

As we all know that mixed language programming is supported by C.
Other high level languages that support assembly language programming: C++, Basic, FORTRAN


Advantages of mixed language programming:
Programming languages are fundamentally abstractions that assist in helping you tell a computer what to do. As they are abstractions, this means that they hide some of the details and so simplify the overall task, enabling you to comprehend how to do some particular piece of programming without having to understand the whole thing at once. But that hiding also means that they restrict what you can do: going outside the abstraction is hard, and so also is having to build a lot of new abstractions on top of the base level provided by the language.
The net effect of this is to mean that a particular programming language has a range of programming tasks that it is well suited to, but it is not going to be good for everything. A low-level programming language allows you to do low-level work, often that happens to be performance critical.
The best way out of this situation where a programming language that can do one task isn't good for others is to use multiple programming languages. Let each language focus on doing the tasks that it is good at, and then transfer control to code written in another language for other parts. It's specialization (and also componentization) and it is a good thing indeed.



Disadvantages of mixed language programming:
Any time you are working in two languages there is the possibility for conflicts which can be tricky to debug . You might use more memory resources than you can afford to spare carrying multiple languages and their libraries during your analysis. The annoyance of switching grammar in medias res might be real depending how good you are at thinking in two different linguistic veins at one time . They would be redundant in most cases because most of the analytical work you can easily do in one you can do in the other.




