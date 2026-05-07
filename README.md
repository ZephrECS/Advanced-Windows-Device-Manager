# Advanced-Windows-Device-Manager
AdvancedDeviceManager | Open Source, free to edit and sell, (pls give credit)

**Advanced Windows Device Manager (Pre-Alpha)**

A more detailed take on the default Windows Device Manager. Instead of just listing devices and saying whether they’re working or not, this aims to show what’s actually going on behind the scenes.

It includes expanded device info, more in-depth driver details, basic error logging, and some tracking for things like disconnects or unusual behavior over time. The goal is to make troubleshooting easier and give a clearer view of your system without needing to jump between multiple tools.

This build is currently in **pre-alpha**, so expect things to be unfinished or inconsistent. Some features might not work properly, and some of the data may not always be accurate yet.

If you end up trying it, any feedback helps—whether something’s broken, confusing, or just feels unnecessary.

---------------------------------------------------------------------------------

**Why it uses ImGui and MinHook**

UI is a simple command prompt, may upgrade to an actual Library, but currently, this is what I'm comfortable with.

MinHook is used for gathering certain bits of data that aren’t exposed cleanly through normal Windows APIs. It lets the program hook into specific system functions so it can capture more detailed information about devices and driver behavior in real time. That’s where some of the extra reporting comes from that you wouldn’t normally see in standard tools.

---------------------------------------------------------------------------------

**Resources Used**

https://github.com/tsudakageyu/minhook

No, this project is not 100% made by a human, I'm an early and learning coder, so I do use assistance using IDEs such as **Antigravity** and **Cursor**. I use these to learn, and no, this project is not 100% AI coded.
