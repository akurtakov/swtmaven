# Build

Command: `mvn clean verify -Dosgi.platform=YOUR_WS.YOUR_OS.YOUR_ARCH` 
E.g. `mvn clean verify -Dosgi.platform=gtk.linux.x86_64`

# Run the app via Maven

Command: `mvn exec:java -Dexec.mainClass="com.akurtakov.App" -Dosgi.platform=gtk.linux.x86_64`