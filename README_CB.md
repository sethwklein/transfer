# `cb`

### Rationale

The clipboard manipulation commands on Windows are impractical to type,
and the commands are different on different operating systems and sometimes even
different machines (Linux).

### About the Name

* `clip` is `clip.exe` on Windows
* `c`    might be a little short
* `cb`   seems to work. Short is not bad

### About the Usage

How to specify input versus output mode?

I think I can't autodetect because both in and out file descriptors will be
open.

Different names? `bc` is taken.

I think out is more common?

* `cb | foo` is out and default
* `foo | cb -` is input mode

The concept is that if you give it a file, it takes input from that,
otherwise it provides output.

### Future Changes

* Support for files, not just `stdin` (`-`)
