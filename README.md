# Quasar Bridge v0.7.2 installation packages

Built from https://github.com/Krelion/quasar-bridge/commit/11ce1e460dd5c095eed87366890bc648ce6f12f8.
These archives include the ChatGPT streamed-output fix and fork update URLs.
ARM64 and ARMv7 packages contain embedded PCM payloads. The source archive
includes the corresponding source, vendored dependencies, rebuild instructions,
and license texts. Each archive has a SHA-256 checksum beside it.

Install from a computer (replace SPEAKER_IP and SSH_PORT):

```sh
curl -fL -o /tmp/install-quasar-bridge.sh https://raw.githubusercontent.com/Krelion/quasar-bridge/packages-v0.7.2/install.sh && \
sh /tmp/install-quasar-bridge.sh root@SPEAKER_IP -p SSH_PORT
```

This version-pinned package branch provides downloads while GitHub Actions
release publication is not available. The code and release tag are in main
and v0.7.2; future built-in update checks use Krelion/quasar-bridge releases.
