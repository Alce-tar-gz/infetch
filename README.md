<div align="center">
<h1>Infetch</h1>
<p>A super tiny system information fetch script written in BASH using nerd fonts</p>
<img src="ss.webp"></img>
<a href='#'><img src="https://img.shields.io/badge/Shell_Script-121011?logo=gnu-bash&logoColor=white"></img><a/>
<a href='#'><img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg"></img><a/>
<a href='#'><img src=https://img.shields.io/badge/Maintained%3F-yes-green.svg></img><a/>
<br/>

## Installation
Download sysfetch

```bash
git clone https://github.com/Alce-tar-gz/infetch; cd ${_##*/}
```

Install to $PATH (optional)
```bash

mv sysfetch infetch
cp infetch /usr/bin/local/
```

---

## Usage
Execute script from within downloaded directory
```bash
./sysfetch
```

Or with BASH
```bash
bash sysfetch
```

Otherwise execute infetch from anywhere if it's in $PATH
```bash
infetch
```

Infetch can be executed in an infinite loop, with a delay, live updating the output every N seconds
```bash
infetch <N>
```

Press Ctrl+C or close terminal to kill the script

---

## Contributing
Make a change; Submit that bitch with a relevant message, e.g. `git commit -m 'issus fix #3'`
