RUN:

#to get all the project docs
git clone https://hub.jazz.net/git/kat18/rSLADocs
#go to specific directory
cd rSLADocs/rSLA\ language\ paper/
#type
latex mainDoc.tex ; bibtex mainDoc.tex ; latex mainDoc.tex ; latex mainDoc.tex

