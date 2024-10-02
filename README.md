#  Music Player in Termux

This bash script allows you to play a random `.mp3` or `.mp4` file from a specified folder using the `mpv` media player. If no folder is specified, it defaults to the current working directory.

## Usage

```bash
putar -d FOLDER_NAME

```

- `-d FOLDER_NAME`: Play a music file from the specified folder.
- If no folder is provided, the script will play MP3 file from the current folder.

## Requirements

- **mpv**: The script uses `mpv` media player to play the selected files.
  - Install `mpv` if not already installed:
    ```bash
    pkg install mpv
    ```
#Install
```bash
chmod +x install.sh
bash install.sh
```

## Examples

1. **Play from a specific folder**:
   ```bash
   putar -d /path/to/music_or_videos
   ```

2. **Play from the current folder**:
   Simply run the script without any options:
   ```bash
    putar
   ```

## Notes

- The script supports `.mp3` and `.mp4` file formats.
- Ensure that the folder contains valid music or video files, or the script will notify you that no files were found.
```