1. Download whale.json

2. Open the whale.json and copy the whole "tokenColors" array. (Tip: If you open the file in VS Code, you can collapse the large array first to make copying easier by hovering just to the left of the line number and clicking the little down arrow that appears.)

3. Open your settings.json file inside of VS Code. To get here, hit Ctrl+Shift+P (on Windows) or Command+Shift+P (on Mac) and type in "settings json" - you should select the option that says "Preferences: Open User Settings (JSON)"

4. Add this setting: "editor.tokenColorCustomizations": { textMateRules: [] }

5. Replace the empty 'textMateRules' array with the one you copied.

6. Go back to whale.json copy the "colors" object.

7. Open your settings.json file again, and this time add a setting called "workbench.colorCustomizations" with the value being the object you just copied.

8. Save the changes
