# GhostXPS

Sometimes someone sends my a file in xps. I created this so I could convert it to a pdf:

    cat file.xps | docker run -i programmerq/ghostxps > file.pdf

This container has GhostXPS from http://ghostscript.com/download/gxpsdnld.html
installed (AGPL version)

## License

The code in the Dockerfile to generate this image is distributed under the AGPL
(choosing AGPL just to match the license that GhostXPS is distributed under)
