## Update default python version of MAC to the latest python version

brew install python --> install the latest Python.
ls -l /usr/local/bin/python* --> List all Python versions installed on your system.
ln -s -f /usr/local/bin/python[your-latest-version-just-installed] /usr/local/bin/python --> Change default Python version to the latest version.
