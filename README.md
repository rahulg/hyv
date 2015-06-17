# hyv

hyv is a CLI tool that makes running [xhyve](https://github.com/mist64/xhyve) VMs easier.

# Requirements

- python3
- OS X 10.10
- `xhyve` from here: [xhyve](https://github.com/mist64/xhyve)
  - For convenience, you may wish to [tap this brew](https://github.com/rahulg/homebrew-xhyve)

# Usage

## Init a New VM

- Create a folder for your VM
- Place your `kernel` and `initrd` in this folder
- `hyv --new` to create a skeleton config.hyv
- edit `config.hyv` to match your desired config

## Running a VM

- `cd $dir`
- `hyv` to run the VM
- `poweroff` your VM to return to OS X
