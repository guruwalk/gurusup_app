# Gurusup App


## Requirements 

* Node.js 14.17.3 or later

If you're using Linux, depending on your distribution, you'll need to run:

* Debian/Ubuntu: sudo apt install libsecret-1-dev
* Red Hat-based: sudo yum install libsecret-devel
* Arch Linux: sudo pacman -S libsecret

## Install

You install ZCLI as a Node.js package.

To install ZCLI

1. In your computer's terminal, run:
    ```
    npm install @zendesk/zcli -g
    ```
2. Verify ZCLI is installed and ready for use:
    ```
    zcli help
    ```

The command returns your installed ZCLI version and other help information.

To update ZCLI, run the installation command again. ZCLI warns you if your installed version is out of date.


## Run 
```
npx @zendesk/zcli apps:server
```