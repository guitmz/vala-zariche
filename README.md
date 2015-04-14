# Linux.Zariche: a Vala virus

Vala is an object-oriented programming language with a self-hosting compiler that generates C code and uses the GObject system. Vala is syntactically similar to C# and and rather than being compiled directly to assembly or to another intermediate language, Vala is source-to-source compiled to C, which is then compiled with a platform's standard C compiler, such as GCC.

You can also create VAPI files which are basically native C (not C++) functions you can import to Vala code. Being a language that is converted into plain and pure C, Vala code can also run on Windows (with the necessary code optimizations, of course).

Anyway I was decided to write a prepender in this language, the first (binary) virus ever written so far in Vala. It's named Linux.Zariche and there are two variants available so far.

* Linux.Zariche.A original release, simple ELF infector (prepender).
* Linux.Zariche.B uses AES encryptation via external library (vapi).

