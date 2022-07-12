# Class 01 Reading Notes

## Component-Based Architecture

A component is a software object that is modular, portable, replaceable, and reusable, intended to interact with other components

### Characteristics

Components are characterized by:

- **Reusability** - while some components are designed for a specific task, they are usually designed to be reused in different situations and applications

- **Replaceable** - components may be freely substituted with other similar components

- **Not context specific** - components are designed to be able to operate in different contexts

- **Extensible** - components can be extended from existing components to provide new behavior

- **Encapsulated** - components do not exposed details of internal processes

- **Independent** - Components are designed to have minimal dependecies on other components

### Advantages

- **Ease of deployment** - if a new compatible version becomes available, it is easier to replace existing version without impacting other components or the system as a whole

- **Reduced cost**

- **Ease of develpoment** - components implement well-known interfaces and allow development without impacting other parts of the system

- **Reusable**

- **Modification of technical complexity** - through the use of a component container and its services

- **Reliability** - The overall system reliability increases since each individual component is reliable

- **System maintenance and evolution** - easy to change and update the implementation without affecting the rest of the system

- **Independent**

## Props

Props is a keyword in React that is short for "properties", and is being used for passing data from one component to another in a uni-directional flow

To use Props:

1. Define an attribute and its value

2. Pass it to a child components using Props

3. Render the Props data
