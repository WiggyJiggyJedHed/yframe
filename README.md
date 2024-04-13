# yFrame

Quick tool to covert a YouTube link into an HTML `iframe` for note taking or web design. Copy the link onto your clipboard and run the script to convert the copied link into the `iframe` and paste it where you need. Likewise, you can run the script on your command line and enter the link following it. This will echo the `iframe` as standard output if you need to pipe/append it. **Currently only supports Linux.**

## Setup

**This script requires [Xclip](https://github.com/astrand/xclip), [WL-Clipboard](https://github.com/bugaevc/wl-clipboard), or if you're using Android, [Termux](https://github.com/termux/termux-app) depending on whether you're using Xorg, Wayland, or your phone, respectively**. 
 
Go to a directory listed in the output of your `$PATH`. Once there, run the following. ***Please for your own sake, review the code first make sure it is optimized for your system!***

```shell
curl https://raw.githubusercontent.com/WiggyJiggyJedHed/yframe/main/yframe > yframe; sudo chmod +x yframe
```

## Plans for the Script

- [x] Get it working as needed
- [x] Remove `line 11: [: missing ]` error on successful run
- [x] Condense the three versions into one script
- [ ] Create version for Windows (maybe Mac assuming the above doesn't work :shrug: )
