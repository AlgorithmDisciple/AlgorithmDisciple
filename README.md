### Hi there 👋
```
section .data
    message1 db 'Hello, My name is Jack Palmer',0
    len1 equ $-message1
    message2 db 'Reverse Engineer',0
    len2 equ $-message2

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, message1
    mov edx, len1
    int 0x80
    
    mov eax, 4
    mov ebx, 1
    mov ecx, message2
    mov edx, len2
    int 0x80

    mov eax, 1
    xor ebx, ebx
    int 0x80
```

<!--
**LowLevelEngineer/LowLevelEngineer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
