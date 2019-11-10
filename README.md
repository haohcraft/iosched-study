## Goal
Study Google I/O app for good Android dev patterns

## Content
1. Navigation Tool bar



## Navigation
### Material Design Read
[link](https://material.io/design/navigation/understanding-navigation.html#)

1. Types of Navigation
- Lateral navigation, move b/w screen at the same level of hierarchy
    - drawers
    - bottom navigation
    - tab

- Forward navigation
    - Downward, parent -- child
    - Sequentially, such as a checkout process
    - Directly

- Reverse navigation
    - upward navigation, allows users to navigate one level upwards within a single app’s hierarchy, until the app’s home or top-level screen is reached. For example, the Up arrow in a top app bar is a form of upwards reverse navigation.
    - considerations 
    
    
2. Top App Bars
[link](https://material.io/develop/android/components/app-bar-layout/)

The Top App Bar was previously termed action bar.
[Anatomy](https://material.io/components/app-bars-top/#anatomy)
[Behavior](https://material.io/components/app-bars-top/#behavior)
    - scrolling
    - nesting actions

Contextual action bar

3. Theming
- h6 headline

4. Spec
[ink](https://material.io/components/app-bars-top/#specs)
 

5. Build a Material Theme
[Link](https://github.com/material-components/material-components-android/tree/master/material-theme-builder)
- type.xml, typography
    - how to add fonts in Android Studio, [link](https://developer.android.com/guide/topics/ui/look-and-feel/downloadable-fonts)
- shape.xml
    - [shape customization tool](https://material.io/design/shape/about-shape.html#shape-customization-tool)
    - [shape scheme](https://material.io/design/shape/applying-shape-to-ui.html#)
- color.xml
    - [color palette](https://material.io/design/color/the-color-system.html#tools-for-picking-colors)