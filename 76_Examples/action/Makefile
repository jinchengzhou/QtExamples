#############################################################################
# Makefile for building: action
# Generated by qmake (1.07a) (Qt 3.3.1) on: Mon Jan 03 00:10:23 2005
# Project:  action.pro
# Template: app
# Command: $(QMAKE) -spec win32-msvc -o Makefile action.pro
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
INCPATH	=	 -I"$(QTDIR)\include" -I"C:\Qt\3.3.1\examples\action" -I"tmp\moc\release_mt_shared" -I"C:\Qt\3.3.1\mkspecs\win32-msvc"
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

HEADERS =	application.h
SOURCES =	application.cpp \
		main.cpp
OBJECTS =	tmp\obj\release_mt_shared\application.obj \
		tmp\obj\release_mt_shared\main.obj
FORMS =	
UICDECLS =	
UICIMPLS =	
SRCMOC	=	tmp\moc\release_mt_shared\moc_application.cpp
OBJMOC	=	tmp\obj\release_mt_shared\moc_application.obj
DIST	=	
TARGET	=	action.exe

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

Makefile: action.pro ..\..\.qmake.cache C:\Qt\3.3.1\mkspecs\win32-msvc\qmake.conf ..\..\lib\qtmain.prl
	$(QMAKE) -spec win32-msvc -o Makefile action.pro
qmake: 
	@$(QMAKE) -spec win32-msvc -o Makefile action.pro

dist:
	$(ZIP) action.zip $(SOURCES) $(HEADERS) $(DIST) $(FORMS) C:/Qt/3.3.1/examples/action/action.pro ..\..\lib\qtmain.prl  

uiclean:
mocclean:
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_application.cpp
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_application.obj
clean: uiclean mocclean
	-$(DEL_FILE) tmp\obj\release_mt_shared\application.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\main.obj



FORCE:

distclean: clean
	-$(DEL_FILE) $(TARGET)

####### Compile

tmp\obj\release_mt_shared\application.obj: application.cpp  \
		application.h \
		..\..\include\qimage.h \
		..\..\include\qpixmap.h \
		..\..\include\qtoolbar.h \
		..\..\include\qtoolbutton.h \
		..\..\include\qpopupmenu.h \
		..\..\include\qmenubar.h \
		..\..\include\qtextedit.h \
		..\..\include\qfile.h \
		..\..\include\qfiledialog.h \
		..\..\include\qstatusbar.h \
		..\..\include\qmessagebox.h \
		..\..\include\qprinter.h \
		..\..\include\qapplication.h \
		..\..\include\qaccel.h \
		..\..\include\qtextstream.h \
		..\..\include\qpainter.h \
		..\..\include\qpaintdevicemetrics.h \
		..\..\include\qwhatsthis.h \
		..\..\include\qaction.h \
		..\..\include\qsimplerichtext.h \
		filesave.xpm \
		fileopen.xpm \
		fileprint.xpm \
		..\..\include\qmainwindow.h \
		..\..\include\qwidget.h \
		..\..\include\qptrlist.h \
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
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h \
		..\..\include\qdockwindow.h \
		..\..\include\qframe.h \
		..\..\include\qbutton.h \
		..\..\include\qiconset.h \
		..\..\include\qkeysequence.h \
		..\..\include\qmenudata.h \
		..\..\include\qsignal.h \
		..\..\include\qvariant.h \
		..\..\include\qscrollview.h \
		..\..\include\qstylesheet.h \
		..\..\include\qptrvector.h \
		..\..\include\qscrollbar.h \
		..\..\include\qrangecontrol.h \
		..\..\include\qdict.h \
		..\..\include\qgvector.h \
		..\..\include\qgdict.h \
		..\..\include\qdir.h \
		..\..\include\qdialog.h \
		..\..\include\qurloperator.h \
		..\..\include\qurlinfo.h \
		..\..\include\qfileinfo.h \
		..\..\include\qdatetime.h \
		..\..\include\qurl.h \
		..\..\include\qnetworkprotocol.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qtranslator.h \
		..\..\include\qpen.h \
		..\..\include\qpointarray.h \
		..\..\include\qwmatrix.h \
		..\..\include\qcursor.h \
		

tmp\obj\release_mt_shared\main.obj: main.cpp  \
		..\..\include\qapplication.h \
		application.h \
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
		..\..\include\qgdict.h \
		..\..\include\qmainwindow.h \
		..\..\include\qtoolbar.h \
		..\..\include\qdockwindow.h \
		..\..\include\qframe.h \
		

tmp\obj\release_mt_shared\moc_application.obj: tmp\moc\release_mt_shared\moc_application.cpp  application.h ..\..\include\qmainwindow.h \
		..\..\include\qwidget.h \
		..\..\include\qtoolbar.h \
		..\..\include\qptrlist.h \
		..\..\include\qtextstream.h \
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
		..\..\include\qdatastream.h \
		..\..\include\qvaluelist.h \
		..\..\include\qiodevice.h \
		..\..\include\qtl.h \
		..\..\include\qglist.h \
		..\..\include\qptrcollection.h \
		..\..\include\qcolor.h \
		..\..\include\qbrush.h \
		..\..\include\qstringlist.h \
		..\..\include\qstrlist.h \
		..\..\include\qdockwindow.h \
		..\..\include\qframe.h

tmp\moc\release_mt_shared\moc_application.cpp: $(MOC) application.h
	$(MOC) application.h -o tmp\moc\release_mt_shared\moc_application.cpp

####### Install

install:  

uninstall:  

