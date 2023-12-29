# Oliver
***Meet Oliver, your video alchemist. Drop him an M3U8 link, and he'll whip up a lightning-fast concoction, delivering a sleek MP4 straight to your local realm. Oliver's all about that need-for-speed vibe!***

**make sure you have [ffmpeg](https://ffmpeg.org/download.html) installed**

## **install using pip**
```bash
pip install oliver_dl
```
**example usage**
```python
from oliver_dl import Downloader

f = Downloader(m3u8_link)
f.save()
```
## **Run from source**

```bash
git clone https://github.com/TumiPare/oliver
```
**Install poetry**
```bash
pip install poetry
```
**Install dependancies**
```bash
poetry install
```
**Create and run virtual environment**
```bash
poetry shell
```
**run as cli**
```bash
python oliver_dl
```


