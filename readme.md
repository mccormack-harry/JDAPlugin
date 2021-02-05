# JDAPlugin
JDAPlugin is a Bukkit plugin which only contains the Java Discord API. <br>
The purpose of this plugin is, so you don't have to shade the whole API into your plugin.<br>
https://github.com/DV8FromTheWorld/JDA
# Use
Add the normal JDA dependency to your project <br>
Add this plugin as a dependency in your plugin.yml `depends: [JDA]` <br>
Add this plugin to your server. See: https://github.com/haz8989/JDAPlugin/releases
# How to build a different version
If your desired JDA version isn't listed in the releases section you can build it yourself:
1. Clone this repo
2. Change `project.version` in `pom.xml` to your desired JDA version
3. Run `mvn package`