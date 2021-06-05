## Update default python version of MAC to the latest python version

brew install python --> install the latest Python.

ls -l /usr/local/bin/python* --> List all Python versions installed on your system.

ln -s -f /usr/local/bin/python[your-latest-version-just-installed] /usr/local/bin/python --> Change default Python version to the latest version.


## Grafana installation in MAC

Use Homebrew to install the most recent released version of Grafana using Homebrew package.

https://brew.sh/

[ To install Brew paste the below command in Terminal

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" ]

On the Homebrew homepage, search for Grafana. The last stable and released version is listed.

Open a terminal and enter:

brew update
brew install grafana
The brew page downloads and untars the files into /usr/local/Cellar/grafana/version.

Start Grafana using the command:

brew services start grafana

Then open http://localhost:3000/ in browser
