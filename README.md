# DoS-Floppy-CTF
Something I wrote for the BSides Leeds 2020 CTF. Some MS-Dos magic is needed to read the flag (and a little container knowledge to get this version running)

Note during the challenge this was running on the SkyBetting and Gamining K8s infrastructure, but this is an early version of the challenge I had working at home.

The idea is to read the flag (a hex GUID in double braces, as is commonly used in CTFs) from inside the running container (it's stupidly trivial to open the DosBSL.img and read it, but obviously you didn't have access to the .img in the real challenge, so don't do that).

So build the dockerfile
Run it mapping port 5900 

vnc to 5900, find and read the file with the flag in it. Easy as that. .... Kinda.

Any hint requests, feedback etc to @glennpegden on twitter

Enjoy

