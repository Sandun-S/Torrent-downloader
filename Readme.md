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

## How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Click on **GitHub** tab.
3. Paste this repository URL:  
   `https://github.com/Sandun-S/Torrent-downloader/blob/main/Torrent%20downloader.ipynb`
4. Select the notebook file to open.
5. Make sure you have a Google account to allow Drive access.
6. Run the installation cells to install necessary dependencies.
7. Mount your Google Drive when prompted.
8. Input a `.torrent` file URL or magnet link when asked.
9. Watch the progress bar for download status.
10. Find your downloaded files in the folder:  
   `/My Drive/Torrent`
11. Optionally unmount Google Drive after download is complete.
---

## Tips

- For more disk space, go to **Runtime -> Change runtime type** and select **GPU**.  
  This provides up to ~xx GB temporary space.
- Google Colab sessions can time out after a few hours; save your data regularly.
- Use `.torrent` URLs, YTS Torrent file download links or magnet links from reliable sources only.

---

## Requirements

- Google Colab environment
- Google account for Drive access


---

Enjoy downloading torrents with ease on Google Colab!
