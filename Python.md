```json
{
    "configurations": {
      "<name>: Launch": {
        "adapter": "debugpy",
        "filetypes": [ "python" ],
        "breakpoints": {
            "exception": {
              "raised": "Y",
              "uncaught": "Y"
            }
          },
        "configuration": {
          "name": "<name>: Launch",
          "type": "python",
          "request": "launch",
          "cwd": "/home/danny/Documents/work/test_debug",
          "python": "/usr/bin/python3",
          "stopOnEntry": true,
          "console": "externalTerminal",
          "debugOptions": [],
          "program": "test.py"
        }
      }
  }
}
```
