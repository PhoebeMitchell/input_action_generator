# Summary

Godot plugin for generating input actions from the actions.

Creates a C# class with properties for each action defined in a project's input map.

This eliminates string dependency when using actions in code.

# Installation

1) Createa folder in your Godot project root called `addons`
1) Clone the repository into the `addons` folder
   - The hierarchy should look like `addons > input_action_generator`
1) Go to `Project > Project Settings... > Plugins`
1) Find `Input Action Generator` in the list and click `On`

# Usage

1) Go to `Project > Tools` and click `Generate Input Actions`
   - This generates a file called `InputActions.cs` in your project's root folder
1) To change the file path the script is generated at:
   1) Go to `Editor > Editor Settings...`
   1) Enable `Advanced Settings`
   1) Scroll to `Input Action Generator` in the sidebar
   1) Set the path under the `Output Path` setting
       - e.g. `Scripts/PlayerInput`
