#############################################################################
# Makefile for building: ansifilter-gui
# Generated by qmake (2.01a) (Qt 4.8.6) on: Do. Jan 22 18:44:27 2015
# Project:  ansifilter-gui.pro
# Template: app
# Command: /usr/bin/qmake-qt4 -o Makefile ansifilter-gui.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DO2 -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -march=x86-64 -mtune=generic -O2 -pipe -fstack-protector-strong --param=ssp-buffer-size=4 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -march=x86-64 -mtune=generic -O2 -pipe -fstack-protector-strong --param=ssp-buffer-size=4 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtGui -I/usr/include/qt4 -I. -I.. -I. -I.
LINK          = g++
LFLAGS        = -Wl,-O1,--sort-common,--as-needed,-z,relro -Wl,-O1
LIBS          = $(SUBLIBS)  -L/usr/lib -lQtGui -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake-qt4
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = main.cpp \
		mydialog.cpp \
		../elementstyle.cpp \
		../plaintextgenerator.cpp \
		../codegenerator.cpp \
		../platform_fs.cpp \
		../rtfgenerator.cpp \
		../htmlgenerator.cpp \
		../pangogenerator.cpp \
		../texgenerator.cpp \
		../latexgenerator.cpp \
		../bbcodegenerator.cpp \
		../stringtools.cpp \
		../stylecolour.cpp \
		../preformatter.cpp moc_mydialog.cpp
OBJECTS       = main.o \
		mydialog.o \
		elementstyle.o \
		plaintextgenerator.o \
		codegenerator.o \
		platform_fs.o \
		rtfgenerator.o \
		htmlgenerator.o \
		pangogenerator.o \
		texgenerator.o \
		latexgenerator.o \
		bbcodegenerator.o \
		stringtools.o \
		stylecolour.o \
		preformatter.o \
		moc_mydialog.o
DIST          = /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_phonon.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/shared.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		ansifilter-gui.pro
QMAKE_TARGET  = ansifilter-gui
DESTDIR       = 
TARGET        = ansifilter-gui

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): ui_ansifilter.h $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: ansifilter-gui.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_phonon.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/shared.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		/usr/lib/libQtGui.prl \
		/usr/lib/libQtCore.prl
	$(QMAKE) -o Makefile ansifilter-gui.pro
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/common/gcc-base.conf:
/usr/share/qt4/mkspecs/common/gcc-base-unix.conf:
/usr/share/qt4/mkspecs/common/g++-base.conf:
/usr/share/qt4/mkspecs/common/g++-unix.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/modules/qt_phonon.pri:
/usr/share/qt4/mkspecs/modules/qt_webkit.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/release.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/shared.prf:
/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/share/qt4/mkspecs/features/include_source_dir.prf:
/usr/lib/libQtGui.prl:
/usr/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -o Makefile ansifilter-gui.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/ansifilter-gui1.0.0 || $(MKDIR) .tmp/ansifilter-gui1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/ansifilter-gui1.0.0/ && $(COPY_FILE) --parents mydialog.h .tmp/ansifilter-gui1.0.0/ && $(COPY_FILE) --parents main.cpp mydialog.cpp ../elementstyle.cpp ../plaintextgenerator.cpp ../codegenerator.cpp ../platform_fs.cpp ../rtfgenerator.cpp ../htmlgenerator.cpp ../pangogenerator.cpp ../texgenerator.cpp ../latexgenerator.cpp ../bbcodegenerator.cpp ../stringtools.cpp ../stylecolour.cpp ../preformatter.cpp .tmp/ansifilter-gui1.0.0/ && $(COPY_FILE) --parents ansifilter.ui .tmp/ansifilter-gui1.0.0/ && (cd `dirname .tmp/ansifilter-gui1.0.0` && $(TAR) ansifilter-gui1.0.0.tar ansifilter-gui1.0.0 && $(COMPRESS) ansifilter-gui1.0.0.tar) && $(MOVE) `dirname .tmp/ansifilter-gui1.0.0`/ansifilter-gui1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/ansifilter-gui1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_mydialog.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_mydialog.cpp
moc_mydialog.cpp: ui_ansifilter.h \
		mydialog.h
	/usr/lib/qt4/bin/moc $(DEFINES) $(INCPATH) mydialog.h -o moc_mydialog.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: ui_ansifilter.h
compiler_uic_clean:
	-$(DEL_FILE) ui_ansifilter.h
ui_ansifilter.h: ansifilter.ui
	/usr/lib/qt4/bin/uic ansifilter.ui -o ui_ansifilter.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_uic_clean 

####### Compile

main.o: main.cpp mydialog.h \
		ui_ansifilter.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

mydialog.o: mydialog.cpp mydialog.h \
		ui_ansifilter.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o mydialog.o mydialog.cpp

elementstyle.o: ../elementstyle.cpp ../elementstyle.h \
		../stylecolour.h \
		../enums.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o elementstyle.o ../elementstyle.cpp

plaintextgenerator.o: ../plaintextgenerator.cpp ../plaintextgenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../version.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o plaintextgenerator.o ../plaintextgenerator.cpp

codegenerator.o: ../codegenerator.cpp ../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../version.h \
		../pangogenerator.h \
		../htmlgenerator.h \
		../rtfgenerator.h \
		../plaintextgenerator.h \
		../texgenerator.h \
		../latexgenerator.h \
		../bbcodegenerator.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o codegenerator.o ../codegenerator.cpp

platform_fs.o: ../platform_fs.cpp ../platform_fs.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o platform_fs.o ../platform_fs.cpp

rtfgenerator.o: ../rtfgenerator.cpp ../charcodes.h \
		../version.h \
		../rtfgenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o rtfgenerator.o ../rtfgenerator.cpp

htmlgenerator.o: ../htmlgenerator.cpp ../htmlgenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../version.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o htmlgenerator.o ../htmlgenerator.cpp

pangogenerator.o: ../pangogenerator.cpp ../pangogenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../version.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o pangogenerator.o ../pangogenerator.cpp

texgenerator.o: ../texgenerator.cpp ../texgenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../charcodes.h \
		../version.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o texgenerator.o ../texgenerator.cpp

latexgenerator.o: ../latexgenerator.cpp ../latexgenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../version.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o latexgenerator.o ../latexgenerator.cpp

bbcodegenerator.o: ../bbcodegenerator.cpp ../bbcodegenerator.h \
		../codegenerator.h \
		../elementstyle.h \
		../stylecolour.h \
		../enums.h \
		../preformatter.h \
		../stringtools.h \
		../version.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bbcodegenerator.o ../bbcodegenerator.cpp

stringtools.o: ../stringtools.cpp ../stringtools.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o stringtools.o ../stringtools.cpp

stylecolour.o: ../stylecolour.cpp ../stylecolour.h \
		../enums.h \
		../stringtools.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o stylecolour.o ../stylecolour.cpp

preformatter.o: ../preformatter.cpp ../preformatter.h \
		../stringtools.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o preformatter.o ../preformatter.cpp

moc_mydialog.o: moc_mydialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_mydialog.o moc_mydialog.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

