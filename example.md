flowchart TD
    A[Power Line] --> B[GridSentinel Pro: CT Sensor]
    B --> C[ESP32: Signal Processing]
    C --> D[NB-IoT Module: Send Event]
    D --> E[Cloud Server: Logs & Monitoring]
    E --> F[KSEB Dashboard / Alerts]
    A --> G[FenceGuard Mini: Voltage Sense]
    G --> H[Alarm + LED → Farmer Safety]
