# $FreeBSD$

PORTNAME=	snap-server
PORTVERSION=	1.1.0.0
PORTREVISION=	3
CATEGORIES=	www haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Fast, iteratee-based, epoll-enabled web server for the Snap Framework

LICENSE=	BSD3CLAUSE

DEPRECATED=		Haskell libraries are getting pushed out of the ports tree. If you are using this port for development, consider switching to cabal sandboxes (old way), cabal new-build (new way), or use devel/stack. If you believe this port shouldn't be removed, contact haskell@FreeBSD.org
EXPIRATION_DATE=	2019-04-14

USE_CABAL=	attoparsec blaze-builder case-insensitive clock io-streams \
		io-streams-haproxy lifted-base mtl network old-locale snap-core \
		unix-compat vector

FLAGS_DEFINE=		OPENSSL

OPENSSL_DESC=		Enable HTTPS support using the HsOpenSSL library
OPENSSL_FLAG_ENABLE=	openssl
OPENSSL_FLAG_CABAL=	HsOpenSSL>=0.10

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
