.include <src.opts.mk>

PACKAGE=runtime
PROG=	copy-file
SRCS=	copy-file.c utils.c
CFLAGS+= -D_ACL_PRIVATE

HAS_TESTS=
SUBDIR.${MK_TESTS}=	tests

.include <bsd.prog.mk>
