# Hello! I'm Federico Benelli
I'm a Chemical Engineer now doing my PhD in thermodynamics, specifically
in designing computational algorithms for PVT simulation of reservoir fluids.
My focus is mainly on phase diagrams tracing (isoplets, isotherms) of multicomponent
mixtures using Equations of State.

I mostly program in _Python_ and _Fortran_, nowadays I'm digging into
bridging between the two with _f2py_, mostly to take old code into nice modern
interfaces or to make new and high-performing code with ease of use.

My principal projects are:

- [fenveloeps](https://www.github.com/fedebenelli/fenvelopes) Fortran software
  for multicomponent systems phase diagrams tracing with Equations of State.
  Right not it provides the possibility of calculation of PT (isoplets) and
  Px (isotherms) using Cubic Equations of State.

- [yaeos](https://www.github.com/fedebenelli/yaeos), a Fortran library for
  equations of state related calculations, with a heavy emphasis in
  ease of extensibility and usage. Using both automatic differentiation
  and analytical derivatives approaches to exploit the best of both worlds.

- [PyForFluids](https://www.github.com/fedebenelli/pyforfluids), a Python
  module that estimates thermodynamic properties of fluids based on Equations
  of State. It uses Fortran code in the background to assure high performance
  in the calculations.

## Hobbies
Besides my work, I'm also a Linux enthusiast, right now I'm rocking Arch Linux
in both my main desktop and my Laptop. I keep in sync most of the files 
between both computers with `SyncThing`, my dotfiles are in their own repo
[dotfiles](https://www.github.com/fedebenelli/dotfiles), each computer has it's
own branch.
