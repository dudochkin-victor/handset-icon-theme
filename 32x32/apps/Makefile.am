themedir = $(datadir)/icons/hicolor/32x32/apps
theme_DATA = \
  icons-Applications-browser.png \
  icons-Applications-calculator.png \
  icons-Applications-calendar.png \
  icons-Applications-camera.png \
  icons-Applications-chat.png \
  icons-Applications-clock.png \
  icons-Applications-dialer.png \
  icons-Applications-email.png \
  icons-Applications-music.png \
  icons-Applications-people.png \
  icons-Applications-photos.png \
  icons-Applications-settings.png \
  icons-Applications-sms.png \
  icons-Applications-video.png \
  icons-Applications-widgets.png \
  icons-Applications-xterminal.png


EXTRA_DIST = $(theme_DATA)

install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(abs_top_srcdir)/icon-name-mapping -x $(abs_top_srcdir)/legacy-icon-mapping.xml -c apps )

MAINTAINERCLEANFILES = Makefile.in

