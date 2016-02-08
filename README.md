# Admin CSS guide

This repository contains the guidelines for writing CSS and SCSS in the Shopify admin.

## Table of contents

* [Introduction](introduction#introduction)
  * [Tools & frameworks](introduction#tools--frameworks)
  * [Philosophy & structure](introduction#philosophy--structure)
* [Building a component](building-a-component)
  * [Basic conventions](building-a-component#basic-conventions)
  * [CSM](building-a-component#csm)
    * [Components](building-a-component#components)
    * [Sub-components](building-a-component#sub-components)
    * [Modifiers](building-a-component#modifiers)
    * [Component modifiers that affect subcomponents](building-a-component#component-modifiers-that-affect-subcomponents)
    * [State](building-a-component#state)
  * [When to split a component](building-a-component#when-to-split-a-component)
  * [Contextual styles](building-a-component#contextual-styles)
  * [Functional variables](building-a-component#functional-variables)
  * [Layout subcomponents](building-a-component#layout-subcomponents)
* [CSS best practices](css-best-practices#css-best-practices)
  * [Code like it's 2020](css-best-practices#code-like-its-2020)
  * [Selector specificity](css-best-practices#selector-specificity)
  * [A note on attribute selectors](css-best-practices#a-note-on-attribute-selectors)
  * [Size units](css-best-practices#size-units)
  * [Context sensitivity](css-best-practices#context-sensitivity)
  * [Format](css-best-practices#format)
  * [Declaration order](css-best-practices#declaration-order)
* [Sass (SCSS) best practices](sass-best-practices#sass-scss-best-practices)
  * [Nest only when necessary](sass-best-practices#nest-only-when-necessary)
  * [Global vs. local variables/mixins](sass-best-practices#global-vs-local-variablesmixins)
  * [`@extends`](sass-best-practices#extends)
  * [Filename naming convention](sass-best-practices#filename-naming-convention)
  * [Commenting best practice](sass-best-practices#commenting-best-practice)
  * [Variable naming convention](sass-best-practices#variable-naming-convention)
* [Block comment documentation guide](comments/Readme.md)

Continue on to [the Introduction →](introduction#introduction)