COMMENT =        Text-based PowerPoint (ncurses slideshow tool)

DISTNAME =       tpp-1.3.1
CATEGORIES =     graphics
HOMEPAGE =       https://www.ngolde.de/tpp.html
MAINTAINER =     Jan Helbling <jhelb1993@gmail.com>
PERMIT_PACKAGE = Yes
PERMIT_DISTFILES =Yes

MASTER_SITES =   http://www.ngolde.de/download/

NO_BUILD =       Yes

do-install:
	${INSTALL_SCRIPT} ${WRKSRC}/tpp.rb ${PREFIX}/bin/tpp
	${INSTALL_MAN} ${WRKSRC}/doc/tpp.1 ${PREFIX}/man/man1/

.include <bsd.port.mk>
