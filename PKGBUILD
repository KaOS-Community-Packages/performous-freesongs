pkgname=performous-freesongs
pkgver=20100713
pkgrel=1
pkgdesc="A collection of free songs for performous game"
url="http://performous.org/songs.html"
arch=('x86_64')
license=('GPL' 'CCPL')
source=(http://sourceforge.net/projects/performous/files/ultrastar-songs-libre/3/ultrastar-songs-libre-3.zip \
	http://sourceforge.net/projects/performous/files/ultrastar-songs-restricted/3/ultrastar-songs-restricted-3.zip \
	http://sourceforge.net/projects/performous/files/ultrastar-songs-shearer/1/ultrastar-songs-shearer-1.zip)
md5sums=('350226f3f971b45666b421e2e782273b'
         '702203ced031eb878d2f67b881c63c44'
         'a60fe0ef43293d332923ab1612b18c43')

package() {
  install -d ${pkgdir}/usr/share/performous/songs
  cp -r ${srcdir}/songs ${pkgdir}/usr/share/performous/songs
}

