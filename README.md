# Prominence II RPG v3.1.6
For optimal performance, allocate 4GB of RAM, and use the following JVM arguments:

```bash
-XX:+UseG1GC -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+OptimizeStringConcat -XX:+UseStringDeduplication -Dfml.ignoreInvalidMinecraftCertificates=true -Dfml.ignorePatchDiscrepancies=true
```
