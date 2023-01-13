```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/Shin-kyoto/autoware_deb_test/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/Shin-kyoto_autoware_deb_test.list
echo "yaml https://raw.githubusercontent.com/Shin-kyoto/autoware_deb_test/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-Shin-kyoto_autoware_deb_test.list
```
