
# Install Java
- perform search of available java JDK: `apt-cache search openjdk`

# Set Java Home
1. sudo vim **/etc/environment**
2. press 'i' to insert mode
3. paste in `JAVA_HOME="/usr/lib/jvm/java-21-openjdk-amd64"`
4. press ':' then 'wq' to save and exit
5. restart your shell