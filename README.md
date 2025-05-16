# Holy C

> [!NOTE]
> All infomation is easily found on many different sites, however we use more sites that will be listed [Here](#Sources)



## History

The origin of C is closely tied to the development of the Unix operating system, originally implemented in assembly language on a PDP-7 by Dennis Ritchie and Ken Thompson, incorporating several ideas from colleagues. Eventually, they decided to port the operating system to a PDP-11. The original PDP-11 version of Unix was also developed in assembly language.

Thompson wanted a programming language for developing utilities for the new platform. He first tried writing a Fortran compiler, but he soon gave up the idea and instead created a cut-down version of the recently developed systems programming language called BCPL. The official description of BCPL was not available at the time, and Thompson modified the syntax to be less 'wordy' and similar to a simplified ALGOL known as SMALGOL. He called the result B, describing it as "BCPL semantics with a lot of SMALGOL syntax". Like BCPL, B had a
bootstrapping compiler to facilitate porting to new machines. Ultimately, few utilities were written in B because it was too slow and could not take advantage of PDP-11 features such as byte addressability.

In 1971 Ritchie started to improve B, to use the features of the more-powerful PDP-11. A significant addition was a character data type. He called this New B (NB). Thompson started to use NB to write the Unix kernel, and his requirements shaped the direction of the language development. Through to 1972, richer types were added to the NB language: NB had arrays of int and char. Pointers, the ability to generate pointers to other types, arrays of all types, and types to be returned from functions were all also added. Arrays within expressions became pointers. A new compiler was written, and the language was renamed C. The C compiler and some utilities made with it were included in Version 2 Unix, which is also known as Research Unix.

### Images

![Concepts of C language](https://github.com/user-attachments/assets/01357239-13f0-48ba-a9c8-4c9a6d887a8f)
![Timeline of C language](https://github.com/user-attachments/assets/a43fdb83-7762-4dcf-936e-c70139025c15)

# Holy C (repo)

This repository is all about featuring cool projects made with C! Each folder will contain a readme. Here is the folder structure of this repo!

*edit:* This will contain projects submitted via PR's, My personal projects, my friends projects, or anything i like!

## File Structure (repo)

> [!WARNING]
> This is just the general scope of this & this part will ***NOT*** be updated often.

```
.
├── README.md
├── My-Projects/
│   ├── DevDaisy
│   ├── Server25-OS-depricated
│   └── Shitty-C-Linker
├── Friends-Projects
├── Projects-I-Like/
│   └── cvpn
└── Tools/
    ├── Libraries/
    │   ├── SDL
    │   └── Raylib
    ├── Apps/
    │   ├── FastFetch
    │   ├── OBS-Studio
    │   └── VLC
    ├── Linux-Kernel
    └── goaccess
```

## Sources 

1. [Wikipedia](https://en.wikipedia.org/wiki/C_(programming_language))
2. [The offical C website](https://www.c-language.org/)

## Contributing

To contribute please submit a `pull request` with the following information.

### Contributing Template

```
Name of project:
Github Link:
Project Website *if any*:
Your github username:
Is this your project?:
give a brief description of this project:
```
