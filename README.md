## karabiner settings.

https://pqrs.org/osx/karabiner/

### Reference Manual

https://pqrs.org/osx/karabiner/json.html

### Setting file path.

``` bash
# for Mac
~/.config/karabiner/assets/complex_modifications/
```

### Sample

``` json
{
  "title": "For Title",
  "rules": [
    {
      "description": "For Description",
      "manipulators": [
        {
          "type": "basic",
          "from": {
            "key_code": "caps_lock"
          },
          "to": {
            "key_code": "left_command"
          }
        }
      ]
    }
  ]
}
```

