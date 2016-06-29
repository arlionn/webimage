# webimage : converting web files to graphical image in Stata

__`webimage`__ prints images from web files in __pdf__, __png__, __jpeg__, 
__gif__, and __bmp__ format

        
Author
------
  **E. F. Haghish**  
  Center for Medical Biometry and Medical Informatics    
  University of Freiburg, Germany        
  _haghish@imbi.uni-freiburg.de_       
  _http://www.haghish.com/dot_      
  _[@Haghish](https://twitter.com/Haghish)_      
  
Installation
------------

The __webimage__ releases are also hosted on SSC server. So you can download the latest release as follows:

    ssc install webimage
    
You can also directly download __webimage__ from GitHub which includes the latest beta version (unreleased). The `force` 
option ensures that you _reinstall_ the package, even if the release date is not yet changed, and thus, must be specified. 
  
    net install diagram, force  from("https://raw.githubusercontent.com/haghish/webimage/master/")
    
For exporting graphical files, the package requires [phantomJS](http://phantomjs.org/download.html), 
which is an open-source freeware available for Windows, Mac, and Linux. The 
path to the executable [phantomJS](http://phantomjs.org/download.html) file is required in order to export the graphical files. However, if the executable file is installed in the default local 
directory (e.g. `/usr/local/bin/` in Mac), the `phantomjs(str)` can be ignored. 


