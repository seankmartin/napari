# User Experience Guidelines

## Related information

- [CZI workshop](https://chanzuckerberg.github.io/napari-plugin-accel-workshops/workshops/february.html)

## Layout

- Overview of UX
- Consitency with napari
- Menus and tooltips
- Containers and tabs

## Guiding principles

- Minimise popups
- Minimise the use of extra windows.


## Overview of UX

Briefly, what your users (not you) will come across when trying to use your software - specifically what they are trying to do, not what you have designed for.

- Evaluate assumptions, what challenge is actually being solved.
- Assess the customer journey
- Show to users and iterate with customers

Observe, reflect, make loop.

What questions you might have:

- Where might users get confused or break something?
- Does our plugin description or tutorial include all necessary information?
- Have we chosen the best GUI to help users best understand the plugin functionality?
- What other use cases might our plugin have?

## Good practices

Related [workshop Lia slides](https://docs.google.com/presentation/d/10pxnwvBBb1rYV-LEWgmn5b2n9CK93-Qc_U_CEKUD5jI/edit#slide=id.g1197662a91c_0_66) and [isabela slides](https://docs.google.com/presentation/d/1JeDCvSYxXXDBMGdtC32rQSi5TJawiZEFW-A1wqHRHhU/edit#slide=id.g11d41ea185c_0_459).

### Consistency with napari


### Group similar actions together

Containers and tabs can used to group actions together and lessen clutter.

### Add tooltips

Adding tooltips to explain paramters allows users to find the information if they need it, but it won't take up unnecessary space.

### Magicgui

There are standarised options (kind of) for different input styles, and using magicgui can make this process much simpler.

### Consider that widgets can be floated

Keep in mind that the napari viewer is configurable. Users can float (or popout) your widget windows, move them around, organise them into containers with tabs etc. So try to keep pieces of functionality well grouped together.

## NB I think there is a push towards supporting more with plugins

When that happens, I think this could be a very valuable space to desribe the UI sections (menu bar, layers, console etc.) - and what we might expect could modify each of these. Some does and don'ts style tips.

When the command palette is added the list expands etc.

### Preferences

Some information about napari preferences.