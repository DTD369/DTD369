I'm a passionate software engineer, OS engineer, and cybersecurity researcher. I code in C, C++ and Assembly.

```
#include <ntddk.h>
#include <wdf.h>

DRIVER_INITIALIZE DriverEntry;

NTSTATUS DriverEntry(PDRIVER_OBJECT DriverObject, PUNICODE_STRING RegistryPath)
{
    UNREFERENCED_PARAMETER(DriverObject);
    UNREFERENCED_PARAMETER(RegistryPath);

    DbgPrint("Hello World!\n");
    return STATUS_SUCCESS;
}
```

> Any fool can write code that a computer can understand. Good programmers write code that humans can understand. ― Martin Fowler
