<h3 align="center">Jack Palmer | Low-Level Engineer</h3>

-------------------

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
<div align="center">



-------------------

### Languages
![C++](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge&logo=C++&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC.svg?style=for-the-badge&logo=C&logoColor=black) ![Rust](https://img.shields.io/badge/Rust-000000.svg?style=for-the-badge&logo=Rust&logoColor=white)

### Platforms
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42.svg?style=for-the-badge&logo=TryHackMe&logoColor=white) ![HackTheBox](https://img.shields.io/badge/Hack%20The%20Box-9FEF00.svg?style=for-the-badge&logo=Hack-The-Box&logoColor=black) ![LeetCode](https://img.shields.io/badge/LeetCode-FFA116.svg?style=for-the-badge&logo=LeetCode&logoColor=white)

 <div>
