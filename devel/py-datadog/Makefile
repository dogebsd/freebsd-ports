# Created by: Po-Chuan Hsieh <sunpoet@FreeBSD.org>

PORTNAME=	datadog
PORTVERSION=	0.40.1
CATEGORIES=	devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Datadog Python library

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}decorator>=3.3.2:devel/py-decorator@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}requests>=2.6.0:www/py-requests@${PY_FLAVOR}

USES=		python:3.6+
USE_PYTHON=	autoplist concurrent distutils

NO_ARCH=	yes

.include <bsd.port.mk>
