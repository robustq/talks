# time tracking with ledger

Command-line, plaintext accounting tools are fun

---

# so you track time?

i, too, track time

---

# why do developers track time?

* billing
* billing
* remembering
* ensuring work/life balance

---

# why do developers track time?

* billing
* billing
* remembering
* **ensuring work/life balance**

---

# tools

* `ledger` - ledger-cli.org
* `t` - https://github.com/colindean/hejmo/blob/master/scripts/t

_(I promise it'll get better if others clamor.)_

_(I'm probably a user away from making a Homebrew tap.)_

---

# Basic `t` usage

```
$ t in Taskname
$ t sw OtherTask
$ t out
```

---

# Forgot something?

```
$ t log 09:15 11:45 Coding
$ t edit
```

It's just a text file.

---

# Basic daily reporting

```
$ t hours
               8.47h  N
               1.03h    Development
               1.04h    Email
               5.90h    Meeting
               24.1m      IT
               4.50h      Recruiting:Interview
               30.0m    Training:Podcasts
--------------------
               8.47h
```

---

# Listing projects

![](projects.png)

---

# Time sheet

![](sheet.png)

Easily view daily totals for transposition to tracking system

---

# But wait, there's more!

---

# BitBar

![](bitbar.png)

https://github.com/colindean/hejmo/blob/master/dotfiles/bitbar/work/hours.6m.sh

_(Unfortunately requires some customization to get `t` path right)_

---

# How can you help?

* Use `t` and submit improvements and reports
* Improve ledger syntax highlighting to include time mode

---

# Text editor support

vim
```
Plugin 'ledger/vim-ledger'
```
atom

```
$ apm install language-ledger
```
and many more

---

# Go forth and track time!