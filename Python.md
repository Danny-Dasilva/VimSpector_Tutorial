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
pip3 install debugpy
https://dev.to/iggredible/debugging-in-vim-with-vimspector-4n0m

https://github.com/microsoft/debugpy/wiki/Debug-configuration-settings

https://github.com/puremourning/vimspector#human-mode
