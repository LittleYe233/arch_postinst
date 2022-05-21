# Arch Linux Post-installation Bash Script

## Introduction

An ordinary Bash project for post-installation of Arch Linux.

## Who to use

To be honest, this small project is for my future installation first. But I hope others can use it (or after some simple modifications).

More specifically, those having installed Arch Linux following the official [installation guide](https://wiki.archlinux.org/title/Installation_guide) fully and rebooting the machine successfully can have a try!

## Usage

### Directly use

After rebooting and entering the console, first download the compiled script from [dist/arch_postinst.sh](https://github.com/LittleYe233/arch_postinst/blob/main/dist/arch_postinst.sh). Then use `bash` to execute it.

```bash
wget -O- https://raw.githubusercontent.com/LittleYe233/arch_postinst/main/dist/arch_postinst.sh | bash
```

### Modify first

Download the repository and enter the folder, edit the configurations (recommended ONLY) and then compile.

```bash
git clone https://github.com/LittleYe233/arch_postinst.git
cd arch_postinst
# do some modifications
make
bash dist/arch_postinst.sh
```
