dnn-groupdocs-viewer
====================

GroupDocs Viewer plugin for DotNetNuke


###
Installation
Install DotNetNuke CMS web site (for instance through Microsoft WebMarix) where plugin will be used.
Go to Admin > Extensions feature menu in the admin module. Mouse over "Installed Extensions" and click "Install Extension Wizard". (It should be in Edit mode and mouse over should be on Manage button - should check if it's for all version of DNN). Choose package EmbedViewer_[Version]_Install.zip or EmbedViewer_[Version]_Source.zip in standard open file dialog and click Next. Click Next in opened Package information dialog. Click Next in opened Release Notes dialog. Agree and click Next in opened License dialog.
Create new Page (Go to Pages > Add New Page) or select existing one.
Go to Modules > Add new module, choose EmbedViewer in Module dropdown and click "Add Module" button.
Mouse over Embed Viewer module > Manage button, click Settings. Fill inside EmbedViewer Settings tab three properties (GUID, Frame Width, Frame Height) and click Update button. Embed Viewer plugin will be shown.