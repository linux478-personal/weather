# weather

## Description

display in the terminal the current day's weather

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

### Dependences

* wget - the program gets the information for the web
* head - help filter some of the information
* tail - help filter some of the information

### Install

* copy weather file to a folder in the PATH variable
* set the execute permission(s) on the weather file 

## Usage

```
$ weather
```

## Default Output

```
                                                       ┌─────────────┐                                                       
┌──────────────────────────────┬───────────────────────┤  Fri 07 Apr ├───────────────────────┬──────────────────────────────┐
│            Morning           │             Noon      └──────┬──────┘     Evening           │             Night            │
├──────────────────────────────┼──────────────────────────────┼──────────────────────────────┼──────────────────────────────┤
│               Overcast       │    \  /       Partly cloudy  │     \   /     Sunny          │     \   /     Clear          │
│      .--.     +37(26) °F     │  _ /"".-.     +39(30) °F     │      .-.      +42(35) °F     │      .-.      32(24) °F      │
│   .-(    ).   ↘ 16-18 mph    │    \_(   ).   → 19-21 mph    │   ― (   ) ―   ↘ 12-14 mph    │   ― (   ) ―   → 8-11 mph     │
│  (___.__)__)  6 mi           │    /(___(__)  6 mi           │      `-’      6 mi           │      `-’      6 mi           │
│               0.0 in | 0%    │               0.0 in | 0%    │     /   \     0.0 in | 0%    │     /   \     0.0 in | 0%    │
└──────────────────────────────┴──────────────────────────────┴──────────────────────────────┴──────────────────────────────┘
```

## Credits

* [wttr.in](https://github.com/chubin/wttr.in)

## License

The MIT License (MIT)

Copyright (c) 2023 Michael Phillips

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
