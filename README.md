# Gradient

A project to explain how to use a gradient color in something like a background of a activity.

## The gradient_background.xml

To create a gradient color, you must create a selector like the on on this project:

```xml
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item>
        <shape>
            <gradient
                android:angle="270"
                android:endColor="@color/gradient_end"
                android:startColor="@color/gradient_start"
                android:type="linear" />
        </shape>
    </item>
</selector>
```

This xml declares that we have a shape with a gradient with a 270 angle (this is a gradient starting from the top to the bottom). For this gradient tag, we must specify two atributes (endColor and startColor) to define what are the two colors for our gradient. We must also define a type attribute to specify the gradient type (in our case, linear).
