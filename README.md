This is a fork of https://github.com/mysteriumnetwork/node, which allows to compile working .deb package for armhf devices (like pi0 and pi3b).

The used for compiling is: `SNAPSHOT_BUILD=false RELEASE_BUILD=true BUILD_VERSION=1.29.9 mage PackageLinuxDebianArmv6l`

note: the command says _PackageLinuxDebianArmv6l_ but it generates a .deb package for amrhf, not armv6l!
