# `text-spacing-trim` bug reproduction

https://tats-u.github.io/text-spacing-trim-test/

## Remote font warning

This page uses a huge remote font.

- Firefox & Chrome (>= 145): 14MB (WOFF2)
- Chrome (<= 144): 14MB (WOFF2) + 37MB (TrueType) = **51MB**
