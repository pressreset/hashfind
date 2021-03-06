# hashfind
Hashfind is a script for Mac OSX that builds a plaintext hash database of files within a directory, and allows you to search that database. The bonuses of this being that you can move the databases for individual directories, cards, or drives wherever you want, so you will know the location of a file even if a drive is unplugged, and that Spotlight will index the files so you can search a hash within Spotlight and it will show the relevant database file. Also, as it hashes all the files, you have a database of hashes to check against in order to verify file integrity.

This is a very simple script, and uses built in utilities.

    -d|--database [/path/to/file.db] | Default is hashfind.db, if in current directory.
    -l|--location [/path/to/location] | Default is current directory.
    -b|--build | Build/rebuild the database. Defaults to current directory.
    -h|--hash [hash] | An md5 of a file to locate.
    -f|--file [file] | Supply a filename or path/to/file. It will be hashed, then located.
    
    
You may have to chmod +x the hashfind file after you download it to make the script executable.
If you move the file to /usr/local/bin, or somewhere in your path, you won't have to type the full path to hashfind everytime you want to run it.
    
Feel free to modify or do whatever you would like with this. It's super simple. It was specifically made to hash video, audio, and image files in video editing projects, and give the database the ability to be taken along with whatever media it is sitting on.
