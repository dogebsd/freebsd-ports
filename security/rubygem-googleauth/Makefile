# Created by: Po-Chuan Hsieh <sunpoet@FreeBSD.org>

PORTNAME=	googleauth
PORTVERSION=	0.16.0
CATEGORIES=	security rubygems
MASTER_SITES=	RG

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Google Auth Library for Ruby

LICENSE=	APACHE20
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	rubygem-faraday>=0.17.3<2.0:www/rubygem-faraday \
		rubygem-jwt>=1.4<3.0:www/rubygem-jwt \
		rubygem-memoist>=0.16<1:devel/rubygem-memoist \
		rubygem-multi_json>=1.11<2:devel/rubygem-multi_json \
		rubygem-os>=0.9<2.0:devel/rubygem-os \
		rubygem-signet>=0.14<1:security/rubygem-signet

USES=		gem shebangfix
USE_RUBY=	yes

NO_ARCH=	yes

SHEBANG_FILES=	.kokoro/*.sh

.include <bsd.port.mk>
