{
    "version": "2.0.0",
    "tasks": [
        {
            "label": "build",
            "type": "shell",
            "command": "make build COSMOS_BUILD_OPTIONS=nostrip",
            "presentation": {
                "close": true
            }
        }
    ]
}
