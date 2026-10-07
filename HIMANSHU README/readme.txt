cd "C:\Users\himan\OneDrive\Documents\GitHub\CyberdropBunkrDownloader"

py -m pip install -r requirements.txt

py dump.py -u "YOUR_URL"

py dump.py -u "YOUR_URL" -p "D:\Downloads" -e jpg,jpeg,png,webp
py dump.py -u "YOUR_URL" -p "D:\Downloads" -e mp4,mkv,mov,webm
