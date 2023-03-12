---
title: '"There is Rust in the Kernel!" - A Closer Look at the Controversy Surrounding Rust in the Linux Kernel'
date: 2022-12-26T17:42:00+02:00

categories: ['Video']
tags: ['Mental Outlaw', 'Linux', 'Rust']
author: 'ChatGPT'

# Set your video id for
youtube: "YCNvLJwSEEQ"
---

The recent release of the Linux kernel 6.1 has sparked controversy due to the inclusion of support for the Rust programming language. As Mental Outlaw mentions in the video "There is Rust in the Kernel!", Rust is a fast, low-level systems programming language that is known for its memory safety. This means that Rust code is guaranteed to be free of certain types of vulnerabilities, such as null pointer dereferences, use after free errors, and buffer overflows, which are commonly caused by memory errors. This is a significant advantage, as approximately three-fourths of all vulnerabilities found in software are the result of memory errors.

<!--more-->

However, not everyone agrees that Rust is a good fit for the Linux kernel. Drew Devault, a knowledgeable C programmer and colonel hacker, has written a blog post critiquing the decision to include Rust in the kernel. Devault argues that there is nothing that Rust can do for the kernel that C can't already do, and that it is possible to write safe code in C. Devault also raises the point that Rust is owned by Mozilla, which could raise concerns about the long-term stability and support for the language.

While it is true that C has been the primary programming language used in kernel development, and that it is possible to write safe code in C, it is also important to consider the benefits of using Rust. Rust has a strong focus on safety and reliability, which can help to reduce the number of vulnerabilities in the kernel. Additionally, Rust's memory safety can help to prevent certain types of vulnerabilities that may be difficult to eliminate using C.

It is also worth considering the potential drawbacks of using Rust in the kernel. As Devault points out, there are certain situations where using unsafe code is necessary in kernel development, and it may be more difficult to do this in Rust. Additionally, the fact that Rust is owned by Mozilla could raise concerns about the long-term stability and support for the language.

Ultimately, the decision to include Rust in the Linux kernel is a complex one that requires consideration of both the potential benefits and drawbacks of using the language. While Rust may have some advantages for the kernel, it is important to have a diverse set of programming languages in the kernel to ensure that it is as robust and secure as possible. Ultimately, the best course of action will depend on the specific needs and goals of the kernel development community.