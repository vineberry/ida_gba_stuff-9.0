# IDA 9.0 GBA Stuff
Useful stuff when reversing gba games with [IDA](https://hex-rays.com/)

## Installation
Copy to the installation directory of your IDA.

## Note
- The directory 'fe' is for fire emblem exclusively, others work for all gba games.
- [GBA loader](https://github.com/laqieer/ida_gba_stuff/blob/master/loaders/GBA_Loader.py) is updated to IDA 7.7, others are for IDA 7.0.
- Now (hopefully) updated for IDA 9.0.

I went with a separate fork rather than a pull request so that the different versions can be maintained. Tested with a couple GBA games, opened without error. I haven't touched the Fire Emblem folder so be warned, this is just an update for GBA Loader to function. It seems to work and that's good enough for me.

Thank you to laqieer and mrsteyk for the plugin!
## Troubleshooting
Just because it works for me doesn't mean it'll work for everyone. If you're unable to load the plugin on your IDA, please open an issue with the following:
- IDA version (the exact one, like 9.0.20241216, RC, and whether free/home/pro)
- Console output describing the error
And, if needed or wanted, feel free to open a pull request! 
