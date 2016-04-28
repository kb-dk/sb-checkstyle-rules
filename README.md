# sb-checkstyle-rules

Experiments with checkstyle rules for IntelliJ plugin.

Instructions:

1) Install Checkstyle-IDEA plugin (not official JetBrains plugin). Restart.

2) In Preferences -> Other Settings -> Checkstyle, click + to add a
   new configuration file.  Set a description.

3) Either use "local checkstyle file" with hugin.xml or use
   "Checkstyle file accessible via HTTP" with 
   https://raw.githubusercontent.com/statsbiblioteket/sb-checkstyle-rules/master/hugin.xml

4) Mark it active, and click Ok to close the settings.

Checkstyle is now run as an inspection by default as part of normal compilation.

See https://github.com/jshiell/checkstyle-idea for documentation.

http://checkstyle.sourceforge.net/checks.html


/tra 2016-04-28