# URDF Snippets

**URDF Snippets** is a VSCode extension providing useful snippets for creating URDF (Unified Robot Description Format) files quickly and easily.

## Features

- Quickly insert URDF tags like `<robot>`, `<link>`, `<joint>`, `<origin>`, and many more.
- Snippets cover robot structure, geometry, joints, materials, Gazebo extensions, and transmissions.
- Save time writing repetitive XML code for robot models.

## Usage

Type the snippet prefix and press **Tab** or **Enter** to expand:

| Prefix          | Description             |
|-----------------|-------------------------|
| `robot`         | Inserts `<robot>` tag   |
| `link`          | Inserts `<link>` tag    |
| `joint`         | Inserts `<joint>` tag   |
| `origin`        | Inserts `<origin>` tag  |
| ...             | ...                     |

Example:  
Typing `robot` + Tab will insert:

```xml
<robot>
  
</robot>
