
# Options for Installing Java and Maven
You have the option to install Java and Maven from the official Ubuntu repository (using apt-get) or from the software website (tar.gz). If you install the software using apt-get, then they should get updated automatically through the APT package manager. The downside is that they probably won't be the latest version. If you want the latest version, then download and install from the software website.

# Install Java using APT
- perform search of available java JDK: `apt-cache search openjdk`

# Install Maven using APT
`sudo apt-get install maven`

# Set Java Home
1. sudo vim **/etc/environment**
2. press 'i' to insert mode
3. paste in `JAVA_HOME="/usr/lib/jvm/java-21-openjdk-amd64"`
4. press ':' then 'wq' to save and exit
5. restart your shell

# Install Latest Maven
follow this guide: https://phoenixnap.com/kb/install-maven-on-ubuntu