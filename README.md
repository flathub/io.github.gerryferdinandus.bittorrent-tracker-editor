# bittorrent-tracker-editor Flatpak

## Installation

To install, simply click the `Get it on Flathub` button and follow the instructions.

<a href='https://flathub.org/apps/io.github.gerryferdinandus.bittorrent-tracker-editor'>
<img width='240' alt='Get it on Flathub' src='https://flathub.org/api/badge?locale=en'/></a>

## Build Locally

1. Clone the site:
   ```shell
   git clone https://github.com/flathub/io.github.gerryferdinandus.bittorrent-tracker-editor.git
   cd io.github.gerryferdinandus.bittorrent-tracker-editor
   ```

2. Add flathub repository to current user:
   ```shell
   flatpak remote-add \
     --if-not-exists \
     --user \
     flathub https://dl.flathub.org/repo/flathub.flatpakrepo
   ```

3. Build and install:
   ```shell
    flatpak-builder \
    --force-clean \
    --user \
    --install-deps-from=flathub \
    --repo=repo \
    --install builddir io.github.gerryferdinandus.bittorrent-tracker-editor.yml
   ```

4. Run the application:
   ```shell
   flatpak run io.github.gerryferdinandus.bittorrent-tracker-editor
   ```
5. Uninstall it:
   ```shell
   flatpak uninstall io.github.gerryferdinandus.bittorrent-tracker-editor
   ```
   