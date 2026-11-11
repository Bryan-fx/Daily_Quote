QUOTE OF THE DAY (WINDOWS)

This is a small Python app that shows one offline quote in a window. It picks
the same quote all day and changes it on the next calendar day.

TRY IT
1. Install Python 3 from https://www.python.org/downloads/ if it is not already
   installed. During setup, enable the option to add Python to PATH.
2. Double-click daily_quote.py. If that does not open it, right-click the file,
   choose Open with, and select Python.

START IT WHEN YOU SIGN IN
1. Press Win+R, type shell:startup, and press Enter.
2. In the folder that opens, right-click an empty area and choose New > Shortcut.
3. For the shortcut location, enter the full path to daily_quote.py, for example:
   "C:\Users\YOUR_NAME\Documents\Codex\2026-11-07\hey-orion-i-want-to-make\outputs\daily_quote.py"
4. Name the shortcut Quote of the Day and finish.

If Windows does not launch .py files from a shortcut, use pythonw.exe as the
program and the full path of daily_quote.py as its argument. For example, set
the shortcut location to:
  "C:\Users\YOUR_NAME\AppData\Local\Programs\Python\Python312\pythonw.exe" "C:\Users\YOUR_NAME\Documents\Codex\2026-11-07\hey-orion-i-want-to-make\outputs\daily_quote.py"
The exact Python folder may differ. To find it, open Command Prompt and run:
  where pythonw

To remove it from startup later, open shell:startup and delete the shortcut.
