### Build .exe (pyinstaller)
`pyinstaller --noconfirm --onefile --windowed --add-data "D:/Electron/Bitbucket/electron-uhf-rc3/.env.production;." --add-data "C:/Windows/System32/libusb0.dll;."  "D:/Electron/Bitbucket/electron-uhf-rc3/main.py"`