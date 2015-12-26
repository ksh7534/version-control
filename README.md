# version-control
Conveniently make a tgz file to backup your source code

Usage: ./version_control ${folder}
It'll automatically create ${FOLDER}_BACKUP (if it does not exist), and make ${folder}.${date}${time}.tgz file.
If you want to see the progress, use --verbose option to make it verbose.
For example:
        ./version_control mySource --verbose
