Simple Architecture Server Health Script

```
        │
        ├── Check Disk (df -h)
        ├── Check Memory (free -h)
        ├── Check CPU (top)
        ├── Delete Logs (find /var/log)
        ├── Restart Service (systemctl)
        └── Restart Server if Critical
```

