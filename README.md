# sb-checkstyle-rules

Experiments with checkstyle rules for IntelliJ plugin.

Instructions:

1) Install Checkstyle-IDEA plugin (not official JetBrains plugin). Restart.

2) In Settings -> Other Settings -> Checkstyle, click + to add a
   new configuration file.  Set a description.

3) Either use "local checkstyle file" with hugin.xml or use
   "Checkstyle file accessible via HTTP" with 
   https://raw.githubusercontent.com/statsbiblioteket/sb-checkstyle-rules/master/hugin.xml

4) Mark it active, and click Ok to close the settings.

There is a new Tool Window available at the bottom named "Checkstyle".
There is an icon looking like four small blue squares in the lower right
corner of a grey rectangle.  This runs checkstyle on the current module.

See https://github.com/jshiell/checkstyle-idea for documentation.

http://checkstyle.sourceforge.net/checks.html

Pull requests adding usage with Eclipse and Netbeans welcome.

/tra 2016-04-29
