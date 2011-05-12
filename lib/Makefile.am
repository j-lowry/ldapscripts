## Process this file with automake to produce Makefile.in
dist_libexec_SCRIPTS = runtime
CLEANFILES = $(dist_libexec_SCRIPTS)
EXTRA_DIST = runtime.in

do_subst = sed -e 's,[@]sysconfdir[@],$(sysconfdir),g'

runtime: runtime.in Makefile
	$(do_subst) < $(srcdir)/runtime.in > runtime
	chmod 0640 runtime

