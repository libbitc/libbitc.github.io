if HAVE_DOXYGEN
Doxyfile.stamp:
	$(DOXYGEN) Doxyfile
	echo Timestamp > Doxyfile.stamp

CLEANFILES = Doxyfile.stamp

distclean-local:
	- rm -rf html
	- rm -rf latex

all-local: Doxyfile.stamp
endif
