INCLUDES = -I../animate -I../animate/common_animates

COMMON_PROGS = tcldemo 

noinst_PROGRAMS = $(COMMON_PROGS)

tcldemo_SOURCES = tcldemo.c newlistview.c newlistview.h tclanimate.c tclanimate.h centersplit.c font_table.c
tcldemo_LDADD = -lmgplus -lfreetype -L../animate -lanimate -L../animate/common_animates -lcommon_animates @APP_LIBS@

SUBDIRS = res
EXTRA_DIST = 

