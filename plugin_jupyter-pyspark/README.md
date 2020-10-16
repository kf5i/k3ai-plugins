# Plugin Template

Build plugins for k3ai is very simple, this guide will drive you through the steps needed to build one and contribute to the project.

The first step is to learn the structure of the plugins repository: https://github.com/kf5i/k3ai-plugins
The repo is structured in a very simple way, for each plugin you have a corresponding folder named:

- plugin_<PLUGIN NAME>

where <PLUGIN NAME> is the name of your plugin (i.e.: plugin_kfpipelines identify the Kubeflow pipelines based on default  Argo workflows engine).

The plugin folder should contain two files:

- README.md
- install

*Notice the absence of an extension for the install file.*
The plugin_template  contains a starting point for contributors.
