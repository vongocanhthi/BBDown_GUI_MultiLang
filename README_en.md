**English** | [中文](README.md) | [Tiếng Việt](README_vi.md)

# BBDown_GUI

Graphical version of BBDown - Bilibili video download, audio download, subtitle download.

## Screenshots

### Simple Mode

<img src="https://user-images.githubusercontent.com/29673994/169644975-066c4ac5-7fb1-4361-8c62-bb1e5aba4381.png" height="50%" width="50%" >

### Advanced Mode

<img src="https://user-images.githubusercontent.com/29673994/200099369-51250aa4-bd7f-4547-864c-f552143adcc1.png">

## Features

- [x] Remember download parameters
- [x] Episode download options (current episode, all episodes, latest episode)
- [x] Prioritize common options, while retaining all functions
- [x] Download progress control

## Usage

Place the BBDown executable in the same folder as this UI program and run it directly. This way, if the main BBDown program is updated in the future, it can be directly replaced and used.

## Download

### Download from [Releases](https://github.com/1299172402/BBDown_GUI/releases) [![img](https://img.shields.io/github/v/release/1299172402/BBDown_GUI?label=Version)](https://github.com/1299172402/BBDown_GUI/releases) 

Pre-packaged binaries, including:
- BBDown - GUI
- BBDown
- FFmpeg
- Aria2c

### Install from [PyPI](https://pypi.org/project/BBDown-GUI/) [![](https://img.shields.io/pypi/v/BBDown_GUI)](https://pypi.org/project/BBDown-GUI/) 

Installation:

```
pip install BBDown-GUI
```

Run (case-insensitive, underscore can be omitted):
```
BBDown_GUI
```

### Run from source code
```
pip install -r requirements.txt
python -m BBDown_GUI
```

### Download from [Continuous Integration](https://github.com/1299172402/BBDown_GUI/actions/workflows/build.yml) (beta version) [![Pack Python application](https://github.com/1299172402/BBDown_GUI/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/1299172402/BBDown_GUI/actions/workflows/build.yml)
Go to Actions, select Pack Python application, enter the workflow you need to download:
![image](https://github.com/1299172402/BBDown_GUI/assets/29673994/d7944b79-ae96-4c6a-9892-f8e7d3238a61)
Go down to Artifacts to download BBDown_GUI:
![image](https://github.com/1299172402/BBDown_GUI/assets/29673994/45c92ba5-80cc-47db-b5cc-8abe23de2078)

## Acknowledgements & License

 - https://github.com/nilaoda/BBDown (MIT License)
