# Created by: ijliao
# $FreeBSD$

PORTNAME=	Gtk2-Html2
PORTVERSION=	0.03
PORTREVISION=	10
CATEGORIES=	x11-toolkits perl5
MASTER_SITES=	http://asofyet.org/muppet/software/gtk2-perl/
PKGNAMEPREFIX=	p5-

MAINTAINER=	bofh@FreeBSD.org
COMMENT=	Perl module for gtkhtml2 html display widget with Gtk2-Perl

LICENSE=	GPLv2

BUILD_DEPENDS=	p5-ExtUtils-Depends>=0:devel/p5-ExtUtils-Depends \
		p5-ExtUtils-PkgConfig>=0:devel/p5-ExtUtils-PkgConfig \
		p5-Glib2>=0:devel/p5-Glib2 \
		p5-Gtk2>=0:x11-toolkits/p5-Gtk2 \
		p5-Cairo>=0:graphics/p5-Cairo
RUN_DEPENDS=	p5-Glib2>=0:devel/p5-Glib2 \
		p5-Gtk2>=0:x11-toolkits/p5-Gtk2

USE_GNOME=	libgtkhtml
USES=		pkgconfig perl5
USE_PERL5=	configure
MAKE_JOBS_UNSAFE=	yes

.include <bsd.port.mk>
