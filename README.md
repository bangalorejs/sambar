sambar
======

Sambar helps you create a static site for your next event.

# Install

    git clone git://github.com/minsh/sambar.git;

# Usage

    Usage: sambar [options]

    Options:

        -h, --help                 output usage information
        -v, --version              output the version number
        -c, --configFile [file]    Config file
        -t, --templatePath [path]  Template path
        -o, --outputDir [path]     Output directory
        -f, --force                Force on non-empty directory

Here is how to create the bangalorejs site:

    ./bin/sambar -c example/bangalorejs.json -t templates/bangaloreJS -o site

# Inspiration
  
* http://www.smore.com
* https://github.com/visionmedia/express/blob/master/bin/express
