# TRS-80 Model 100 Alarm Clock

This is the original source code for an alarm clock program I 
wrote for my [**Tandy TRS-80 Model 100**](https://en.wikipedia.org/wiki/TRS-80_Model_100) in the 1980s.

The program was written in Microsoft BASIC and was designed to 
provide an alarm clock with support for multiple alarms, time-zone 
adjustments, and date and time manipulation.

## History

The program was published on **CompuServe** under the name:

```text
ALARM 02.00.00
```

The original source identifies me as the author:

```text
ALARM 02.00.00 by David W. Parvin
CompuServe Number 76576,3337
```

The program was stored and distributed using cassette tape, which 
was one of the common ways to save programs on the TRS-80 Model 100.

The Model 100 had a small built-in LCD display and limited memory, so 
the program was written with the constraints of that hardware in mind.

## Features

The program includes:

* Multiple configurable alarms
* Audible alarms using the Model 100's `BEEP` command
* Date and time display
* Day, month, and year adjustment
* Time-zone support
* 12-hour and 24-hour time display
* Alarm persistence using a data file
* Keyboard-driven menus
* Cassette save/load support
* Date calculations, including leap-year handling

The program also makes extensive use of the capabilities available in 
Microsoft BASIC on the Model 100, including string manipulation, arrays, 
subroutines, keyboard handlers, and direct memory access using `PEEK`, 
`POKE`, and `VARPTR`.

## Why I Am Keeping This

This program is preserved primarily as a piece of my programming history.

It represents an early stage of my programming experience, long before 
modern development environments, source control systems, automated 
testing, and cloud repositories existed.

The program is especially interesting to me because many of the programming 
concepts I work with today—-date and time calculations, persistence, user 
interfaces, input handling, error handling, and managing limited 
resources—-were already things I was working with in BASIC decades ago.

## Original Environment

**Computer:** Tandy TRS-80 Model 100
**Language:** Microsoft BASIC
**Storage:** Cassette tape
**Distribution:** CompuServe
**Program Version:** 02.00.00

The original program has been preserved as closely as possible. The source 
code is intentionally not modernized or reformatted so that it remains 
representative of the code as it was originally written.

## A Note About the Source

Some of the techniques used in this program may look unusual by modern 
programming standards. The Model 100 had very limited memory and processing 
resources, and BASIC provided a very different programming environment from 
modern languages such as C#, VB.NET, C++, and F#.

The direct memory manipulation and compact code are examples of programming 
techniques that were useful in that environment.

This code is preserved for historical and educational purposes rather than 
as an example of modern programming practices.
