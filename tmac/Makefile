TEX_MACRO_PATH=$$(kpsewhich -var-value=TEXMFHOME)/tex/plane/tmac


all: env install update_tex


install:
	cp -v ./tmac.tex $(TEX_MACRO_PATH)/
	cp -v ./cz_hyp.tex $(TEX_MACRO_PATH)/ 
				 
				     

update_tex:
	texhash ~/texmf

env:
	mkdir $(TEX_MACRO_PATH) -vp
