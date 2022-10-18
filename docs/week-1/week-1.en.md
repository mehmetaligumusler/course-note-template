---
marp: true
theme: default
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Algorithms and Programming I'
footer: '![height:50px](http://erdogan.edu.tr/Images/Uploads/MyContents/L_379-20170718142719217230.jpg) RTEU CE204 Week-1'
title: "Algorithms and Programming I"
author: "Mehmet Ali GUMUSLER"
date:
subtitle: "Algorithms and Programming I"
geometry: "left=2.54cm,right=2.54cm,top=1.91cm,bottom=1.91cm"
titlepage: true
titlepage-color: "FFFFFF"
titlepage-text-color: "000000"
titlepage-rule-color: "CCCCCC"
titlepage-rule-height: 4
logo: "assets/2021-10-19-15-01-36-image.png"
logo-width: 100 
page-background:
page-background-opacity:
links-as-notes: true
lot: true
lof: true
listings-disable-line-numbers: true
listings-no-page-break: false
disable-header-and-footer: false
header-left:
header-center:
header-right:
footer-left: "© Mehmet Ali GUMUSLER"
footer-center: "License: WTFPL"
footer-right:
subparagraph: true
lang: en-US 

math: katex
---

<!-- _backgroundColor: aquq -->

<!-- _color: orange -->

<!-- paginate: false -->

## Algorithms and Programming I

### Week-1

#### What is the Windows Subsystem for Linux?

Download [DOC](week-1.en.md_doc.pdf), [SLIDE](week-1.en.md_slide.pdf), [PPTX](week-1.en.md_slide.pptx)

<iframe width=700, height=500 frameBorder=0 src="../week-1.en.md_slide.html"></iframe>

---

<!-- paginate: true -->

### Outline

- Find out what WSL 1 and WSL 2 are

---

## What is the Windows Subsystem for Linux?

---

### WSL

- What is WSL ?
  The Windows Subsystem for Linux lets developers run a GNU/Linux   environment -- including most command-line tools, utilities, and  applications -- directly on Windows, unmodified, without the overhead of a traditional virtual machine or dualboot setup.

---

![center h:400px](assets/wsl.png)

---

### What can you do?

- Choose your favorite GNU/Linux distributions from the Microsoft Store.
- Run common command-line tools such as grep, sed, awk, or other ELF-64 binaries.
- Run Bash shell scripts and GNU/Linux command-line applications including:
  Tools: vim, emacs, tmux
  Languages: NodeJS, Javascript, Python, Ruby, C/C++, C# & F#, Rust, Go, etc.
  Services: SSHD, MySQL, Apache, lighttpd, MongoDB, PostgreSQL.
- Install additional software using your own GNU/Linux distribution package manager.
- Invoke Windows applications using a Unix-like command-line shell.
- Invoke GNU/Linux applications on Windows.
- Run GNU/Linux graphical applications integrated directly to your Windows desktop
- Use GPU acceleration for machine learning, data science scenarios and more

---

### Install WSL

- https://learn.microsoft.com/en-us/windows/wsl/install

---

### What is WSL 2?

WSL 2 is a new version of the Windows Subsystem for Linux architecture that powers the Windows Subsystem for Linux to run ELF64 Linux binaries on Windows. Its primary goals are to increase file system performance, as well as adding full system call compatibility.

This new architecture changes how these Linux binaries interact with Windows and your computer's hardware, but still provides the same user experience as in WSL 1 (the current widely available version).

Individual Linux distributions can be run with either the WSL 1 or WSL 2 architecture. Each distribution can be upgraded or downgraded at any time and you can run WSL 1 and WSL 2 distributions side by side. WSL 2 uses an entirely new architecture that benefits from running a real Linux kernel.

--- 

## References

- https://learn.microsoft.com/en-us/windows/wsl/about

---

$End-Of-Week-1-Module$
