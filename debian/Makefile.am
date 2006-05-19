#ident "$Id: Makefile.am -- pcoval"
lib_LTLIBRARIES = libnewmat.la

libnewmat_la_LDFLAGS = -version-info 10:0:0

libnewmat_la_SOURCES = \
  newmat1.cpp newmat2.cpp newmat3.cpp newmat4.cpp newmat5.cpp newmat6.cpp \
  newmat7.cpp newmat8.cpp newmatex.cpp bandmat.cpp submat.cpp myexcept.cpp \
  cholesky.cpp evalue.cpp fft.cpp hholder.cpp jacobi.cpp newfft.cpp \
  sort.cpp svd.cpp newmatrm.cpp newmat9.cpp
 #

pkgincludedir = $(includedir)/newmat

pkginclude_HEADERS = \
  config.h include.h \
  boolean.h controlw.h myexcept.h newmat.h newmatnl.h newmatrm.h solution.h \
  newmatap.h  newmatio.h  newmatrc.h  precisio.h
 #

bin_PROGRAMS = example test_exc tmt

example_SOURCES = example.cpp
example_LDFLAGS = -lnewmat

test_exc_SOURCES = test_exc.cpp
test_exc_LDFLAGS = -lnewmat


tmt_SOURCES = tmt.cpp \
  tmt1.cpp tmt2.cpp tmt3.cpp tmt4.cpp tmt5.cpp tmt6.cpp tmt7.cpp tmt8.cpp \
  tmt9.cpp tmta.cpp tmtb.cpp tmtc.cpp tmtd.cpp tmte.cpp tmtf.cpp tmtg.cpp \
  tmth.cpp tmti.cpp tmtj.cpp tmtk.cpp tmtl.cpp tmtm.cpp
 #
tmt_LDFLAGS = -lnewmat

#eof "$Id: Makefile.am -- pcoval"
