<div align = center>

# 42 Common Core Index

|Current Project|Current Rank|
|--|--|
|Fract-ol|Rank 02|

# Progress Graph

</div>

```mermaid
graph LR;
    libft-->get_next_line;
    libft-->ft_printf;
    libft-->Born2BeRoot;
    Born2BeRoot-->Minitalk;
    Born2BeRoot-->Fract-ol;
    Fract-ol-->Push_Swap
```

---

<div align=center>

# Norminette

</div>

The Norminette is a set of rules that 42 students have to follow. These rules were made so students would build better looking and better organized code, some of this rules include specific variables names for some elements like strcutures having to start with s_ or global variables having to start with g_. These rules also make for a better experience when trying to help other peers and when evaluating because it makes code easier to read and understand.

<div align=center>

# Moulinette

</div>

The Moulinette is an automated solving bot created by 42 that will evaluate the student throughout the piscine and the first 3 C projects of the common core. It's composed by a series of tests that will check if the code is giving the correct output, it the code doesn't use any forbidden functions and of course if it's according to the norm.

<div align=center>

---

# [Libft](https://github.com/mota494/42_libft)

![Static Badge](https://img.shields.io/badge/IDE-green?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=%230078d7&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Score-125%2F100-green?style=for-the-badge&logo=42&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Language-green?style=for-the-badge&logo=C&logoColor=%230078d7&labelColor=%23000000&color=%23ffffff)

</div>

Libft is the very first project of the 42 common core and makes the stundent go back to piscine days to recreate a bunch of functions and also introduces the concept of linked lists to the student through the bonus part.

The project is organized in three main parts:
- A set of libc functions
- Some additional 42 functions
- The bonus part

The libc functions contain some usefull functions like `atoi` or `calloc` that will be usefull in every project from the common core, making these are a good way to get back to speed after the months between passing the piscine and starting the cursus

The additional 42 functions aren't functions that already exist so the stundent doesn't have anything to be a guide, this encourages the student to write his own tests and get really creative on trying to break his own code.

The bonus part is a set of functions that revolve around linked lists a concept that will be extremely usefull for everything that's C related as it's a fundamental part of the programming language and also presents the student with new concepts and challenges.

---

<div align = center>

# [ft_printf](https://github.com/mota494/42_ftprintf)

![Static Badge](https://img.shields.io/badge/IDE-green?style=for-the-badge&logo=CLion&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Score-100%2F100-green?style=for-the-badge&logo=42&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Language-green?style=for-the-badge&logo=C&logoColor=%230078d7&labelColor=%23000000&color=%23ffffff)

</div>

Everyone that has written an "Hello World!" in C already knowns what printf is, unfurtunately, 42 students are not allowed to use printf and how do we fix that ? Creating our own of course, this project is recreating the basic functionality of printf for the mandatory part and if the student really wants to go beyond the bonus part challenges them by giving a few more things to do.

These project is unlocked right after libft is submitted and evaluated by the Moulinette and it was my 2nd project of common core. It caught me by surprise because the basic functionality of the printf is well, basic, the project makes the student learn about variadic functions a type of function that can receive an arbitrary ammount of argumments.

---

<div align = center>

# [Get Next Line](https://github.com/mota494/42_get_next_line)

![Static Badge](https://img.shields.io/badge/IDE-green?style=for-the-badge&logo=CLion&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Score-100%2F100-green?style=for-the-badge&logo=42&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Language-green?style=for-the-badge&logo=C&logoColor=%230078d7&labelColor=%23000000&color=%23ffffff)

</div>

GNL or get next line was my 3rd project on the common core and it was a challenging project because of the norm and also the restraints that are given to the student, these restraints make a project that otherwise be a basic project into a kinda hard and frustrating experience. 

It's a simple function that receives a file descriptor and returns line by line the contents of the file received. Example, if the file has the contents presented below and the functions is called once it will return `42 common core` and if it's ran again it will return `42 norm` and so on.

```file.txt
42 common core
42 norm
42 mouli
```

These project makes the student learn at least a little about file descriptors and also it's the first project that the student will have to run into memory management a key elemment in C.


<div align = center>

# [Born 2 Be Root](https://github.com/mota494/42_Born2BeRoot)

![Static Badge](https://img.shields.io/badge/Virtual%20Machine-green?style=for-the-badge&logo=VirtualBox&logoColor=%23183A61&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Score-100%2F100-green?style=for-the-badge&logo=42&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Operating%20System-green?style=for-the-badge&logo=Debian&logoColor=%23A81D33&labelColor=%23000000&color=%23ffffff)

</div>

Born2BeRoot is a very infamous project in 42, some call it their first "nightmare", it's a challenging project that introduces the student to the world of virtualization. It challenges the student by giving a few features that his virtual machine should have and to make that happen the student has to dive down in old forums, documentation pages and discover some neat functionality of the UNIX system. 

The project allows the student to build his virtual machine in Debian or Rocky (RIP centOS), i choose Debian thanks to the more user friendly experience and the great ammount of documentation that already exists since the OS is so loved by a large community

During the project i developed my own B2BR guide that helped some of my peers get through the project.

These was the last project before my first exam, this index will not talk about my exams.

---

<div align = center>

# [Minitalk](https://github.com/mota494/42_minitalk)

![Static Badge](https://img.shields.io/badge/IDE-green?style=for-the-badge&logo=CLion&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Score-115%2F100-green?style=for-the-badge&logo=42&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Language-green?style=for-the-badge&logo=C&logoColor=%230078d7&labelColor=%23000000&color=%23ffffff)

</div>

Minitalk is a project that has as it's main challenge learning about UNIX signals

<div align = center>

# [Fract-ol](https://github.com/mota494/42_fractol)

![Static Badge](https://img.shields.io/badge/IDE-green?style=for-the-badge&logo=Neovim&logoColor=%2357A143&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Score-%3F%2F100-green?style=for-the-badge&logo=42&labelColor=%23000000&color=%23ffffff)
![Static Badge](https://img.shields.io/badge/Language-green?style=for-the-badge&logo=C&logoColor=%230078d7&labelColor=%23000000&color=%23ffffff)

</div>

(IN PROGRESS)
