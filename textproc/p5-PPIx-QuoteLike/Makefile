# Created by: Po-Chuan Hsieh <sunpoet@FreeBSD.org>

PORTNAME=	PPIx-QuoteLike
PORTVERSION=	0.016
CATEGORIES=	textproc perl5
MASTER_SITES=	CPAN
MASTER_SITE_SUBDIR=	CPAN:WYANT
PKGNAMEPREFIX=	p5-

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Parse Perl string literals and string-literal-like things

LICENSE=	ART10 GPLv1+
LICENSE_COMB=	dual
LICENSE_FILE_ART10=	${WRKSRC}/LICENSES/Artistic
LICENSE_FILE_GPLv1+ =	${WRKSRC}/LICENSES/Copying

BUILD_DEPENDS=	${RUN_DEPENDS}
RUN_DEPENDS=	p5-PPI>=1.117:textproc/p5-PPI \
		p5-Readonly>=0:devel/p5-Readonly

USES=		perl5
USE_PERL5=	configure

NO_ARCH=	yes

PORTSCOUT=	limit:^[0-9\.]*$$

.include <bsd.port.mk>
