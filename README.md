# PluginTemplate

Template for Spigot plugins

## How to use

1. Run [BuildTools](https://www.spigotmc.org/wiki/buildtools/) at least once for your desired Minecraft version.
2. Import the Plugin as existing Gradle project in Eclipse.
3. To be able to see the sources in Eclipse run `gradlew fixEclipseClasspath` and refresh the project in Eclipse, **do not** refresh the Gradle project in Eclipse.
4. To start the server with a up-to-date version of your plugin simply run `gradlew startSpigot`. You may need to accect the EULA the first time doing this.
