INCLUDES = -I$(top_srcdir)/kkstrtext -I$(top_srcdir)/kkconsui/include \
    -I$(top_srcdir)/kksystr/include -I$(top_srcdir)/intl \
    -I$(top_srcdir)/src/ui/ncurses -I$(top_srcdir)/src/debugger \
    -I$(top_srcdir)/src/executor -I$(top_srcdir)/src/project \
    -I$(top_srcdir)/src/configuration -I$(top_srcdir)/src/manager \
    -I$(top_srcdir)/src/grepper -I$(top_srcdir)/src/ui -I$(top_srcdir)/src \
    -I$(top_srcdir)/src/vcs -I$(top_srcdir)/src/tagbrowser \
    -I$(top_srcdir)/parser/include

noinst_LIBRARIES = libncursesui.a

libncursesui_a_SOURCES = ncursesui.cc uiconfiguration.cc uieditor.cc \
    uitagbrowser.cc uigrepper.cc uiwatcher.cc uiregexper.cc uivcs.cc

EXTRA_DIST = ncursesui.h uidefs.h uiconfiguration.h uieditor.h \
    uitagbrowser.h uigrepper.h uiwatcher.h uiregexper.h uivcs.h
