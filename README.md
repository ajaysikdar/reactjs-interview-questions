# Reactjs Interview Questions and Answers

## Basic

   * Developer- Jordan Walke
   * React was first deployed on Facebook's News Feed in 2011 and on Instagram in 2012.

1. ### What is React?
    * it is an open source frontend java script lib.
    * it is used for buiding ui specially single page application.

2. HOC- 
   * high order component is an advanced technique in react for reusing component logic.
   * It is a function that takes component and returns a new component.
   * HOC allows reuse code , logic. 
        Exm , redux connect function.
   * HOCs are best for sharing behavior between react and component.

3. Portals-
   - Portals provide a first-class way to render children into a DOM node that exists outside the DOM hierarchy of the parent component.
   -  ```ReactDOM.createPortal(child, container)```
   -  A typical use case for portals is when a parent component has an overflow: hidden or z-index style, but you need the child to visually “break out” of its container. For example, dialogs, hovercards, and tooltips.