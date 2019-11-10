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

SharpDX was originally developed by the [SharkDX Team](http://sharpdx.org/).
