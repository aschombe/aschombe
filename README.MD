## Hi, I'm Andrew! 👋

### About Me
```c
struct Student {
    char *name;
    char *education;
    char *courses[1024];
    char *experience[1024];
    char *leadership[1024];
    char *interests[1024];
};

struct Student aschombe = {
    .name = "Andrew Schomber",
    .education = "Computer Science Student at Stevens Institute of Technology",
    .courses = {
        "CS 284 - Data Structures",
        "CS 306 - Intro to IT Security",
        "CS 334 - Theory of Computation",
        "CS 382 - Computer Architecture and Organization",
        "CS 385 - Algorithms",
        "CS 392 - Systems Programming",
        "CS 492 - Operating Systems",
        "CS 496 - Programming Languages",
        "CS 516 - Compiler Design & Implementation",
        "CS 573 - Fundamentals of Cybersecurity",
        "CS 615 - Systems Administration",
        "CS 810 - Automated Techniques for Security, Privacy & Reliability"
    },
    .experience = {
        "Former ROC Engineering Intern at Dega Systems",
        "Course Assistant for Computer Architecture and Systems Programming"
    },
    .leadership = {
        "Vice President of the Stevens Game Development Club"
    },
    .interests = {
        "Information Technology",
        "Cybersecurity",
        "Computer Architecture",
        "Programming Languages",
        "Game Development"
    }
};
```

### Tech Stack
- Operating Systems:
    [![Linux](https://img.shields.io/badge/-Linux-333333?style=flat&logo=linux)](https://www.linux.org/)
    [![Windows](https://custom-icon-badges.demolab.com/badge/Windows-333333?logo=windows&logoColor=white)](https://www.microsoft.com/en-us/windows)
    [![MacOS](https://img.shields.io/badge/-MacOS-333333?style=flat&logo=apple)](https://www.apple.com/macos)

- Languages:
    [![C](https://img.shields.io/badge/-C-333333?style=flat&logo=c)](https://www.gnu.org/software/gnu-c-manual/)
    [![ARM Assembly](https://img.shields.io/badge/-ARM_Assembly-333333?style=flat&logo=ARM)](https://developer.arm.com/documentation/107829/0200/Assembly-language-basics)
    [![C++](https://img.shields.io/badge/-C++-333333?logo=cplusplus&logoColor=blue)](https://isocpp.org/)
    [![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)](https://www.python.org)
    [![Typst](https://img.shields.io/badge/-Typst-333333?style=flat&logo=Typst)](https://typst.app/)
    [![Markdown](https://img.shields.io/badge/-Markdown-333333?style=flat&logo=markdown)](https://www.markdownguide.org/)
    [![GDScript](https://img.shields.io/badge/-GDScript-333333?style=flat&logo=godotengine)](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
    
- Tools:
    [![Neovim](https://img.shields.io/badge/-Neovim-333333?style=flat&logo=neovim)](https://neovim.io/)
    [![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)](https://git-scm.com/)
    [![GitHub](https://img.shields.io/badge/-GitHub-333333?style=flat&logo=github)](https://github.com/)
    [![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/VSCode-333333.svg?logo=vsc)](https://code.visualstudio.com/)
    [![Godot Engine](https://img.shields.io/badge/-Godot_Engine-333333?style=flat&logo=godotengine)](https://godotengine.org/)
    [![Logisim Evolution](https://img.shields.io/badge/Logisim--Evolution-333333?logo=data:image/jpeg;base64,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)](https://github.com/logisim-evolution/logisim-evolution)

## Current Projects
- [microRISC](https://github.com/aschombe/microRISC) - A 32-bit CPU architecture implemented in Logisim-Evolution, with an assembler and manual.
- [C-Script](https://github.com/aschombe/C-Script) - A programming language implemented in C++, with an interpreter and soon a compiler.
- [Jam Mini Launcher](https://github.com/aschombe/jam-mini-launcher) - A custom game library and launcher for the Stevens Game Development Club's upcoming project.

## My Stats
![Most commit languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=aschombe&theme=nord_dark)
![Repos per language](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=aschombe&theme=nord_dark)
![My GitHub Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aschombe&theme=nord_dark)
[![LeetCode Stats](https://leetcard.jacoblin.cool/aschombe?theme=nord)](https://leetcode.com/aschombe)

## Connect with Me

[![Website](https://img.shields.io/badge/Website-aschombe.github.io-333333?logo=Firefox&logoColor=orange)](https://aschombe.github.io)

[![GitHub](https://img.shields.io/badge/GitHub-aschombe-333333?logo=github)](https://github.com/aschombe)

[![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-andrew--schomber-333333?logo=linkedin-white)](https://www.linkedin.com/in/andrew-schomber/)

[![Gmail](https://img.shields.io/badge/Gmail-aschombe%40stevens.edu-333333?logo=gmail)](mailto:aschombe@stevens.edu)