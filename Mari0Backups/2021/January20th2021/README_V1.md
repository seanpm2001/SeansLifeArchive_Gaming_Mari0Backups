
***

# January 20th 2021 Mari0 backup data

I finally got around to tinkering with my snap packages long enough to learn how to back up my Mari0 save data today. I quit playing for several months, because I couldn't backup my data. My backup data is now here!

To get started, you have to have the mari0 snap package installed. If the service still works, try this:

`sudo apt install mari0`

I got it from the Ubuntu store, and this command is a bit dated. If you already have the game installed, make sure you create a backup before overwriting any files.

For safety, make sure the game isn't running first.

Navigate to: `/home/snap/mari0/current/.local/share/love/mari0/mappacks/smb/`

There should be 53 text files, of which 52 can be replaced. Make sure to back these files up first if you have any levels here.

Grab all files that start with a number, and avoid `settings.txt` delete them, and place the new files that start with a number `1-1` etc. here. 

Now load up the game, and enjoy!

I will work on making actual mappacks instead of overwriting the default when I figure out how.

Backup size is below 700 kilobytes when compressed, when uncompressed, it is a little over 2000 kilobytes (2.0 MiB)

***
