# Hotter
Utilities for Unity

## How to Use
* Hotter.dll: Add to Assets/Plugins
* Example.cs: Add to your Scene & run

### Debug
Custom Debug that overrides UnityEngine.Debug.

```c#
// Mute
Debug.IsEnabled = false;

// Filter
Debug.Add( this );
Debug.Log( this, "Message" );

// FontSize
Debug.FontSize = 14;

// RichText
Debug.LogBold( "LogBold" );
Debug.LogItalic( "LogItalic" );
Debug.LogColor( "LogRed", "red" );
```
