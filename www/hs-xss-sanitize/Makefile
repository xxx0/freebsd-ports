# $FreeBSD$

PORTNAME=	xss-sanitize
PORTVERSION=	0.3.5.6
CATEGORIES=	www haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Sanitize untrusted HTML to prevent XSS attacks

LICENSE=	BSD3CLAUSE

USE_CABAL=	attoparsec>=0.10.0.3 css-text>=0.1.1 network>=2.6 \
		network-uri>=2.6 tagsoup>=0.12.2 text>=0.11 utf8-string>=0.3

FLAGS_ENABLE=	network-uri

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
