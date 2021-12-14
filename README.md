# hashfind
Hashfind is a script for Mac OSX that builds a plaintext hash database of files within a directory, and allows you to search that database.

This is a very simple script, and uses the built in utilities.

    -d|--database [/path/to/file.db] | Default is hashfind.db, if in current directory.
    -l|--location [/path/to/location] | Default is current directory.
    -b|--build | Build/rebuild the database. Defaults to current directory.
    -h|--hash [hash] | An md5 of a file to locate.
    -f|--file [file] | Supply a filename or path/to/file. It will be hashed, then located.
    
Feel free to modify or do whatever you would like with this. It's super simple. It was specifically made to hash video, audio, and image files in video editing projects, and give the database the ability to be taken along with whatever media it is sitting on.
