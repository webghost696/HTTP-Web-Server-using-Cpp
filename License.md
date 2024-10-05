
#### TROUBLESHOOTING.md:
```markdown
# Troubleshooting Guide

## Common Issues and Fixes

### 1. WSAStartup Failed
Ensure that `WSAStartup()` is successfully initialized. If it fails, the output will show the error code.

### 2. Port 8080 Already in Use
If port 8080 is blocked or in use, change the port in the code:
```cpp
#define PORT 8081
