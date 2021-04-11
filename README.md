# Analog Clock

An analog clock built with Unity, by following [this tutorial](https://catlikecoding.com/unity/tutorials/basics/game-objects-and-scripts/).


## Notes

* Gamma vs. Linear colorspace
  * Gamma for old devices (performance)
  * Linear for better quality
* Class fields are private by default.
* Use [SerializeField] above (or before) a variable declaration to make it available in the Unity Editor without having to make the variable public.
* `Type variable = default` - assign `default` to a variable to avoid C# warnings of non-initialized objects (useful for objects set via Unity editor).
* `var` can be used to imply the type of a variable.