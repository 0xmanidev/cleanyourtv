# Realme 32" Theme

Optimized theme for Realme 32 inch Android TV running Android 9 (API 28).

## Features

- **5 columns, 1 row below dock** - Optimized for 32" screen with 1GB RAM
- **Reduced motion** - Enabled for better performance on weaker GPU
- **System stats** - Shows CPU, memory, and storage under clock
- **App library** - Browse all installed apps, add/remove from Home
- **Tile menu** - Hold OK on tile for Move, Remove from Home, App info
- **Bluetooth pill** - Shows Bluetooth status in top bar (requires launcher modification)
- **Pinned apps** - Pin favorite apps to dock (requires launcher modification)
- **Dock as glass band** - Frosted glass dock band for modern look
- **WiFi status color** - Green icon when online, white when offline
- **Auto clock screensaver** - After 10 minutes of inactivity

## Configuration

| Setting | Value | Description |
|---------|-------|-------------|
| Columns | 5 | Tiles per row |
| Rows below dock | 1 | One row of apps visible under dock |
| Reduced motion | true | Calmer animations for 1GB RAM |
| Show stats | true | CPU, RAM, Storage under clock |
| App library | true | Browse all apps |
| Tile menu | true | Hold OK for Move/Remove/App info |
| Dock glass | true | Frosted glass dock band |
| WiFi status color | true | Green when online |
| Cinematic home | false | Disabled for performance |

## Apply Theme

```bash
TV_HOST=<tv ip> tools/theme.sh themes/realme-32
```

## Build and Install Launcher with Theme

```bash
TV_HOST=<tv ip> launcher/build-and-install.sh
```

Then apply theme:
```bash
TV_HOST=<tv ip> tools/theme.sh themes/realme-32
```