# Galeria-triat

## Product Screens Configuration

The `screens.json` file defines the list of product screens. It lives at the repository root and contains an array of screen objects.

### Structure

Each entry in `screens.json` should look similar to the following example:

```json
[
  {
    "name": "home",
    "image": "images/home.png",
    "description": "Main screen"
  }
]
```

* `name` - unique identifier for the screen.
* `image` - path to the screenshot file.
* `description` - optional short text describing the screen.

### Adding or Editing Screens

1. Open `screens.json` in your editor.
2. Add a new object with the fields shown above or modify an existing entry.
3. Place any images referenced in the `image` field inside an appropriate folder such as `images/`.
4. Save the file and commit the changes.
