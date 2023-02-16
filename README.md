# Xenon's UI Library (Credit: Enxquity)

Creating the library:

library.Create(name, nameUnder)
___________________________________________

Creating a tab:

lib:Tab(name, iconId)
___________________________________________

Creating a button:

tab:Button("name", "description", callback) 
___________________________________________

Creating a toggle:

tab:Toggle("name", "description", starting_state, callback) --// returns state true or false
___________________________________________

Creating a dropdown:

tab:Dropdown("name", list [table], callback) --// returns selected item in dropdown
___________________________________________

Creating a label:

tab:Label(text)
___________________________________________

Creating a slider:

tab:Slider(name, min, max, starting_value, callback) --// returns current value
___________________________________________

Creating a keybind:

tab:Keybind(name, keybind [enum], blacklisted_keys [table] (THESE ARE IN TEXT NO ENUM EG.. {"A", "B"}), callback) --// only returns a value (new key) when there is a new key selected
___________________________________________
Creating a textbox:

tab:TextBox(text, callback) --// returns new text typed in
___________________________________________
Creating a notification:

tab:Notification(text)
___________________________________________

(this documentation looks so shitty because im a noob at github)
