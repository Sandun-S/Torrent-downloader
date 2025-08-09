# Happy torrenting! 
🚀This project provides a beginner-friendly Google Colab notebook/script to download torrents and magnet links directly to your Google Drive using the `libtorrent` library.

---

## Features

- Supports both `.torrent` file URLs and magnet links
- Downloads directly to your mounted Google Drive
- Real-time progress bars showing download speed, progress, ETA, and state
- Uses libtorrent for efficient peer discovery (DHT, LSD, UPnP, NAT-PMP)
- Easy to use with minimal setup

---
# How to Open This Notebook

### Option 1: Open Entire Repository in Colab

1. Go to [https://colab.research.google.com/](https://colab.research.google.com/)
2. Select the **GitHub** tab.
3. Paste this repository URL and press Enter:  
   `https://github.com/Sandun-S/Torrent-downloader`
4. Browse and select the **Torrent downloader.ipynb** notebook file to open.

### Option 2: Open This Notebook Directly

Click or paste this link into your browser to open this notebook directly in Colab:  
[https://colab.research.google.com/github/Sandun-S/Torrent-downloader/blob/main/Torrent%20downloader.ipynb](https://colab.research.google.com/github/Sandun-S/Torrent-downloader/blob/main/Torrent%20downloader.ipynb)

---

## How to Use

1. Run the installation cells to install necessary dependencies.
2. Mount your Google Drive when prompted.
3. Input a `.torrent` file URL or magnet link when asked (Similer to **Seedr**).
4. Watch the progress bar for download status.
5. Find your downloaded files in the folder:  
   `/My Drive/Torrent`
6. Optionally unmount Google Drive after download is complete.
---

## Tips

- For more disk space, go to **Runtime -> Change runtime type** and select **GPU**.  
  This provides up to ~xx GB temporary space.
- Google Colab sessions can time out after a few hours; save your data regularly.
- Use `.torrent` URLs, YTS Torrent file download links or magnet links from reliable sources only. Ex: https://yts.mx/torrent/download/A87D36A8EFD2924E9FB607722DE5B453C625884A

---

## Requirements

- Google Colab environment
- Google account for Drive access


---

Enjoy downloading torrents with ease on Google Colab!
