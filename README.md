# android-colors
Color resources for your android project

Available modules:
- **material**: Material Design colors (https://www.google.com/design/spec/style/color.html#color-color-palette)
- **holo**: Android Holo colors (Android 4.x default)

## How to include
```gradle
repositories { 
    // ...
    maven { url "https://jitpack.io" }
}
dependencies {
    compile 'io.freefair.android-colors:material:1.2.0'
    // or
    compile 'io.freefair.android-colors:holo:1.2.0'
}
```

## Usage
### XML
```xml
<item name="colorPrimary">@color/material_indigo_500</item>
```
```xml
<item name="colorPrimary">@color/holo_red_light</item>
```
### Java
```java
R.color.material_indigo_500
```
```java
R.color.holo_red_light
```
