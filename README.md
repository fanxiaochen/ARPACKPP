ARPACK++
========

ARPACK++ is a C++ interface for the famous ARPACK, which is used to eigenvalue problem. It includes only headers of templates, so we could use it without compilation. However, since ARPACK++ is a wrapper of ARPACK and doesn't contain ARPACK itself, we need to compile the   old fortran routines ourselves, which becomes a hard task under Windows.

This package has already been compiled under VS2012 64bit. ARPACK patch has been copied to original arpack96 files. I have made a few modifications of both ARPACK and ARPACK++ as some blogs and forums show and make it available. 

Some useful links as follows:

[http://blog.csdn.net/guillotine007/article/details/8636647](http://blog.csdn.net/guillotine007/article/details/8636647)

[http://www-bcf.usc.edu/~jbarbic/arpack.html](http://www-bcf.usc.edu/~jbarbic/arpack.html)

[http://modb.oce.ulg.ac.be/mediawiki/index.php/How_to_compile_ARPACK](http://modb.oce.ulg.ac.be/mediawiki/index.php/How_to_compile_ARPACK)

[http://reuter.mit.edu/software/arpackpatch/](http://reuter.mit.edu/software/arpackpatch/)
