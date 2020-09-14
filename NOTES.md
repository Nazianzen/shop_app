## Notes on state management
- We use the **provider** package for state management in flutter
- When assigning the provider for widgets, provide it at the highest possible parent widget.

## TODO
- Configure firebase for filtering products according to creatorId.
    { 
        "rules" : {
            // ...
            "products" : {
                ".indexOn" : ["creatorId"]
            }
        }
    }