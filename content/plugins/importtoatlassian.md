---
title: How Do I Import Mockups to Mockups for Confluence or JIRA?
date: '2015-05-09T14:46:35.000+00:00'
weight: 40
menu:
  menuplugins:
    weight: 40
draft: ''

---

{{% alert info %}}**Note:** Using Mockups 3 for Confluence Cloud? See [this document](https://docs.balsamiq.com/confluence/user-guide-cloud/) instead.{{% /alert %}}

{{% alert info %}}**Note:** Using Mockups 3 for JIRA Cloud? See [this document](https://docs.balsamiq.com/jira/user-guide-cloud/) instead.{{% /alert %}}

In Google Drive, Confluence Server or JIRA Server you can use export/import to import mockups you've created on your site, or those you saved from elsewhere, for instance [Mockups to Go](https://mockupstogo.mybalsamiq.com). Here's how you'd do it.

## Export

### Exporting Mockups from Confluence Server, JIRA Server 

*   Open the mockup and select the menu Mockup > Export Mockup XML.

### Exporting Mockups from Mockups 3 for Desktop or Mockups 3 for Google Drive 

If you are using [Balsamiq Mockups 3](https://docs.balsamiq.com/desktop/intro/) or Mockups 3 for Google Drive:

*   Export to a [BMML Zip file as described here](https://docs.balsamiq.com/desktop/exporting/#exporting-for-use-in-a-previous-version).
*   Use Balsamiq Mockups version 2 or myBalsamiq to open any mockups you want to export and choose File/Project > Export Mockup XML. The contents are copied to your clipboard. You can also open the BMML files with a text editor and copy and paste the text from there.

* * *

If you are using Balsamiq Mockups **version 2**:

*   Export the mockup using the menu File > Export Mockup XML. The contents are copied to your clipboard.

{{% alert info %}}**Note:** Even if you don't have a paid version of the Desktop app, you can still download and use the trial version to open and export mockup files (after 30 days you can no longer save files, but all other features are fully-functional). This can be a convenient way, for example, to get [Mockups to Go](https://mockupstogo.mybalsamiq.com) libraries into your plugin version.{{% /alert %}}

### Exporting Mockups from myBalsamiq 

*   Export the mockup from the menu Project > Export Mockup XML. The contents are copied to your clipboard.

{{% alert info %}}**Note:** If you don't use the Desktop app or myBalsamiq you can open a BMML file in a text editor (like Notepad or or TextEdit) and copy its contents to your clipboard.{{% /alert %}}

* * *

## Import

### For Confluence Server or JIRA Server

*   Export the Mockup XML from the product you are exporting from (see instructions above)
*   Create a new mockup in your Mockups plugin.
*   When the editor is loaded, use the menu Mockups > Import Mockup XML...
*   Paste the mockup data in the text area and click Import.

{{% alert info %}}**Note:** To see a demonstration of this process in Confluence Server see our tutorial on [Creating a Mockups Design Library in Confluence](/tutorials/confluencesymbollibrary/).{{% /alert %}}

### For Google Drive 

*   Follow the steps above or see [these instructions on importing to Mockups 3 for Google Drive](https://docs.balsamiq.com/google-drive/user-guide/#importing-from-other-versions-of-balsamiq-mockups).

* * *

## More Import/Export Options

If you use Google Drive, Confluence Server or JIRA Server but don't have a license for one of our Mockups plugins, you can still share your mockups using these products. To do this, upload your mockups as images (go to "File > Export to PNG image" in the Desktop version) and attach or embed the images. You can also upload your Mockups (.bmml) files for other Desktop users to download to their computers.

If you're looking for import/export options for other applications or file formats, a good number of extensions have been written so far. You can find the list of [import/export extensions here](/resources/extensions/).

