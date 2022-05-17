# Greatest Developer Portfolio ...Ever

A collection of project ideas and inspiration to build and add to your developer portoflio.

To add your project idea to the list, clone this repo and edit `projects/data.json` to add your project ideas using following the json strucutre below.

## Object data structure is as follows:

```json
  {
    "title": "PROJECT TITLE",
    "description": "BRIEF PROJECT DESCRIPTION",
    "tutorial": "SAMPLE TUTORIAL URL",
    "type": "WebApp",
    "role": ["frontend", "backend", "fullstack", "android", "ios"],
    "stack": ["react", "javascript", "php", "ios", "java"]
  },
```

`title`

Give the project a title.

`description`

Give the project a brief description

`tutorial` (URL)

If the project has a suggested tutorial or example to link to. (Optional).

`type`

This is project type and can be of the following types:

```
WebApp, MobileApp, API, Service, Component, Plugin, Theme
```

`role` (Array)

The role of the Developer, can be an array of the following:

```
["frontend", "backend", "fullstack", "android", "ios"]
```

`stack` (Array)

The suggested stack to use for the project, can be an array of tech stacks:

```
["react", "javascript", "php", "ios", "java"]
```
