---
title: "Java Action Call"
parent: "Action+Call+Activities"
space: "Reference Guide 5"
---


Java action call can be used to call a Java action. Arguments can be passed to the action and the result can be stored in a variable. Java actions can be found in the resources section of a model.

See [Java Actions](Java+Actions) for information on how to use this section.

<div class="alert alert-info">{% markdown %}

See [Microflow Element Common Properties](Microflow+Element+Common+Properties) for properties that all activities share (e.g. caption). This page only describes the properties specific to the action.

{% endmarkdown %}</div>

## Action Properties

### Java action

The Java action that is called by this activity.

### Parameters

For each parameter of the Java action you have to supply an argument of the same type. The values of the arguments can be expressed using [microflow expressions](Microflow+Expressions).

## Output Properties

### Return type

The return type is the type of the result of the Java action.

### Variable name

The result of the Java action will be stored in a variable with this name.
