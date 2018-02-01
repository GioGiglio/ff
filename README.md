# ff
Searching files directly from the shell is never been easier

# How to use it?
1. Grant the execution permission to the script ( `chmod +x ff` )
2. Move the script to `/usr/local/bin/` ( `sudo mv ff /usr/local/bin/` )
3. Now just type `ff` on shell and start searching files!

# Usage
- `ff [-i] [-c] [-l] [filename]`
- `ff` ( the script will prompt you to insert the filename )
- `ff --help` for extra info

# How it works?
It is heavily based on another script named `locate`, that offers incredibly fast searches of files on the file system.
