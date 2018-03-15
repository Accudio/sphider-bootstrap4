# Bootstrap 4 Sphider Theme
[![GitHub](https://img.shields.io/badge/GitHub-Accudio-0366d6.svg)](https://github.com/Accudio) [![Twitter](https://img.shields.io/badge/Twitter-@accudio-1DA1F2.svg)](https://twitter.com/accudio) [![Website](https://img.shields.io/badge/Website-accudio.com-4B86AF.svg)](https://accudio.com) [![Donate](https://img.shields.io/badge/Donate-Paypal-009cde.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=alistair.shepherd@hotmail.co.uk&item_name=Supporting+open+source+projects+by+Alistair+Shepherd&currency_code=GBP)

A theme based on [Bootstrap 4][bootstrapurl] for the [Sphider][sphiderurl] PHP search engine and spider, a useful PHP-based spider and search interface with many advanced features, that simply lacks a modern interface. The theme features a minimal, responsive interface designed for use with modern sites and devices.

## Demo

You can see a demo of the theme at [accudio.com/sitesearch](https://accudio.com/sitesearch/), which displays results from accudio.com and sphider.eu.

## Requirements

All required is a working installation of [Sphider][sphiderdown] or one of it's forks. The theme has been tested with Sphider-PDO v1.3.10, but should work on many versions, including of the forks [Sphider Plus][sphiderplus] and [Sphider Pro][sphiderpro].

## Installation

1. Download the latest release zip file: ```wget https://github.com/Accudio/sphider-bootstrap4/releases/download/v1.0.0/sphider-bootstrap4-v1.0.0.zip```
2. Extract the zip in the root Sphider directory: ```unzip sphider-bootstrap4-v1.0.0.zip```.
3. Ensure ```templates/``` includes the folder ```bootstrap4```.
4. Log in to Sphider administration page:
	1. Go to 'Settings';
	2. Under General Settings and Search Template, select ```bootstrap4```;
	3. 'Save Changes' at the bottom of the page. 
5. All new searches made will display the new theme.

## Version History

- v1.0.0 - Initial public release

## License

Copyright &copy; 2018 [Alistair Shepherd][accudiourl]. Licensed under the [GPLv3 License][licenseurl].

[bootstrapurl]:https://getbootstrap.com/
[sphiderurl]:http://www.sphider.eu/
[sphiderdown]:http://www.sphider.eu/download.php
[sphiderplus]:https://www.sphider-plus.eu/
[sphiderpro]:http://www.sphiderpro.eu/
[accudiourl]:https://accudio.com
[licenseurl]:https://github.com/accudio/sphider-bootstrap4/blob/master/LICENSE