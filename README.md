# s76-scheduler
Tiny GNOME plugin that updates process priorities using the [System76 Scheduler](https://github.com/pop-os/system76-scheduler).

## Installation
### Prerequisites
You must install [System76 Scheduler](https://github.com/pop-os/system76-scheduler) separately.

Ensure that the `com.system76.Scheduler` service is enabled:
```
sudo systemctl enable --now com.system76.Scheduler.service
```

### From source
```bash
git clone https://github.com/ossianwinter/s76-scheduler ~/.local/share/gnome-shell/extensions/s76-scheduler@winter.vg
```
