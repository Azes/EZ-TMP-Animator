# EZ TMP Animator

**EZ TMP Animator** is a powerful and lightweight Unity tool designed to bring your **TextMeshPro** UI to life. It allows you to create complex, high-performance text animations by manipulating individual characters through rich text tags automatically.

---

## 🚀 Features

* **Combine Multiple Effects:** Mix and match Wave, Zoom, Rotation, and Color effects simultaneously.
* **Advanced Color Control:** Supports solid colors, random color shifting, blinking effects, and animated gradients (Horizontal/Vertical).
* **Dynamic Character Effects:**
    * **Wave:** Bouncy sine-wave motions.
    * **Roll-in:** Spin characters into place with custom angles.
    * **Zoom Slide:** Dynamic scaling of individual letters.
    * **Fade In/Out:** Smooth alpha transitions for typewriter or reveal effects.
* **Performance:** Optimized to update only when changes occur, keeping your UI snappy.
* **Full Editor Integration:** Real-time preview directly in the Unity Scene View without pressing Play.

---

## 📸 Examples & Screenshots

*(Add your GIFs or Screenshots here to showcase your tool!)*

| Feature | Preview |
| :--- | :--- |
| ![e1](https://your-link-here.com/image1.gif) |
| ![e2](https://your-link-here.com/image2.gif) |
| ![e3](https://your-link-here.com/image2.gif) |
| ![e4](https://your-link-here.com/image2.gif) |
| ![e5](https://your-link-here.com/image2.gif) |
| ![e6](https://your-link-here.com/image2.gif) |
| ![e7](https://your-link-here.com/image2.gif) |
| ![e8](https://your-link-here.com/image2.gif) |
| ![e9](https://your-link-here.com/image2.gif) |
| ![e10](https://your-link-here.com/image2.gif) |
---

## 🛠 Usage & Integration

### Control via Timeline or Code
The TMP Animator can be controlled manually or synchronized with other systems:
1.  **Manual Phase:** Use the `AnimatePhase` or `sliderValue` in the inspector to animate via **Unity Timeline** or Animation clips.
2.  **Scripting:** Access the component via code to change text or states dynamically:

```csharp
public TMP_Animation myAnimator;

void Start() {
    // Change text via script
    myAnimator.SetText("Hello World!");
    
    // Set animation progress (0.0 to 1.0)
    myAnimator.SetAnimationState(0.5f);
}
