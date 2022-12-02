# 📋 Clipboard 
Cut, copy, and paste anything anywhere you want, all from the comfort of your terminal! The ultimate clipboard system for the command line.

**Clipboard...**
- **is really tiny**. Clipboard rings in at mere kilobytes for most/all platforms.
- **is really simple**. Clipboard takes no time to learn because there's nothing to learn.
- **is really friendly**. Clipboard is one of the most user-friendly pieces of software out there.
- **is really discoverable**. I never found out about any previously made terminal clipboards because they were 99% invisible.
- **just works everywhere**. Clipboard works on any Windows or POSIX (Linux, macOS, *BSD, etc.) system and has ZERO dependencies.
- **looks pretty**. Colors make everything nicer. 🌈 Say adiós to boring black & white!
- **saves time**. Stop making temporary directories or memorizing file locations. Say hello to productivity!

# How To Use

## Copy
`clipboard copy (file) [files]`

or

`cb copy (file) [files]`

Examples:

```
cb copy foo.txt launchcodes.doc
clipboard copy MyDirectory
cb copy bar.conf AnotherDirectory baz.txt
```
## Cut
`clipboard cut (file) [files]`

or

`cb cut (file) [files]`

Examples:

```
cb cut bar.txt baz.docx
clipboard cut MyDirectory
cb cut bar.conf AnotherDirectory baz.txt
```
## Paste
`clipboard paste`

or

`cb paste`

## Pipe In

`(something) | clipboard [copy]`

or

`(something) | cb [copy]`

## Pipe Out

`clipboard [paste] | (something)`

or

`clipboard [paste] > (some file)`

or

`cb [paste] | (something)`

or

`cb [paste] > (some file)`

# Quick Installation
## Clone
```
git clone https://github.com/slackadays/Clipboard
```
## Compile

You'll need a compiler that supports C++17.
```
cmake Clipboard/src
cmake --build .
```
## Install
```
sudo cmake --install .
```

# Documentation 

[Click here](https://github.com/Slackadays/Clipboard/wiki) to go the Clipboard Wiki.