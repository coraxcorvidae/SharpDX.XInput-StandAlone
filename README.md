# SharpDX.XInput-StandAlone

SharpDX.XInput-StandAlone is a standalone version of the SharpDX.XInput library version 4.2.0 in a form ready to use to add game controller support to an application.

## Examples

On creation connect to the first plugged in controller:

```C#
Controller controller = new Controller(UserIndex.One);
Controller.SetReporting(true);
````

During the gameplay loop you can get the current controller state:

```C#
var state = controller.GetState();
````
## Acknowledgments

SharpDX.XInput was originally developed by the [Alexandre Mutel](https://github.com/sharpdx/SharpDX) as part of [SharpDX](http://sharpdx.org/).
