# $FreeBSD$

PORTNAME=	wai-extra
PORTVERSION=	3.0.22.1
PORTREVISION=	2
CATEGORIES=	www haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Provides some basic WAI handlers and middleware

LICENSE=	MIT

DEPRECATED=		Haskell libraries are getting pushed out of the ports tree. If you are using this port for development, consider switching to cabal sandboxes (old way), cabal new-build (new way), or use devel/stack. If you believe this port shouldn't be removed, contact haskell@FreeBSD.org
EXPIRATION_DATE=	2019-04-14

USE_CABAL=	aeson ansi-terminal base64-bytestring blaze-builder \
		case-insensitive cookie data-default-class \
		fast-logger http-types iproute lifted-base \
		network old-locale resourcet streaming-commons \
		stringsearch unix-compat vault void \
		wai wai-logger word8 zlib

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
