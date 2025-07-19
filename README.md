Python Website Blocker: Stay Focused, Effortlessly 
This Python-powered website blocker is your go-to tool for a more focused and productive online experience. Designed for simplicity and efficiency, it empowers users to easily filter distracting websites and control their digital environment without complex configurations.

How It Works: Simple & Secure 
The script operates by making temporary, non-persistent modifications to your system's hosts file. When activated, it redirects requests for specified unwanted domains, effectively blocking access. This method is lightweight and ensures your system reverts to its original state automatically once the blocking session ends. You maintain full control, with changes only active during the script's execution in filtering mode.

Key Benefits & Features 
Instant Control: Quickly enable or disable website filtering with a simple interactive prompt.

Customizable Blocklist: Manage your list of blocked URLs and domains in a plain text file (urllist.txt). Update it anytime, and your changes are recognized immediately by the script.

Universal Compatibility: Works seamlessly across Windows, macOS, and Linux distributions, automatically adapting to your operating system.

Zero System Impact: All changes to your hosts file are temporary. Your internet access returns to normal as soon as the script is terminated or you choose to disable filtering.

Safe & User-Friendly: Includes a confirmation step before disabling blocking, preventing accidental interruptions to your focused work.

Get Started in 3 Steps! 
Clone the Repository:

Bash

git clone https://github.com/AzharAnwar9/Python-Website-Blocker/
cd Python-Website-Blocker/
Edit Your Blocklist: Open urllist.txt and add the websites you want to block, one domain per line.

Run as Administrator/Root: Execute the script with administrative privileges to allow hosts file modification (changes are temporary):

Bash

python websiteblocker.py
