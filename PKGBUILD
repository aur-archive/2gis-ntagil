# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-ntagil
pkgver=3
pkgrel=1
pkgdesc="Map of Ntagil for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Ntagil-${pkgver}.orig.zip")
md5sums=('d9cdecf41f3d05d84f3419e851d9d599')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Ntagil.dgdat "${startdir}/pkg/opt/2gis/ntagil.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Ntagil.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Ntagil.dglf" || return 1
     
}

