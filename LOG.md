# Learning Log

## 2026-11-20 – Phase 0: Tower setup

**Done**
- Ubuntu 26.04 LTS installed as dual boot next to Windows (~150 GB)
- Boot order fixed (MSI board kept starting Windows; set ubuntu first in BIOS)
- Remote access: Tailscale + SSH key (`ssh tower`), VS Code Remote-SSH
- Python 3.12 env (uv), JAX on GPU (CUDA 13, driver 595) -> `CudaDevice(id=0)`
- MuJoCo 4.0.1 installed, Go2 model runs
- Remote desktop: GNOME Remote Login via FreeRDP (`tower-desktop`)

**Problems & fixes**
- Windows could only shrink C: by 3.7 GB (unmovable files) -> let Ubuntu installer resize
- `apt` lock error -> forgot `sudo`
- SSH asked for "password" -> was the key passphrase -> saved in macOS keychain
- Microsoft Windows App: black screen (fails at RDP server redirection) -> FreeRDP works

**Next**
- Repo structure + Git refresher
- Pendulum simulation in Python (Euler vs. RK4)
- Order moteus-c1 dev kit
