Sambar
======

Sambar helps you create a static web site for your community vertical, i.e., it takes care of creating the next meetup event page while showing previous meetup pictures and videos.

# Prerequisites

    node v0.6.19+

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

    ./bin/sambar -c examples/bangaloreJS -t templates/bangaloreJS -o site

# Inspiration
  
* http://www.smore.com
* https://github.com/visionmedia/express/blob/master/bin/express
