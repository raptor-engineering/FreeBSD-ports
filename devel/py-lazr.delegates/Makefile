# $FreeBSD$

PORTNAME=	lazr.delegates
PORTVERSION=	2.0.3
PORTREVISION=	1
CATEGORIES=	devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	acm@FreeBSD.org
COMMENT=	Easily write objects that delegate behavior

LICENSE=	LGPL3
LICENSE_FILE=	${WRKSRC}/COPYING.txt

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}zope.interface>=0:devel/py-zope.interface \
		${PYTHON_PKGNAMEPREFIX}nose>=1.3.7:devel/py-nose

USES=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
