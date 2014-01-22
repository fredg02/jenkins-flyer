jenkins-flyer
=============

Concept for a Jenkins flyer.

Final design
--------------

Intermediate format (incl. 3mm bleed): 196x71mm

Final format: 190x65mm

Resolution: 300 DPI


###2013

Ready to print CMYK PDF: flyer\_2013/JenkinsFlyer\_2013\_Final\_CMYK.pdf


###2014

Ready to print CMYK PDF: flyer\_2014/JenkinsFlyer\_2014\_Final\_CMYK.pdf

---

Jenkins Flyer Mini-Howto
------------------------

1. Open last year's flyer front and back vector files in [Inkscape](http://www.inkscape.org)
  - e.g. for 2013: 
    - flyer\_2013/JenkinsFlyer\_2013\_back\_final\_allSVG.svg
    - flyer\_2013/JenkinsFlyer\_2013\_front\_final\_allSVG.svg
    - flyer\_2013/jenkinsScreenshot.png (embedded graphic)

2. Edit texts and graphics

3. Once finished, convert SVGs to "pathsOnly" (otherwise text gets screwed up)
  - Select all texts and use "Path -> Object to Path"
  - Ungroup texts if necessary
  
4. Export SVGs to TIF
  - Open SVGs in [GIMP](http://www.gimp.org/)
    - Width: 	71.17
    - Height:	196.00
    - DPI: 300.00
  - Add white background layer
  - Export as TIF (enable LZW compression!)

5. Convert TIFs to CMYK PDF
  - One file, two pages (back and front)
  - Use Adobe Illustrator for example (is there any reliable open-source alternative?)

6. Send PDF file to print shop (1.4 MB)
  - 65 x 190mm
  - 250 gram matt paper
  - double-sided
  - 4/4 color