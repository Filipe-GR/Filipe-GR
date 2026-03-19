# Filipe G.R.

> CTO and Co-founder at [Ative o Fit](https://ativeofit.com/) | Computer Science Student at [UFLA](https://ufla.br)

Much like the nature of a fractal, my approach to software engineering is to build scalable, robust, and strictly deterministic systems grounded in precise fundamentals.

### Knowledge Base & Articles
I maintain a public archive to document my research, architectural designs, and technical articles. It is a space where I mostly share knowledge.
* [Access Knowledge Base](https://filipe-gr.github.io/knowledge-base/)

---

### Technical Highlights

**[Floatless: Q16.16 & Q32.32 Deterministic Math in C++ (128-bit safe)](https://gist.github.com/Filipe-GR/3004193aa8a7daa2ed1a9871269d1f16)**
A C++ library for fixed-point arithmetic (Q16.16 and Q32.32), architected to guarantee strict determinism in cross-platform simulations by entirely suppressing the inconsistencies inherent to floating-point numbers.
* **Strict Type Safety:** Explicit constructors that block accidental float/double conversions, ensuring data integrity within the simulation.
* **Safe Q32.32 Arithmetic:** Native 128-bit support in GCC/Clang, implementing a manual 64x64->128-bit fallback to bypass overflow risks in 32-bit compilers (MSVC).
* **High-Performance Trigonometry:** Sine and Cosine functions mapped to 1024-entry look-up tables (LUT), refined via linear interpolation (lerp).
* **Bitwise Integer Square Root:** Highly optimized bit-shift algorithm, replacing the inefficiency of the Newton-Raphson method in a fixed-point context.

---

### Contact
* **Email:** filipegarciar@gmail.com
* **Instagram:** [@filipe.g_r](https://www.instagram.com/filipe.g_r?igsh=aGVuejRlcTN5bTdu)
