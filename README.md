# PufferpanelTemplates
Pufferpanel templates used by SkyMist

## Why is this here?
As one of our servers are based on an arm64 architecture, most default Pufferpanel templates did not work. Also, software such as WaterdogPE did not a have pre-made templates, so we decided to make our own.

## Should I use these?
If you want to, go ahead! 

## How to install?
From the sidebar, go to Templates, and click the plus icon to create a new template. Then, click "JSON" from the top right and paste in the relevant JSON from this repository. Make sure to name your template on the field above the JSON editor or the save button won't work! After then, click save and you're all set!

### Note
As some templates were not intended to be released when created, the WaterdogPE template does not have a custom variable for min and max memory. However, if you would like to, feel free to access the `write file` action on the template and change `java -Xms512M -Xmx4G -jar Waterdog.jar` to your liking!
