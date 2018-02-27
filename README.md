ArchivesSpace PUI Help Page Plugin
======================================

**Special thanks to Randy Kuehn from University of Louisville for writing and sharing this plugin~**

This is a plugin that add's a Help page to the ArchivesSpace PUI. 


Enable the plugin
-----------------

Edit `config.rb` and append:

```
AppConfig[:plugins] << "archivesspace_pui_help"
```
Edit the views/help/index.html.erb file as desired to populate your Help page.

Restart ArchivesSpace.

---