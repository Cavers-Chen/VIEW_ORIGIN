# VIEW_ORIGIN
## Introduction
Hey! This is my CG project and I want to make a tiny engine, which contains abilities to render a scene and simulate some specific physical movements.
I'll update my code periodically and make some manuals on my GitHub project website.
Wish you have fun!

## Dependence 

- Eigen

This project tries not to include the third part lib, but Eigen is an efficient lib, which could save our time to implement the Matrix lib. You can easily configure this lib by searching the tutorial on the internet.

the website of Eigen is below
```
https://eigen.tuxfamily.org/index.php?title=Main_Page
```
- Easyx

Also, considering if we use .pmm file or Windows Api to represent our result, it would be time-consuming when our code processes the results(the results can't be directly seen),and it's a little difficult to learn new stuff. To focus only on our engine, I choose the easyx lib to convert our pixel data to image immediately. 

the website of easyx is below
```
https://easyx.cn/
```
