# Maintainer: James An <james@jamesan.ca>

pkgname=drupal-l10n-mk
_language=mk
pkgver=7.31
pkgrel=1
pkgdesc="Drupal core translation: Macedonian"
arch=('any')
url="http://localize.drupal.org/translate/downloads"
_watch="http://localize.drupal.org/translate/downloads"
license=('nonfree')
depends=('drupal')
source=("http://ftp.drupal.org/files/translations/7.x/drupal/drupal-7.31.mk.po")
md5sums=('8ec5eec57a400baddbb613874cde4c33')
package () {
    install -Dm644 "${srcdir}/drupal-${pkgver}.${_language}.po" "${pkgdir}/usr/share/webapps/drupal/profiles/standard/translations/drupal-${pkgver}.${_language}.po"
}
