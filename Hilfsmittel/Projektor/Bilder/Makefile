#
# Makefile -- build images for the differential equations script
#
# (c) 2015 Prof Dr Andreas Mueller, Hochschule Rapperswil
#
all:	komplex

komplex_FILES = komplex-1.pdf 
komplex:	$(komplex_FILES)
$(komplex_FILES): komplex.mp
	TEX=latex mpost komplex.mp
	for f in komplex.[0-9]*; \
	do \
		mptopdf $${f}; \
	done




