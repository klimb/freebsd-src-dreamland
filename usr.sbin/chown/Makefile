.include <src.opts.mk>

PACKAGE= runtime
PROG= 	change-owner	
LINKS=	${BINDIR}/chown /usr/bin/chgrp
MAN=	chgrp.1 change-owner.8

HAS_TESTS=
SUBDIR.${MK_TESTS}+= tests

.include <bsd.prog.mk>
