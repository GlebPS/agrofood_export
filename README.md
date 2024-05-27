Для сборки приложения
1)
pyinstaller --onefile --hidden-import=sklearn --hidden-import=sklearn.pipeline  --windowed main.py
2)
Скопировать папки models, trad_map и файл trade_map.db в папку с .exe

