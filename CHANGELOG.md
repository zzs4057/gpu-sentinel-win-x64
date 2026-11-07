# Changelog

## 1.1.2 - 2026-11-07

- Reworked each GPU card into separate header, gauge, metric-tile and detail-tile regions.
- Moved driver, mode, PCIe and INF into a 2x2 footer layout.
- Increased metric-tile text bounds so values are no longer clipped.
- Made event-row count responsive to the available panel height.
- Rechecked the UI at 1260x850 and 1000x740.

## 1.1.1 - 2026-11-07

- Shortened event-list messages so long PnP fallback descriptions do not clip.
- Added compact trend-chart labels for NVIDIA, Intel and AMD devices.
- Rechecked the UI at 1260x850 and 1000x740.
- Prevented a horizontal scrollbar when two cards fit in a compact window.

## 1.1.0 - 2026-11-06

- Added automatic discovery of all PCI display adapters.
- Added selectable Intel, NVIDIA, AMD and other GPU monitoring.
- Added dynamic cards, charts and CSV rows for any number of selected devices.
- Added PnP, INF, driver and problem-code fallback for non-NVIDIA GPUs.
- Improved compact-window layout and eliminated overlapping card text.
- Added `--select-devices` startup mode.
- Excluded local device-selection configuration and telemetry from Git.

## 1.0.0 - 2026-11-06

- Initial RTX 5070 + Tesla V100 monitor.
