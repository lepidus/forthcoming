
# Forthcoming publications plugin for OJS/OMP 3.4

This is a complete rewrite of the old Forthcoming plugin, which changes the entire concept of the plugin and utilizes the versioning features of OJS 3.2+. The new version supports statistics and uses DOIs. Forthcoming publications also have their own landing pages with the same URL structure as the final article or monograph.

## Usage

### Settings
1. Create a new issue(or series if using OMP) and name it for example "Forthcoming" and *publish it*
2. Enable the Forthcoming plugin from Website Settings
3. In the plugin settings, choose the Forthcoming issue or series from the pull down menu and save settings
4. Go to Navigation menu settings and add the Forthcoming listing page to your menu. If you want a different name, you can just create a new custom url menu item and point it to the Forthcoming listing page.

The plugin will hide the Forthcoming publication from the regular archive and redirect all traffic from the table of contents page to the custom Forthcoming listing page.

### Workflow
1. When you want to add a new publication to Forthcoming listing, just choose the Forthcoming issue/series from the submission metadata settings and publish it. The publication is now visible in Forthcoming page.
2. When the actual issue/series is being published, *create a new version* for the publication, change the issue/series and publish the new version. The publication is no longer visible in the Forthcoming page.

Note. I recommend that you do not use the OJS default pattern for DOIs with this plugin.


***
Plugin created by The Federation of Finnish Learned Societies (https://tsv.fi/en/).
***
