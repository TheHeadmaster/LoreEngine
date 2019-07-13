#TintScreen
``` csharp
public static void TintScreen(Color color);
```

Tints the screen with a specified color. The effect will persist until another overlay is used.

Remarks:
This effect will play instantly with no transition. The calling thread will be blocked until its finished, which is useful for timing visuals in succession.

Overlays are drawn just under the UI layer, but above everything else. This is so that UI elements such as message boxes can be displayed while the screen is black.
