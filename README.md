# PluginAuth

PluginAuth is a Minecraft plugin for custom authentication using a database.

## Overview

PluginAuth allows server administrators to implement custom player authentication using a database. It is designed to work with CraftBukkit or Spigot servers running Minecraft 1.19.2.

## Features

- Custom player authentication
- Integration with a database for storing player information
- Event-driven architecture for handling player connections

## Installation

1. Download the latest release JAR file from the [releases page](https://github.com/votre-utilisateur/PluginAuth/releases).
2. Place the JAR file into the "plugins" directory of your CraftBukkit or Spigot server.
3. Start or restart your Minecraft server.

## Configuration

To configure PluginAuth, modify the `config.yml` file in the "plugins/PluginAuth" directory. The configuration file allows you to specify database connection details and other settings.

```yaml
# Example configuration
database:
  url: jdbc:mysql://localhost:3306/your_database
  username: your_database_username
  password: your_database_password
