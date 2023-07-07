<h3 align="center">Reverse Engineer | Malware Analyst | Security Analyst</h3>

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
![ASSEMBLY](https://img.shields.io/badge/_-ASM-6E4C13.svg?style=for-the-badge) ![C](https://img.shields.io/badge/_-C-555555.svg?style=for-the-badge) ![C++](https://img.shields.io/badge/_-CPP-F34B7D.svg?style=for-the-badge) 
  


 <div>
