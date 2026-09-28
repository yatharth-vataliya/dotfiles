
# Below line turns off all the way to suspend or sleep the server

```bash
sudo systemctl mask sleep.target suspend.target hibernate.target hybrid-sleep.target
```

# Undo below thing

```bash
sudo systemctl unmask sleep.target suspend.target hibernate.target hybrid-sleep.target
```

