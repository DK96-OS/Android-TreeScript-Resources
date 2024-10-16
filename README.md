# Android TreeScript Resources
A repository of TreeScript files for building Android apps.

TreeScript files are organized into groups corresponding to different app layers.

## Android App Layers
| **Layer** | **Builder Directory** |
|:----------|:--------------------|
| **Project** | Project Root |
| **Module** | Project Root |
| **Source Set** | Module Directory |
| **Resources** | Module Directory |

These layers are explained in more detail in the following subsections.

### Project
TreeScript starting at the project's root directory.

These Trees generally contain the following:
- Project Gradle Files
- Application Module

### Module
TreeScript starting at the project's root directory. Always begins with the module directory at the top.

These Trees contain:
- Module Gradle build file
- Source Directory

May Contain:
- One or more source sets
- Resources directories
- Android Manifest file

### Source Set
TreeScript starting in a module directory.
- Creates one or more source sets
- Does not include source packages

### Resources
TreeScript starting in a module directory.
- Creates one or more resource directories
- May include resource files
