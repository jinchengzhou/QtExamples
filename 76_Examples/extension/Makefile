#############################################################################
# Makefile for building: extension
# Generated by qmake (1.07a) (Qt 3.3.1) on: Mon Jan 03 00:10:29 2005
# Project:  extension.pro
# Template: app
# Command: $(QMAKE) -spec win32-msvc -o Makefile extension.pro
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
INCPATH	=	 -I"$(QTDIR)\include" -I"C:\Qt\3.3.1\examples\extension" -I"tmp\moc\release_mt_shared" -I"C:\Qt\3.3.1\mkspecs\win32-msvc"
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

HEADERS =	
SOURCES =	main.cpp
OBJECTS =	tmp\obj\release_mt_shared\main.obj \
		tmp\obj\release_mt_shared\mainform.obj \
		tmp\obj\release_mt_shared\dialogform.obj \
		tmp\obj\release_mt_shared\extension.obj
FORMS =	mainform.ui \
		dialogform.ui \
		extension.ui
UICDECLS =	mainform.h \
		dialogform.h \
		extension.h
UICIMPLS =	mainform.cpp \
		dialogform.cpp \
		extension.cpp
SRCMOC	=	tmp\moc\release_mt_shared\moc_mainform.cpp \
		tmp\moc\release_mt_shared\moc_dialogform.cpp \
		tmp\moc\release_mt_shared\moc_extension.cpp
OBJMOC	=	tmp\obj\release_mt_shared\moc_mainform.obj \
		tmp\obj\release_mt_shared\moc_dialogform.obj \
		tmp\obj\release_mt_shared\moc_extension.obj
DIST	=	
TARGET	=	extension.exe

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

Makefile: extension.pro ..\..\.qmake.cache C:\Qt\3.3.1\mkspecs\win32-msvc\qmake.conf ..\..\lib\qtmain.prl
	$(QMAKE) -spec win32-msvc -o Makefile extension.pro
qmake: 
	@$(QMAKE) -spec win32-msvc -o Makefile extension.pro

dist:
	$(ZIP) extension.zip $(SOURCES) $(HEADERS) $(DIST) $(FORMS) C:/Qt/3.3.1/examples/extension/extension.pro ..\..\lib\qtmain.prl mainform.ui.h dialogform.ui.h extension.ui.h  

uiclean:
	-$(DEL_FILE) mainform.h
	-$(DEL_FILE) dialogform.h
	-$(DEL_FILE) extension.h
	-$(DEL_FILE) mainform.cpp
	-$(DEL_FILE) dialogform.cpp
	-$(DEL_FILE) extension.cpp
mocclean:
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_mainform.cpp
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_dialogform.cpp
	-$(DEL_FILE) tmp\moc\release_mt_shared\moc_extension.cpp
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_mainform.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_dialogform.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\moc_extension.obj
clean: uiclean mocclean
	-$(DEL_FILE) tmp\obj\release_mt_shared\main.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\mainform.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\dialogform.obj
	-$(DEL_FILE) tmp\obj\release_mt_shared\extension.obj



FORCE:

distclean: clean
	-$(DEL_FILE) $(TARGET)

####### Compile

tmp\obj\release_mt_shared\main.obj: main.cpp  \
		mainform.h \
		

mainform.h: mainform.ui 
	$(UIC) mainform.ui -o mainform.h

mainform.cpp: mainform.h mainform.ui 
	$(UIC) mainform.ui -i mainform.h -o mainform.cpp

dialogform.h: dialogform.ui 
	$(UIC) dialogform.ui -o dialogform.h

dialogform.cpp: dialogform.h dialogform.ui 
	$(UIC) dialogform.ui -i dialogform.h -o dialogform.cpp

extension.h: extension.ui 
	$(UIC) extension.ui -o extension.h

extension.cpp: extension.h extension.ui 
	$(UIC) extension.ui -i extension.h -o extension.cpp

tmp\obj\release_mt_shared\mainform.obj: mainform.cpp  \
		mainform.ui.h \
		mainform.h \
		

tmp\obj\release_mt_shared\dialogform.obj: dialogform.cpp  \
		extension.h \
		dialogform.ui.h \
		dialogform.h \
		

tmp\obj\release_mt_shared\extension.obj: extension.cpp  \
		extension.ui.h \
		extension.h \
		

tmp\obj\release_mt_shared\moc_mainform.obj: tmp\moc\release_mt_shared\moc_mainform.cpp  mainform.h 

tmp\obj\release_mt_shared\moc_dialogform.obj: tmp\moc\release_mt_shared\moc_dialogform.cpp  dialogform.h 

tmp\obj\release_mt_shared\moc_extension.obj: tmp\moc\release_mt_shared\moc_extension.cpp  extension.h 

tmp\moc\release_mt_shared\moc_mainform.cpp: $(MOC) mainform.h
	$(MOC) mainform.h -o tmp\moc\release_mt_shared\moc_mainform.cpp

tmp\moc\release_mt_shared\moc_dialogform.cpp: $(MOC) dialogform.h
	$(MOC) dialogform.h -o tmp\moc\release_mt_shared\moc_dialogform.cpp

tmp\moc\release_mt_shared\moc_extension.cpp: $(MOC) extension.h
	$(MOC) extension.h -o tmp\moc\release_mt_shared\moc_extension.cpp

####### Install

install:  

uninstall:  

