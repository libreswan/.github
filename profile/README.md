## Libreswan VPN software

Libreswan is a free software implementation of the most widely supported and standardized VPN protocol using "IPsec" and the Internet Key Exchange ("IKE"). These standards are produced and maintained by the Internet Engineering Task Force ("IETF").

Libreswan has been under active development for over 20 years, going back to The FreeS/WAN Project founded in 1997 by John Gilmore and Hugh Daniel. For more information, see the project's [History](https://libreswan.org/wiki/History).
Libreswan supports IKE versions 1 and 2.  It runs on Linux 2.4 to 5.x, FreeBSD, NetBSD, and OpenBSD.  On Linux, it uses the built-in "XFRM" IPsec stack (linux-ipsec).  It uses the [NSS](https://libreswan.org/wiki/Using_NSS_with_libreswan) crypto library.  The list of supported RFC's can be found at [Implemented standards](https://libreswan.org/wiki/Implemented_Standards).

### Download

Libreswan is licensed under the GNU Public License ("GPLv2"). See the [License](https://www.gnu.org/licenses/gpl-2.0.html). It ships as part of many Linux distributions, including Fedora, RHEL/EPEL, Debian and Arch Linux and can be installed on those systems using the native software management tools. The source code is available as tarball and via our git repository. Older versions, patches and pre-compiled versions are available on our [download](https://download.libreswan.org/) site.

### Configuration Examples

Common configuration examples can be found in our [Wiki](https://libreswan.org/wiki). See [ipsec.conf(5)](https://testing.libreswan.org/latest/documentation/ipsec.conf.5.html) (which is part of our [documentation](https://testing.libreswan.org/latest/documentation/)) for more details on configuration options.

Furthermore, our [test cases](https://github.com/libreswan/libreswan/tree/master/testing/pluto) also document our behaviour. You can find test case results and log files on our daily testing site at [testing.libreswan.org](https://testing.libreswan.org/). . 
