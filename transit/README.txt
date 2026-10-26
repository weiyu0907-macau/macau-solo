這裡放 macau.json（輕軌路線與車站）。
目前內建的是「車站座標＋車站連線示意」版本（部分車站位置概略）。
在 WSL 執行 python3 tools/make-transit.py 會用 OpenStreetMap 的實際軌道覆蓋這個檔案（需要網路連到 overpass-api.de）。
