#############################################################################
# Makefile for building: i18n
# Generated by qmake (1.07a) (Qt 3.3.1) on: Mon Jan 03 00:10:32 2005
# Project:  i18n.pro
# Template: app
# Command: $(QMAKE) -spec win32-msvc -o Makefile i18n.pro
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
INCPATH	=	 -I"$(QTDIR)\include" -I"C:\Qt\3.3.1\examples\i18n" -I"tmp\moc\release_mt_shared" -I"C:\Qt\3.3.1\mkspecs\win32-msvc"
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

HEADERS =	mywidget.h
SOURCES =	main.cpp \
		mywidget.cpp
OBJECTS =	tmp\obj\release_mt_shared\main.obj \
		tmp\obj\release_mt_shared\mywidget.obj
FORMS =	
UICDECLS =	
UICIMPLS =	
SRCMOC	=	tmp\moc\release_mt_shared\moc_mywidget.cpp
OBJMOC	=	tmp\obj\release_mt_shared\moc_mywidget.obj
DIST	=	
TARGET	=	i18n.exe

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

Makefile: i18n.pro ..\..\.qmake.cache C:\Qt\3.3.1\mkspecs\win32-msvc\qmake.conf ..\..\lib\qtmain.prl
	$(QMAKE) -spec win32-msvc -o Makefile i18n.pro
qmake: 
	@$(QMAKE) -spec win32-msvc -o Makefile i18n.pro

dist:
	$(ZIP) i18n.zip $(SOURCES) $(HEADERS) $(DIST) $(FORMS) C:/Qt/3.3.1/examples/i18n/i18n.pro ..\..\lib\qtmain.prl mywidget_cs.ts mywidget_de.ts mywidget_el.ts mywidget_en.ts mywidget_eo.ts mywidget_fr.ts mywidget_it.ts mywidget_jp.ts mywidget_ko.ts mywidget_no.ts mywidget_ru.ts mywidget_zh.ts mywidget_cs.ts mywidget_de.ts mywidget_el.ts mywidget_en.ts mywidget_eo.ts mywidget_fr.ts mywidget_it.ts mywidget_jp.ts mywidget_ko.ts mywidget_no.ts mywidget_ru.ts mywidget_zh.ts 

uiclean:
mocclean:
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_mywidget.cpp
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_mywidget.obj
clean: uiclean mocclean
	-$(DEL_FILE) tmp\obj\release_mt_shared\main.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\mywidget.obj



FORCE:

distclean: clean
	-$(DEL_FILE) $(TARGET)

####### Compile

tmp\obj\release_mt_shared\main.obj: main.cpp  \
		..\..\include\qapplication.h \
		..\..\include\qtranslator.h \
		..\..\include\qfileinfo.h \
		..\..\include\qmessagebox.h \
		..\..\include\qcheckbox.h \
		..\..\include\qvbox.h \
		..\..\include\qlayout.h \
		..\..\include\qbuttongroup.h \
		..\..\include\qpushbutton.h \
		..\..\include\qsignalmapper.h \
		..\..\include\qtextcodec.h \
		mywidget.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qpalette.h \
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
		..\..\include\qfile.h \
		..\..\include\qdatetime.h \
		..\..\include\qdialog.h \
		..\..\include\qbutton.h \
		..\..\include\qkeysequence.h \
		..\..\include\qhbox.h \
		..\..\include\qframe.h \
		..\..\include\qgroupbox.h \
		..\..\include\qiconset.h \
		..\..\include\qpixmap.h \
		..\..\include\qmainwindow.h \
		..\..\include\qtoolbar.h \
		..\..\include\qdockwindow.h \
		

tmp\obj\release_mt_shared\mywidget.obj: mywidget.cpp  \
		..\..\include\qbuttongroup.h \
		..\..\include\qradiobutton.h \
		..\..\include\qlabel.h \
		..\..\include\qlistbox.h \
		..\..\include\qcombobox.h \
		..\..\include\qhbox.h \
		..\..\include\qvbox.h \
		..\..\include\qaccel.h \
		..\..\include\qpopupmenu.h \
		..\..\include\qmenubar.h \
		..\..\include\qstatusbar.h \
		..\..\include\qapplication.h \
		mywidget.h \
		..\..\include\qgroupbox.h \
		..\..\include\qframe.h \
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
		..\..\include\qbutton.h \
		..\..\include\qkeysequence.h \
		..\..\include\qscrollview.h \
		..\..\include\qpixmap.h \
		..\..\include\qscrollbar.h \
		..\..\include\qrangecontrol.h \
		..\..\include\qmenudata.h \
		..\..\include\qiconset.h \
		..\..\include\qsignal.h \
		..\..\include\qvariant.h \
		..\..\include\qdesktopwidget.h \
		..\..\include\qasciidict.h \
		..\..\include\qtranslator.h \
		..\..\include\qgdict.h \
		..\..\include\qmainwindow.h \
		..\..\include\qtoolbar.h \
		..\..\include\qdockwindow.h \
		

tmp\obj\release_mt_shared\moc_mywidget.obj: tmp\moc\release_mt_shared\moc_mywidget.cpp  mywidget.h ..\..\include\qmainwindow.h \
		..\..\include\qstring.h \
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

tmp\moc\release_mt_shared\moc_mywidget.cpp: $(MOC) mywidget.h
	$(MOC) mywidget.h -o tmp\moc\release_mt_shared\moc_mywidget.cpp

####### Install

install:  

uninstall:  

