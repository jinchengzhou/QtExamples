#############################################################################
# Makefile for building: tetrix
# Generated by qmake (1.07a) (Qt 3.3.1) on: Mon Jan 03 00:10:54 2005
# Project:  tetrix.pro
# Template: app
# Command: $(QMAKE) -spec win32-msvc -o Makefile tetrix.pro
#############################################################################

####### Compiler, tools and options

CC		=	cl
CXX		=	cl
LEX		= flex
YACC		= byacc
CFLAGS	=	-nologo -Zm200 -W3 -MD -O1  -DUNICODE -DQT_DLL -DQT_THREAD_SUPPORT -DQT_ACCESSIBILITY_SUPPORT -DQT_NO_DEBUG
CXXFLAGS	=	-nologo -Zm200 -W3 -MD -O1  -DUNICODE -DQT_DLL -DQT_THREAD_SUPPORT -DQT_ACCESSIBILITY_SUPPORT -DQT_NO_DEBUG
LEXFLAGS	=
YACCFLAGS	=-d
INCPATH	=	 -I"$(QTDIR)\include" -I"C:\Qt\3.3.1\examples\tetrix" -I"tmp\moc\release_mt_shared" -I"C:\Qt\3.3.1\mkspecs\win32-msvc"
LINK	=	link
LFLAGS	=	/NOLOGO delayimp.lib /DELAYLOAD:comdlg32.dll /DELAYLOAD:oleaut32.dll /DELAYLOAD:winmm.dll /DELAYLOAD:wsock32.dll /DELAYLOAD:winspool.dll /DELAYLOAD:opengl32.dll /SUBSYSTEM:windows /LIBPATH:"$(QTDIR)\lib"
LIBS	=	 "qt-mt331.lib" "qtmain.lib" "opengl32.lib" "glu32.lib" "delayimp.lib" "kernel32.lib" "user32.lib" "gdi32.lib" "comdlg32.lib" "advapi32.lib" "shell32.lib" "ole32.lib" "oleaut32.lib" "uuid.lib" "imm32.lib" "winmm.lib" "wsock32.lib" "winspool.lib"
MOC		=	$(QTDIR)\bin\moc.exe
UIC		=	$(QTDIR)\bin\uic.exe
QMAKE		=	qmake
IDC		=	$(QTDIR)\bin\idc.exe
IDL		=	midl
ZIP		=	zip -r -9
COPY_FILE	=       copy
COPY_DIR	=       copy
DEL_FILE	=       del
DEL_DIR	=       rmdir
MOVE		=       move
CHK_DIR_EXISTS =	if not exist
MKDIR		=	mkdir

####### Files

HEADERS =	gtetrix.h \
		qdragapp.h \
		qtetrix.h \
		qtetrixb.h \
		tpiece.h
SOURCES =	gtetrix.cpp \
		qdragapp.cpp \
		qtetrix.cpp \
		qtetrixb.cpp \
		tetrix.cpp \
		tpiece.cpp
OBJECTS =	tmp\obj\release_mt_shared\gtetrix.obj \
		tmp\obj\release_mt_shared\qdragapp.obj \
		tmp\obj\release_mt_shared\qtetrix.obj \
		tmp\obj\release_mt_shared\qtetrixb.obj \
		tmp\obj\release_mt_shared\tetrix.obj \
		tmp\obj\release_mt_shared\tpiece.obj
FORMS =	
UICDECLS =	
UICIMPLS =	
SRCMOC	=	tmp\moc\release_mt_shared\moc_qdragapp.cpp \
		tmp\moc\release_mt_shared\moc_qtetrix.cpp \
		tmp\moc\release_mt_shared\moc_qtetrixb.cpp \
		tmp\moc\release_mt_shared\qdragapp.moc
OBJMOC	=	tmp\obj\release_mt_shared\moc_qdragapp.obj \
		tmp\obj\release_mt_shared\moc_qtetrix.obj \
		tmp\obj\release_mt_shared\moc_qtetrixb.obj
DIST	=	
TARGET	=	tetrix.exe

####### Implicit rules

.SUFFIXES: .c .cpp .cc .cxx .C

{.}.cpp{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{.}.cc{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{.}.cxx{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{.}.C{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{.}.c{tmp\obj\release_mt_shared\}.obj::
	$(CC) -c $(CFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{tmp\moc\release_mt_shared}.cpp{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{tmp\moc\release_mt_shared}.cc{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{tmp\moc\release_mt_shared}.cxx{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{tmp\moc\release_mt_shared}.C{tmp\obj\release_mt_shared\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

{tmp\moc\release_mt_shared}.c{tmp\obj\release_mt_shared\}.obj::
	$(CC) -c $(CFLAGS) $(INCPATH) -Fotmp\obj\release_mt_shared\ @<<
	$<
<<

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(UICDECLS) $(OBJECTS) $(OBJMOC) 
	$(LINK) $(LFLAGS) /OUT:$(TARGET) @<< 
	  $(OBJECTS) $(OBJMOC) $(LIBS)
<<


mocables: $(SRCMOC)
uicables: $(UICIMPLS) $(UICDECLS)

Makefile: tetrix.pro ..\..\.qmake.cache C:\Qt\3.3.1\mkspecs\win32-msvc\qmake.conf ..\..\lib\qtmain.prl
	$(QMAKE) -spec win32-msvc -o Makefile tetrix.pro
qmake: 
	@$(QMAKE) -spec win32-msvc -o Makefile tetrix.pro

dist:
	$(ZIP) tetrix.zip $(SOURCES) $(HEADERS) $(DIST) $(FORMS) C:/Qt/3.3.1/examples/tetrix/tetrix.pro ..\..\lib\qtmain.prl  

uiclean:
mocclean:
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_qdragapp.cpp
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_qtetrix.cpp
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_qtetrixb.cpp
	-$(DEL_FILE) tmp\moc\release_mt_shared\qdragapp.moc
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_qdragapp.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_qtetrix.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_qtetrixb.obj
clean: uiclean mocclean
	-$(DEL_FILE) tmp\obj\release_mt_shared\gtetrix.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\qdragapp.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\qtetrix.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\qtetrixb.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\tetrix.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\tpiece.obj



FORCE:

distclean: clean
	-$(DEL_FILE) $(TARGET)

####### Compile

tmp\obj\release_mt_shared\gtetrix.obj: gtetrix.cpp  \
		gtetrix.h \
		tpiece.h \
		

tmp\obj\release_mt_shared\qdragapp.obj: qdragapp.cpp  \
		qdragapp.h \
		..\..\include\qptrlist.h \
		..\..\include\qintdict.h \
		..\..\include\qpopupmenu.h \
		..\..\include\qguardedptr.h \
		..\..\include\qcolor.h \
		..\..\include\qwidget.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qcursor.h \
		..\..\include\qobjectlist.h \
		tmp\moc\release_mt_shared\qdragapp.moc \
		..\..\include\qapplication.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qpalette.h \
		..\..\include\qtranslator.h \
		..\..\include\qstrlist.h \
		..\..\include\qstringlist.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qfont.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qbrush.h \
		..\..\include\qgdict.h \
		..\..\include\qframe.h \
		..\..\include\qmenudata.h \
		..\..\include\qiconset.h \
		..\..\include\qkeysequence.h \
		..\..\include\qsignal.h \
		..\..\include\qpixmap.h \
		..\..\include\qvariant.h \
		

tmp\obj\release_mt_shared\qtetrix.obj: qtetrix.cpp  \
		qtetrix.h \
		..\..\include\qapplication.h \
		..\..\include\qlabel.h \
		..\..\include\qdatetime.h \
		qtetrixb.h \
		..\..\include\qframe.h \
		..\..\include\qlcdnumber.h \
		..\..\include\qpushbutton.h \
		..\..\include\qpainter.h \
		gtetrix.h \
		tpiece.h \
		..\..\include\qwidget.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qpalette.h \
		..\..\include\qfont.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qptrlist.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h \
		..\..\include\qbitarray.h \
		..\..\include\qbutton.h \
		..\..\include\qiconset.h \
		..\..\include\qkeysequence.h \
		..\..\include\qpixmap.h \
		..\..\include\qpen.h \
		..\..\include\qpointarray.h \
		..\..\include\qwmatrix.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qtranslator.h \
		..\..\include\qgdict.h \
		

tmp\obj\release_mt_shared\qtetrixb.obj: qtetrixb.cpp  \
		qtetrixb.h \
		qtetrix.h \
		..\..\include\qtimer.h \
		..\..\include\qpainter.h \
		gtetrix.h \
		..\..\include\qframe.h \
		tpiece.h \
		..\..\include\qwidget.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qpalette.h \
		..\..\include\qfont.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qptrlist.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h \
		..\..\include\qlcdnumber.h \
		..\..\include\qlabel.h \
		..\..\include\qpushbutton.h \
		..\..\include\qbitarray.h \
		..\..\include\qbutton.h \
		..\..\include\qiconset.h \
		..\..\include\qkeysequence.h \
		..\..\include\qpixmap.h \
		..\..\include\qpen.h \
		..\..\include\qpointarray.h \
		..\..\include\qwmatrix.h \
		

tmp\obj\release_mt_shared\tetrix.obj: tetrix.cpp  \
		qtetrix.h \
		qdragapp.h \
		..\..\include\qfont.h \
		qtetrixb.h \
		..\..\include\qframe.h \
		..\..\include\qlcdnumber.h \
		..\..\include\qlabel.h \
		..\..\include\qpushbutton.h \
		..\..\include\qpainter.h \
		gtetrix.h \
		tpiece.h \
		..\..\include\qwidget.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qpalette.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qptrlist.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h \
		..\..\include\qbitarray.h \
		..\..\include\qbutton.h \
		..\..\include\qiconset.h \
		..\..\include\qkeysequence.h \
		..\..\include\qpixmap.h \
		..\..\include\qpen.h \
		..\..\include\qpointarray.h \
		..\..\include\qwmatrix.h \
		..\..\include\qapplication.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qtranslator.h \
		..\..\include\qgdict.h \
		

tmp\obj\release_mt_shared\tpiece.obj: tpiece.cpp  \
		tpiece.h \
		..\..\include\qstring.h \
		..\..\include\qcstring.h \
		..\..\include\qwinexport.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		

tmp\obj\release_mt_shared\moc_qdragapp.obj: tmp\moc\release_mt_shared\moc_qdragapp.cpp  qdragapp.h ..\..\include\qapplication.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qpalette.h \
		..\..\include\qtranslator.h \
		..\..\include\qstrlist.h \
		..\..\include\qstringlist.h \
		..\..\include\qwidget.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qfont.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qptrlist.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qgdict.h

tmp\obj\release_mt_shared\moc_qtetrix.obj: tmp\moc\release_mt_shared\moc_qtetrix.cpp  qtetrix.h qtetrixb.h \
		..\..\include\qframe.h \
		..\..\include\qlcdnumber.h \
		..\..\include\qlabel.h \
		..\..\include\qpushbutton.h \
		..\..\include\qpainter.h \
		gtetrix.h \
		tpiece.h \
		..\..\include\qwidget.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qpalette.h \
		..\..\include\qfont.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qptrlist.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h \
		..\..\include\qbitarray.h \
		..\..\include\qbutton.h \
		..\..\include\qiconset.h \
		..\..\include\qkeysequence.h \
		..\..\include\qpixmap.h \
		..\..\include\qpen.h \
		..\..\include\qpointarray.h \
		..\..\include\qwmatrix.h

tmp\obj\release_mt_shared\moc_qtetrixb.obj: tmp\moc\release_mt_shared\moc_qtetrixb.cpp  qtetrixb.h gtetrix.h \
		..\..\include\qframe.h \
		tpiece.h \
		..\..\include\qwidget.h \
		..\..\include\qwindowdefs.h \
		..\..\include\qobject.h \
		..\..\include\qpaintdevice.h \
		..\..\include\qpalette.h \
		..\..\include\qfont.h \
		..\..\include\qfontmetrics.h \
		..\..\include\qfontinfo.h \
		..\..\include\qsizepolicy.h \
		..\..\include\qwinexport.h \
		..\..\include\qobjectdefs.h \
		..\..\include\qstring.h \
		..\..\include\qnamespace.h \
		..\..\include\qwindowdefs_win.h \
		..\..\include\qglobal.h \
		..\..\include\qconfig-minimal.h \
		..\..\include\qconfig-small.h \
		..\..\include\qconfig-medium.h \
		..\..\include\qconfig-large.h \
		..\..\include\qconfig.h \
		..\..\include\qmodules.h \
		..\..\include\qfeatures.h \
		..\..\include\qcstring.h \
		..\..\include\qmemarray.h \
		..\..\include\qgarray.h \
		..\..\include\qshared.h \
		..\..\include\qevent.h \
		..\..\include\qregion.h \
		..\..\include\qmime.h \
		..\..\include\qpair.h \
		..\..\include\qrect.h \
		..\..\include\qsize.h \
		..\..\include\qpoint.h \
		..\..\include\qmap.h \
		..\..\include\qptrlist.h \
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qtextstream.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h

tmp\moc\release_mt_shared\moc_qdragapp.cpp: $(MOC) qdragapp.h
	$(MOC) qdragapp.h -o tmp\moc\release_mt_shared\moc_qdragapp.cpp

tmp\moc\release_mt_shared\moc_qtetrix.cpp: $(MOC) qtetrix.h
	$(MOC) qtetrix.h -o tmp\moc\release_mt_shared\moc_qtetrix.cpp

tmp\moc\release_mt_shared\moc_qtetrixb.cpp: $(MOC) qtetrixb.h
	$(MOC) qtetrixb.h -o tmp\moc\release_mt_shared\moc_qtetrixb.cpp

tmp\moc\release_mt_shared\qdragapp.moc: $(MOC) qdragapp.cpp
	$(MOC) qdragapp.cpp -o tmp\moc\release_mt_shared\qdragapp.moc

####### Install

install:  

uninstall:  

