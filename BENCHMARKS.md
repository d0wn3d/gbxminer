# GBXminer Benchmarks

Benchmark conditions:
- GPU temperature measured under load (>80°C, thermal saturation)
- Hashrate measured after warmup period (120s+)
- Default kernel launch configs unless specified
- Stock GPU clocks (no OC/undervolt unless noted)

---

## GeForce GTX Series

### GTX 1080 Ti
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | 1350 kH/s | 84°C |1900 MHz|

---

## GeForce RTX Series

### RTX 2080 Ti
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |
| X16S | | | |

### RTX 3070
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 3080
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 3090
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 4070
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 4080
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 4090
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 5070
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 5080
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

### RTX 5090
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

---

## Quadro / Tesla

### A100
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | | | |
| X16R | | | |

---

## Submit Your Benchmark

To add your results, edit this file to add a row, then open a Pull Request:

```markdown
| Algorithm | Hashrate | Temp | Notes |
|------------|----------|------|-------|
| NeoScrypt | 1350 kH/s | 84°C | OC 2100 MHz |
```

Include:
- **GPU model** (exact variant if possible)
- **Algorithm** (e.g., neoscrypt, x16r, x11)
- **Hashrate** (use kH/s, MH/s, or H/s consistently)
- **Temperature** under load (after 120+ seconds)
- **Notes** (any OC, undervolt, driver version, etc.)
