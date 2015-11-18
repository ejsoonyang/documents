gs
-q
-dBATCH
-dNOPAUSE

-o out.pdf \
-sDEVICE=pdfwrite \

-c "<</PageOffset [500 0]>>setpagedevice" \
-f b.pdf

-sOutputFile=fileout.pdf
-f filein.pdf filein2.pdf

-dFirstPage=3 -dLastPage=3

-dFIXEDMEDIA
-dPDFFitPage

-sPAPERSIZE=a4

(My -o ... is shorter and saves one from adding -dBATCH -dNOPAUSE -- but works only for more recent versions of Ghostscript.)

example:
gs -o 孝經（A4）.pdf -sDEVICE=pdfwrite -g8405x5943 -c "<</PageOffset [-30 -60]>>setpagedevice" -f 孝經.pdf
