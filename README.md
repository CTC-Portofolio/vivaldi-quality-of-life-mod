# Vivaldi Mod Template

A template for custom UI mods for the Vivaldi Browser

DISCLAIMER: This template is not developed or approved by Vivaldi

# How to install?

After creating a new repository from this mod, you can install your changes by following the steps below:

- Go in vivaldi://experiments and check Allow for using CSS modifications (You need to do this only once)
- Open Vivaldi Settings > Apperance and in "Custom UI Modifications", select the Mod folder
- Restart Vivaldi (you can easily do this by going in vivaldi://restart)

# How to inspect the UI

Vivaldi runs inside a react shell. To inspect the css classes and the markup, follow the steps below:

- Open vivaldi://inspect/#apps
- There should be listed every Vivaldi window you have open, with its tabs, in a "tree style" view.
- Look for the window you want to use as test subject (Vivaldi windows are named Vivaldi with its url being chrome-extension://<something>/browser.html).
- Hit Inspect under "Vivaldi"
- This will open the Dev tools, inspecting the UI


