# BlockDistractions-Official

BlockDistractions is a focus tool for macOS (Windows version in progress) that helps you stay productive by blocking distracting apps.  

🎬 **Demo Video:** [Watch on YouTube](https://www.youtube.com/watch?v=ankPLK6IiDs)  

---

## Features

- ✅ Block apps temporarily to focus  
- ⏱️ Timer for focus sessions  
- ⚠️ Website blocking (in progress)  
- 💻 macOS Accessibility permission request  

---

## How to Use (macOS)

1. Download the app (`.app`) or run the Python script.  
2. On first run, the app will ask for **Accessibility permissions**.  
3. Enter apps you want to block (executable names) and set a timer.  
4. Click **Start Focus Session**.  

> ⚠️ Website blocking is not yet fully functional.  

---

## How to Use (Windows) *(Beta, Not Tested Yet)*

1. Download the Python script from the repository.  
2. Make sure Python is installed on your Windows PC.  
3. Open a terminal or IDLE and navigate to the folder containing the script.  
4. Install required dependencies (if any): `pip install tk`  
5. To generate a `.exe` file using PyInstaller, run:  
   `pyinstaller --onefile --windowed --icon=path\to\icon.ico BlockDistractions.py`  
6. Run the generated `.exe` file.  
7. Enter the apps you want to block (executable names) and set a timer.  
8. Click **Start Focus Session**.  

> ⚠️ Windows version is in beta. Website blocking is not yet implemented.  

---

## Contributing

Feel free to submit issues or pull requests. Improvements to website blocking and Windows support are welcome!  

---

## License

MIT License
