# pi-docker-compose

Collection of Docker Compose configs I use on my home Raspberry Pi running Raspbian Buster

These configs assume that an external storage partition is mounted to `/mnt/external` similarly to this:

```bash
sudo mkdir -p /mnt/external
sudo chown $USER /mnt/external
sudo mount /dev/sda2 /mnt/external # Assuming /dev/sda2 is your desired partition
```
