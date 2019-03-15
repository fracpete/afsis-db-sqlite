# afsis-db-sqlite

The *Africa Soil Information Service (AfSIS)* lists the copyrighted
ICRAF/ISRIC spectral library (*A Globally Distributed Soil Spectral
Library: Visible Near Infrared Diffuse Reflectance Spectra*) on their
homepage:

[http://africasoils.net/data/spectral-libraries](https://web.archive.org/web/20141229232058/http://www.africasoils.net/data/spectral-libraries)

[http://www.isric.org/data/icrafisric-spectral-library](https://web.archive.org/web/20161025184945/http://www.isric.org/data/icrafisric-spectral-library)

The download contains a Microsoft Access database with roughly 4500
spectra (wave numbers: 350-2500). This project contains an SQLite
port of this database.

## Conversion to SQLite

An [ADAMS](https://adams.cms.waikato.ac.nz/) workflow was used 
([access2sqlite.flow](https://raw.githubusercontent.com/fracpete/afsis-db-sqlite/master/access2sqlite.flow)) 
to export the MS Access database to intermediate CSV files and
then imported into a SQLite database.

## License

[Creative Commons (CC BY-NC)](https://web.archive.org/web/20161025184945/http://www.isric.org/data/icrafisric-spectral-library)
