# Minecraft spigot plugin template

A lightweight, ready-to-use template for creating Minecraft plugins using **Java** and **Maven**.  
This repository provides a clean, standard structure for Spigot plugins.

## Project Structure
```
minecraft-java-plugin-template/
├── src/ # Java source files (main and test)
├── pom.xml # Maven configuration
├── .gitignore # Ignore build files, IDE settings, etc.
├── LICENSE # MIT License
└── README.md # Project documentation
```

## How to use

Rename the project
Update the following:
- In pom.xml → change the `<groupId>`, `<artifactId>`, and `<name>`
- In src/main/java → rename the package and main plugin class
- In plugin.yml (create it under src/main/resources if missing) → update the main path and plugin metadata

## License

This template is released under the MIT License - feel free to use, modify, and distribute it for any project.
