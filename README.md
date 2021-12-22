<h1 align="center">Library template</h1>

Installation & usage
--------------------
1. Create your library
```bash
$ composer create-project elodgy/library-template my-library
```

2. Modify composer.json to fit with your library

```json
{
  "name": "elodgy/my-library",
  "description": "My library",
  "type": "library",
  "autoload": {
    "psr-4": {
      "Elodgy\\MyLibrary\\": "lib/"
    }
  },
  "autoload-dev": {
    "psr-4": {
      "Elodgy\\MyLibrary\\Tests\\": "tests/"
    }
  }
}
```

3. Initialize git
```bash
$ git init
```

4. Enjoy!!
