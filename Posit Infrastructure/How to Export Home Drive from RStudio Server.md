# Export Contents of Home Directory from RStudio Server

## Background

If you have logged in to [Posit Workbench](https://pwb.publichealthscotland.org/), you may have noticed that your home directory is empty. This is because the contents of your home directory on the old [RStudio Server](https://rstudio.nhsnss.scot.nhs.uk/auth-sign-in) **have not and will not** be transferred across to the new infrastructure. Additionally, once we migrate fully to the new system, your home directory on the current server will no longer be accessible.

Going forward, nothing should be saved in your home directory apart from files explicitly listed as exceptions in the [Posit Workbench Acceptable Use Policy](Acceptable%20Usage%20Policy%20for%20Posit%20Workbench.md). There is very little space allocated to home drives and using these areas for storage will have an impact on both the performance of the system and on storage costs. In addition, the home drive is **not an authorised storage location for data**.

If you do have files stored in your current home directory that you will need in future, you can follow the steps below to export the contents of your home directory.

## Export Steps

1. Log in to the current RStudio server: [https://rstudio.nhsnss.scot.nhs.uk/auth-sign-in](https://rstudio.nhsnss.scot.nhs.uk/auth-sign-in) and open a new session as normal.

2. Click on the 'Files' tab to view your home directory.

![RStudio Server Home Drive files pane](https://user-images.githubusercontent.com/36995878/214892087-b3d9822b-9c4f-47f7-bfa8-e5fc97d5a638.png)

3. To select all files from your home directory, tick the checkbox circled in red in the screenshot below. To select only specific files tick the checkbox(es) next to the file(s) you would like to export. Then click on 'More' as circled in the screenshot below.

![RStudio Server select files](https://user-images.githubusercontent.com/36995878/214898083-9dbc1b2c-c47c-489b-94dc-d4467cc2196a.png)

4. A pop up will appear (see screenshot below) for you to give the zip file to be exported a suitable name, then click 'Download'. The zip file will then be saved to the Downloads folder on your device and you can copy the zip file or extract the content to a more suitable location.

![download_pop_up](https://user-images.githubusercontent.com/36995878/214899786-f2b55fb3-5c66-455d-a1e7-78746f9b4a80.png)

**Note that the exported files should not be uploaded to your home directory on Posit workbench and files should not be saved there going forward. Saving any data (regardless of sensitivity) to your home directory is a violation of the** [Posit Workbench Acceptable Use Policy](Acceptable%20Usage%20Policy%20for%20Posit%20Workbench.md).
