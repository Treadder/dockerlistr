### Info

- Code lives in `/usr/local/bin/dockerlistr`
- Provides a command `dockerlistr` to list running Docker containers with formatted output

### Development / Installation

- Build a new Debian package with: `dpkg-deb --build dockerlistr-1.0`
- Install with: `sudo dpkg -i dockerlistr-1.0.deb`
- Uninstall with: `sudo dpkg -r dockerlistr`
