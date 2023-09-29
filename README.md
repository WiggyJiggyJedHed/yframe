# yFrame

Quick tool to covert a YouTube link into an HTML `iframe` for note taking or web design. Copy the link onto your clipboard and run the script to convert the copied link into the `iframe` and paste it where you need. Likewise, you can run the script on your command line and enter the link following it. This will echo the `iframe` as standard output if you need to pipe/append it. **Currently only supports Linux.**

## Setup

 **This script requires [Xclip](https://github.com/astrand/xclip) or [WL-Clipboard](https://github.com/bugaevc/wl-clipboard) depending on whether you're using Xorg or Wayland, respectively**. 
 
 Go to a directory listed in the output of your `$PATH`. Once there, run one of the commands listed below depending on what you're using it with.

### Xclip

```shell
curl https://raw.githubusercontent.com/WiggyJiggyJedHed/yframe/main/yframe_xclip > yframe; sudo chmod +x yframe
```

### WL-Clipboard

```shell
curl https://raw.githubusercontent.com/WiggyJiggyJedHed/yframe/main/yframe_wl-clipboard > yframe; sudo chmod +x yframe
```

### Termux

```shell
curl https://raw.githubusercontent.com/WiggyJiggyJedHed/yframe/main/yframe_termux > yframe; chmod +x yframe
```

## Plans for the Script

- [x] Get it working as needed
- [x] Remove `line 11: [: missing ]` error on successful run
- [ ] Condense the three versions into one script
- [ ] Create version for Windows (maybe Mac assuming three above don't work :shrug: )
