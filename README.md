# opc - A CLI for OpenShift Pipeline

`opc` make it easy to work with Tekton resources in OpenShift Pipelines. It is built on top of `tkn` and `tkn-pac` and expands their capablities to the functionality and user-experience that is available on OpenShift. 

## Build

Use the default target of the Makefile:

i.e:

`make`

## Useful commands

The following commands help you understand and effectively use the OpenShift Pipelines CLI:

`opc hub`: search and install from Tekton Hub

`opc pac`: add and manage git repositories (pipelines as code)

`opc pipeline`: manage Pipelines
`opc pipelinerun`: manage PipelineRuns
`opc task`: manage Tasks
`opc clustertask`: manage ClusterTasks
`opc taskrun`: manage TaskRuns

`opc triggerbinding`: manage TriggerBindings
`opc clustertriggerbinding`: manage ClusterTriggerBindings
`opc triggertemplate`: manage TriggerTemplates
`opc eventlistener`: manage EventListeners

## Features

### Versions :

- `opc version`: Show all versions of all components
- `opc version [pac|tkn|opc]` show version of a specific component

### Completion :

`opc completions [bash|zsh|...]`

### Plugins :

tkn plugins are used for opc plugins (ie: [tkn-watch](https://github.com/chmouel/tkn-watch/) become opc watch), it doesn't try to show any opc plugins. (may change).

