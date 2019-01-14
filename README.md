
A fancy and highly customizable bash prompt and suite of generally useful 
scripts to go along with it. Basic prompts include:

  * The usual user, host (or tty), working directory, date, time,
    command sequence number. 
    
  * Clock and other information can be written to the top of the
    screen and/or the title of the terminal emulator program
    (where compatible with xterm escape sequences.)
    
  * Notification of errors (non-zero return value), command run time,
    and other notes/statistics about commands being run.
  
  * System load (color coded as a warning when high), jobs running 
    in background, and more. Can be set to only show when higher
    than a given value, etc.
  
  * If multiple shells/windows are being run by the same user
    simultaneously, color schemes can automatically change so as
    to have a visual cue as to which one is being accessed. Visual
    cues for running as root, etc. can be included as well.
  
  * Customize colors for all elements of the command line, for text
    being entered, etc. Colors can be saved as themes, which can be
    edited interactively.
  
  * Line numbers and special colors highlighting here-documents (<<EOF),
    shell command continuation, etc.
    
  * Command prompts can be one line of text, or two or more if a great deal
    of information is being displayed.
 
  * Scripts and other programs (including ones written in other languages)
    can easily be run and their output included in the prompt with or
    without additional processing and highlighting.

  * Terminal escape sequences, etc. can be customized (changed from
    default of standard ANSI+xterm) if necessary. They are saved in one
    place to avoid having to run 'tput' frequently.

Going beyond the usual colors and few shell commands, PSx is a powerful tool
for anyone who uses the command line interface. Some features include:
  
  * Visual themes, fully customizeable, including 'true color'/24-bit RGB
    options with fall-back to traditional 8/16 color ANSI. Easily created
    and edited with an interactive tool. 'dircolors' for 'ls', etc. are
    included in themues as well so as to seamlessly create attractive 
    color schemes.

  * Plugins: PSx is set up so as to easily include bash scripts written as
    plugins (simple scripts already giving simple output that the user
    would like to include in the prompt require only minimal modification)
    for everything from displaying a clock and machine status as a 'taskbar'
    type line of text at the top of the screen, to checking e-mail and
    even social media accounts.

  * Comes with a suite of utilities for formatting text in an attractive
    manner on the terminal, creating text-based terminal menus, etc.
    
  * Can run as almost 100% native bash code, without having to shell out to 
    other programs (textutils, coreutils, etc.), so can run on any platform 
    which can run bash, even if standard UNIX setup is not there. Only a
    very few commands are required (rm, cp, mv and a few others) which
    can easily be redefined for the system in question (e.g. del, copy,
    move on Windows.) The scripts which replicate these utilities (head, 
    tail, cat, which, etc.) can also be run by the user and/or other
    scripts. Some of them will save time and resources (some of them will
    take longer than shelling out to the system binary, however, due to
    naïve impementations.)
      
  * Prompts can be created in a simple markup language instead of the
    traditional format for the PS1/etc. variables, which rapidly becomes
    complex when scripts/code/terminal escape sequences (e.g. colors and
    formaatting) are involved.
  
  PSx is currently in pre-alpha development stage, but early alpha versions
  should be released in early 2019.
  
#
#  PSx: a highly customizeable and full-featured set of utilities for
#       creating attractive and useful prompts for the bash(1) shell.
#
#       Version 0.01(alpha)
#
# GitHub: https://github.com/38spl/PSx 
# Project web page: https://38spl.net/PSx
#
# Copyright (C) 2019 Noah T. Paul <ntp@38spl.net>
#
# Permission is hereby granted, free of charge, to any person obtaining a copy
# of this software and associated documentation files (the "Software"), to deal
# in the Software without restriction, including without limitation the rights
# to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
# copies of the Software, and to permit persons to whom the Software is
# furnished to do so, subject to the following conditions:
#
#     The above copyright notice, this permission notice, and the following
#     disclamer shall be included in all copies or substantial portions of
#     the Software.
#
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
# IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
# THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
# OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
# ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
# OTHER DEALINGS IN THE SOFTWARE.
