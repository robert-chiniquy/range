AM_CFLAGS = -Wall -DLIBCRANGE_FUNCDIR=\"$(pkglibdir)\" -I../src @PCRE_CFLAGS@ @APR_CFLAGS@
AM_LDFLAGS = -module -L../src -lcrange @PCRE_LIBS@ @APR_LIBS@

pkglib_LTLIBRARIES = yst-ip-list.la ip.la nodescf.la

nodescf_la_SOURCES = nodescf.c
yst_ip_list_la_SOURCES = yst-ip-list.c netblock.c tinydns_ip.c \
                         hosts-netblocks.c
ip_la_SOURCES = ip.c tinydns_ip.c



