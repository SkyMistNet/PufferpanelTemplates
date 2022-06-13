# PufferpanelTemplates
Pufferpanel templates used by SkyMist

## Why is this here?
As one of our servers are based on an arm64 architecture, most default Pufferpanel templates did not work. Also, software such as WaterdogPE did not a have pre-made templates, so we decided to make our own.

## Should I use these?
If you want to, go ahead! 

## Note
As the templates were not intended to be released when created, the WaterdogPE template does not have a custom variable for min and max memory. However, if you would like to, feel free to access the `write file` action on the template and change `java -Xms512M -Xmx4G -jar Waterdog.jar` to your liking!
