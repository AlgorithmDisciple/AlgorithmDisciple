<h3 align="center">Jack Palmer | Red Team Operator |     Exploit Developer</h3>

-------------------

``` c
#include <stdio.h>
#include <unistd.h>

#define ESC "\x1B"
#define CLEAR_ESC ESC "[2J"
#define POSITION_ESC ESC "[%d;%dH"

void printFigure(int x, int y, int state) {
    const char *figure[5];

    if (state == 0) {
        figure[0] = " O ";
        figure[1] = "-|-";
        figure[2] = "/ \\";
    } else {
        figure[0] = " O ";
        figure[1] = "\\|-";
        figure[2] = " / ";
    }

    printf(CLEAR_ESC);
    for (int i = 0; i < 3; i++) {
        printf(POSITION_ESC "%s\n", y + i, x, figure[i]);
    }
}

int main() {
    int x = 10, y = 10;
    int state = 0;

    while (1) {
        printFigure(x, y, state);
        usleep(500000);
        state = !state;
    }

    return 0;
}
```
<div align="center">



-------------------

### Languages
![C++](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge&logo=C++&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC.svg?style=for-the-badge&logo=C&logoColor=black) ![Rust](https://img.shields.io/badge/Rust-000000.svg?style=for-the-badge&logo=Rust&logoColor=white)

### Platforms
![LeetCode](https://img.shields.io/badge/LeetCode-FFA116.svg?style=for-the-badge&logo=LeetCode&logoColor=white)

 <div>
