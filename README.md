# CanvasElementVisibility
Easily hide/show Unity Canvas elements.

# Usage
## Unity Editor
Add the CanvasElementVisibility component script to the game object you want to hide/show and toggle the *Visible* property to change its visibility.

![Unity Editor Usage](Images/unity-editor-usage.png)

## Code
```csharp
gameObject.GetComponent<CanvasElementVisibility>().Visible = true;
```
