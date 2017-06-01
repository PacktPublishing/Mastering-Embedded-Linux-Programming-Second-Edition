# Mastering Embedded Linux Programming – Second Edition

This is the code repository for [Mastering Embedded Linux Programming - Second Edition](https://www.packtpub.com/networking-and-servers/mastering-embedded-linux-programming-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787283282), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
Embedded Linux is widely used and there’s a need of selection, organization, and presentation of embedded linux.

Mastering Embedded Linux Programming 2nd edition takes you through the product cycle and gives you an in-depth description of the components and options that are available at each stage.The aim of this book is to help you create efficient and secure embedded devices using Linux. You will begin by learning about tool chains, boot loaders, the Linux kernel, and how to configure a root file system to create a basic working device which will be followed by using Buildroot and Yocto to speed up and simplify the development process .Key topics include basic system set-up, toolchains, accessing hardware at a low-level, robustness, real-time behavior and security.Its purpose is to make you aware how to construct an embedded Linux using open source projects to produce a robust and reliable system by understanding about Linux 4.9 Yocto’s Pyro 2.3 along with the latest Buildroot.

By the end of the book , you will be able to derive a wide choice of solutions to solve a particular problem.

## Instructions and Navigation

All of the code is organized into folders. For example, Chapter04.


The code will look like the following:
```
/dts-v1/;
/{
    model = "TI AM335x BeagleBone";
    compatible = "ti,am33xx";
    #address-cells = <1>;
    #size-cells = <1>;
    cpus {
        #address-cells = <1>;
        #size-cells = <0>;
        cpu@0 {
            compatible = "arm,cortex-a8";
            device_type = "cpu";
            reg = <0>;
        };
    };
    memory@0x80000000 {
        device_type = "memory";
        reg = <0x80000000 0x20000000>; /* 512 MB */
    };
};
```

At the end of the ROM code phase, the next stage bootloader is present in on-chip memory and the ROM code jumps to the beginning of that code.

## Related Embedded Linux Programming Products

* [GNU/Linux Rapid Embedded Programming](https://www.packtpub.com/hardware-and-creative/gnulinux-rapid-embedded-programming?utm_source=github&utm_medium=repository&utm_campaign=9781786461803)

* [Mastering Kali Linux for Advanced Penetration Testing - Second Edition](https://www.packtpub.com/networking-and-servers/mastering-kali-linux-advanced-penetration-testing-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787120235)

* [Mastering Linux Kernel Development](https://www.packtpub.com/application-development/mastering-linux-kernel-development?utm_source=github&utm_medium=repository&utm_campaign=9781785883057)

### Suggestions and Feedback

[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
