# ⚠️ IMPORTANT ⚠️
I originally created this project for my Trimui Smart Pro and for other users of the device. However, this tool can be used on any compatible device, so feel free to use it as you like! 🚀

# 🎵 Trimui MP3ToMP4 Converter 🎥

Convert your MP3 files into MP4 videos with album covers as static images! Perfect for uploading music with visuals to platforms like YouTube. 🚀

## ✨ Features
- 🖼️ Extracts album cover from MP3 files and adds it as a static video.
- 🎵 Supports batch conversion from `songs` folder.
- ⏳ Displays real-time progress while converting.
- 💨 Uses `ffmpeg` for fast and efficient encoding.

## 📥 Installation

### 1️⃣ Prerequisites
Ensure you have the following installed:
- Python 3.8+
- `ffmpeg` (Install via package manager or from [ffmpeg.org](https://ffmpeg.org/))
- Required Python packages:
  ```sh
  pip install mutagen pillow
  ```

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/Trimui-MP3ToMP4.git
cd Trimui-MP3ToMP4
```

## 🚀 Usage

1. Place your `.mp3` files inside the `songs` folder.
2. Run the script:
   ```sh
   python main.py
   ```
3. Select an option from the menu:
   - `1` ➜ Start Conversion
   - `2` ➜ Info about the program
   - `3` ➜ Exit

4. Converted `.mp4` files will be saved in the `out` folder.

## 🖥️ Compatibility
### ✅ Operating System Support
| Windows Version | Supported |
|---------------|------------|
| Windows 7     | ✅         |
| Windows 8     | ✅         |
| Windows 10    | ✅         |
| Windows 11    | ✅         |
| Linux        | ✅         |
| macOS        | ✅         |

### 📂 File Format Support
| Input Format | Supported |
|-------------|------------|
| MP3         | ✅         |
| WAV         | ❌         |
| FLAC        | ❌         |
| AAC         | ❌         |
| OGG         | ❌         |

| Output Format | Supported |
|--------------|------------|
| MP4         | ✅         |
| AVI         | ❌         |
| MKV         | ❌         |
| MOV         | ❌         |

## 📜 License
This project is open-source under the MIT License.

## ❤️ Contributing
Feel free to fork and submit a PR if you have any improvements! 🚀

