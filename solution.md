# Solution

**_Step 1 :_** Use _strings_ or _exiftool_ to get the hidden password.

**_Step 2 :_** Now use _steghide_ tool to extract the file.(Passphrase is the password obtained from above step)

**_Step 3 :_** Decode the cipher by applying  vignere encode, from base 85, atbash cipher, vignere encode in sequence in cyberchef

**_Step 4 :_** To obtain the key for vignere encode apply _stegsnow_ tool to the extracted file.
