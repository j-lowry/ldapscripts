## Process this file with automake to produce Makefile.in
sbin_SCRIPTS = ldapaddgroup\
		ldapaddmachine\
		ldapadduser\
		ldapaddusertogroup\
		ldapdeletegroup\
		ldapdeletemachine\
		ldapdeleteuser\
		ldapdeleteuserfromgroup\
		ldapfinger\
		ldapgid\
		ldapid\
		ldapinit\
		ldapmodifygroup\
		ldapmodifymachine\
		ldapmodifyuser\
		ldaprenamegroup\
		ldaprenamemachine\
		ldaprenameuser\
		ldapsetpasswd\
		ldapsetprimarygroup\
		lsldap

CLEANFILES =  $(sbin_SCRIPTS)
EXTRA_DIST = ldapaddgroup.in\
		ldapaddmachine.in\
		ldapadduser.in\
		ldapaddusertogroup.in\
		ldapdeletegroup.in\
		ldapdeletemachine.in\
		ldapdeleteuser.in\
		ldapdeleteuserfromgroup.in\
		ldapfinger.in\
		ldapgid.in\
		ldapid.in\
		ldapinit.in\
		ldapmodifygroup.in\
		ldapmodifymachine.in\
		ldapmodifyuser.in\
		ldaprenamegroup.in\
		ldaprenamemachine.in\
		ldaprenameuser.in\
		ldapsetpasswd.in\
		ldapsetprimarygroup.in\
		lsldap.in

do_subst = sed -e 's,[@]sysconfdir[@],$(sysconfdir),g'

ldapaddgroup: ldapaddgroup.in Makefile
	$(do_sub) < $(srcdir)/ldapaddgroup.in > ldapaddgroup
	chmod 0755 ldapaddgroup

ldapaddmachine: ldapaddmachine.in Makefile
	$(do_sub) < $(srcdir)/ldapaddmachine.in > ldapaddmachine
	chmod 0755 ldapaddmachine

ldapadduser: ldapadduser.in Makefile
	$(do_sub) < $(srcdir)/ldapadduser.in > ldapadduser
	chmod 0755 ldapadduser

ldapaddusertogroup: ldapdaddusertogroup.in Makefile
	$(do_sub) < $(srcdir)/ldapaddusertogroup.in > ldapaddusertogroup
	chmod 0755 ldapaddusertogroup

ldapdeletegroup: ldapdeletegroup.in Makefile
	$(do_sub) < $(srcdir)/ldapdeletegroup.in > ldapdeletegroup
	chmod 0755 ldapdeletegroup

ldapdeletemachine: ldapdeletemachine.in Makefile
	$(do_sub) < $(srcdir)/ldapdeletemachineg.in > lsldap
	chmod 0755 ldapdeletemachineg

ldapdeleteuser: ldapdeleteuser.in Makefile
	$(do_sub) < $(srcdir)/ldapdeleteuser.in > ldapdeleteuser
	chmod 0755 ldapdeleteuser

ldapdeleteuserfromgroup: ldapdeleteuserfromgroup.in Makefile
	$(do_sub) < $(srcdir)/ldapdeleteuserfromgroup.in > ldapdeleteuserfromgroup
	chmod 0755 ldapdeleteuserfromgroup

ldapdeleteuser: ldapdeleteuser.in Makefile
	$(do_sub) < $(srcdir)/ldapdeleteuser.in > ldapdeleteuser
	chmod 0755 ldapdeleteuser

ldapfinger: ldapfinger.in Makefile
	$(do_sub) < $(srcdir)/ldapfinger.in > ldapfinger
	chmod 0755 ldapfinger

ldapgid: ldapgid.in Makefile
	$(do_sub) < $(srcdir)/ldapgid.in > ldapgid
	chmod 0755 ldapgid

ldapid: ldapid.in Makefile
	$(do_sub) < $(srcdir)/ldapid.in > ldapid
	chmod 0755 ldapid

ldapinit: ldapinit.in Makefile
	$(do_sub) < $(srcdir)/ldapinit.in > ldapinit
	chmod 0755 ldapinit

ldapmodifygroup: ldapmodifygroup.in Makefile
	$(do_sub) < $(srcdir)/ldapmodifygroup.in > ldapmodifygroup
	chmod 0755 ldapmodifygroup

ldapmodifymachine: ldapmodifymachine.in Makefile
	$(do_sub) < $(srcdir)/ldapmodifymachine.in > ldapmodifymachine
	chmod 0755 ldapmodifymachine

ldapmodifyuser: ldapmodifyuser.in Makefile
	$(do_sub) < $(srcdir)/ldapmodifyuser.in > ldapmodifyuser
	chmod 0755 ldapmodifyuser

ldaprenamegroup: ldaprenamegroup.in Makefile
	$(do_sub) < $(srcdir)/ldaprenamegroup.in > ldaprenamegroup
	chmod 0755 ldaprenamegroup

ldaprenamemachine: ldaprenamemachine.in Makefile
	$(do_sub) < $(srcdir)/ldaprenamemachine.in > ldaprenamemachine
	chmod 0755 ldaprenamemachine

ldaprenameuser: ldaprenameuser.in Makefile
	$(do_sub) < $(srcdir)/ldaprenameuser.in > ldaprenameuser
	chmod 0755 ldaprenameuser

ldapsetpasswd: ldapsetpasswd.in Makefile
	$(do_sub) < $(srcdir)/ldapsetpasswd.in > ldapsetpasswd
	chmod 0755 ldapsetpasswd

ldapdeleteuser: ldapdeleteuser.in Makefile
	$(do_sub) < $(srcdir)/ldapdeleteuser.in > ldapdeleteuser
	chmod 0755 ldapdeleteuser

ldapsetprimarygroup: ldapsetprimarygroup.in Makefile
	$(do_sub) < $(srcdir)/ldapsetprimarygroup.in > ldapsetprimarygroup
	chmod 0755 ldapsetprimarygroup

lsldap: lsldap.in Makefile
	$(do_sub) < $(srcdir)/lsldap.in > lsldap
	chmod 0755 lsldap
