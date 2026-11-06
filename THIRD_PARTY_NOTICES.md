# Third-party notices

GPU Sentinel calls the installed NVIDIA `nvidia-smi.exe` and Windows device APIs.
It does not redistribute NVIDIA drivers or NVIDIA runtime DLLs.

Design references:

- `hanxiangmin/TaskbarTelemetry` (MIT)
- `LibreHardwareMonitor/LibreHardwareMonitor` (MPL-2.0)
- `jcbritobr/nvml-csharp` (MIT)
- `Wheelem/V100_Monitor`

The current implementation is original and uses `nvidia-smi`, Windows PnP APIs
and Windows event logs as its data sources.

NVIDIA, GeForce, Tesla, Intel, AMD and Windows are trademarks of their
respective owners.
