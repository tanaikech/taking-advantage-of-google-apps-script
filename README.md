# Taking Advantage of Google Apps Script (Tanaike's list)

<a name="top"></a>
Here, CLI tools, libraries, Add-ons, Reports, Benchmarks and Sample Scripts for taking advantage of Google Apps Script which are publishing in my [blog](https://tanaikech.github.io/), [Gists](https://gist.github.com/tanaikech) and [GitHub](https://github.com/tanaikech) are summarized. If these are useful for you, I'm glad.

<br>

# Index

- [News](#news)
- [Trend of Google Apps Script](#trend)
- [Settings](#settings)
- [CLI tools for GAS](#clitool)
- [Web Applications](#webapps)
- [GAS libraries](#gaslibraries)
- [GAS library database](#gaslibrarydatabase)
- [Go libraries](#golibraries)
- [Node.js modules](#nodemodules)
- [Python library](#pythonlibrary)
- [Javascript library](#javascriptlibrary)
- [Add-ons](#addons)
- [Reports](#reports)
- [Benchmarks](#benchmarks)
- [Communities](#communities)
- [Sample Scripts](#samplescripts)
  - [Files in Google Drive](#filesingoogledrive)
  - [Projects](#projects)
  - [Spreadsheets](#spreadsheets)
  - [Documents](#documents)
  - [Slides](#slides)
  - [Gmail](#gmail)
  - [Calendar](#calendar)
  - [Chart](#chart)
  - [Analytics](#analytics)
  - [Slack](#slack)
  - [Virtual Currency](#virtualcurrency)
  - [Stackoverflow](#stackoverflow)
  - [Netatmo](#netatmo)
  - [Figma](#figma)
  - [Etc](#etc)
  - [Node.js](#nodejs)
  - [Golang](#golang)
  - [Python](#python)
  - [Curl](#curl)
  - [Javascript](#javascript)
  - [PHP](#php)

<br>
<br>

<a name="news"></a>

# News

- **April 6, 2021:** [A Bug of New IDE about Time Zone of Google Apps Script project was removed](https://tanaikech.github.io/2021/04/06/a-bug-of-new-ide-about-time-zone-of-google-apps-script-project-was-removed/)
- **December 15, 2020:** [Meet the Google Workspace Developer Experts](https://tanaikech.github.io/2020/12/15/meet-the-google-workspace-developer-experts/)
- **December 8, 2020:** [New IDE for Google Apps Script has been finally released](https://tanaikech.github.io/2020/12/08/new-ide-for-google-apps-script-has-been-finally-released/)
- **July 30, 2020:** [Drive API got to be able to create Google Apps Script project again](https://gist.github.com/tanaikech/36821c7d70f9ce376d043c3d682d404e)
- **July 10, 2020:** [Transfer of owner of files got to be able to be achieved with batch requests of Drive API](https://tanaikech.github.io/2020/07/10/transfer-of-owner-of-files-got-to-be-able-to-be-achieved-with-batch-requests-of-drive-api/)
- **July 9, 2020:** [Specification of Files: copy in Drive API was changed](https://tanaikech.github.io/2020/07/09/specification-of-files-copy-in-drive-api-was-changed/)
- **July 7, 2020:** [Transfer of owner of files got not to be able to be used with batch requests of Drive API](https://tanaikech.github.io/2020/07/07/transfer-of-owner-of-files-got-not-to-be-able-to-be-used-with-batch-requests-of-drive-api/)
- **June 15, 2020:** [Transfer of owner of files got to be able to be achieved with batch requests of Drive API](https://tanaikech.github.io/2020/06/15/transfer-of-owner-of-files-got-to-be-able-to-be-achieved-with-batch-requests-of-drive-api/)
- **June 4, 2020:** [Managing Shared Drive using Drive Service of Google Apps Script](https://gist.github.com/tanaikech/ede1c9ea6eb6a27235df7d4cb16ef48d)
- **March 11, 2020:** [Drive API cannot create Google Apps Script project no longer](https://gist.github.com/tanaikech/0609f2cd989c28d6bd49d211b70b453d)
- **February 7, 2020:** [V8 Runtime was added to Google Apps Script at February 7, 2020](https://gist.github.com/tanaikech/8246f89540957b177f0e350f453ea2fb)
- **April 8, 2019:** [Specification of Google Apps Script Project was Changed at April 8, 2019](https://gist.github.com/tanaikech/558a5b6da0d9533017b1abe5815989c3)

<br>

<a name="trend"></a>

# Trend of Google Apps Script

> At Stackoverflow, a lot of people post the questions and answers to the questions every day. There are various tags in Stackoverflow. A lot of discussions are performed at each tag. Their discussions bring the important information and are much useful for a lot of people. As one of tags, there is "google-apps-script". I sometimes discuss at the questions with that tag. When we see the discussions, we can notice that the discussions are changed and progressed by the time, because "Google Apps Script" which is the origin of the tag is updated. This report thinks this change as the trend of tag of "google-apps-script". This trend includes the number of questions, questioners, answerers and tags adding to the tag of "google-apps-script". The trend of tag of "google-apps-script" is deeply related to the progression of Google Apps Script and the various applications for Google Apps Script. In this report, as one of several approaches, the trend of Google Apps Script was investigated by statistically analyzing all questions with the tag of "google-apps-script". As the result, it was found that by investigating all questions with the tag of "google-apps-script", the tags added to this main tag strongly affected to the trend of the tag of "google-apps-script". Also the possibility which can estimate the future trend by investigating the tags adding to the tag of "google-apps-script" was indicated.

- [Trend of google-apps-script Tag on Stackoverflow 2019](https://gist.github.com/tanaikech/4e4f1ca20b8dbce08f87289db415df7d)

- [Trend of google-apps-script Tag on Stackoverflow 2020](https://gist.github.com/tanaikech/fd7dbc6d630fd0550c32159635cecc96)

- [Trend of google-apps-script Tag on Stackoverflow 2021](https://gist.github.com/tanaikech/18519c3177e284638dce9113ec7ab5b1)

<br>

<a name="settings"></a>

# Settings

- [Linking Cloud Platform Project to Google Apps Script Project](https://gist.github.com/tanaikech/e945c10917fac34a9d5d58cad768832c): At April 8, 2019, the specification of Google Apps Script Project was changed. In this report, the flow for linking Cloud Platform Project to GAS project is explained.

- [Linking Google Cloud Platform Project to Google Apps Script Project for New IDE](https://github.com/tanaikech/Linking-Google-Cloud-Platform-Project-to-Google-Apps-Script-Project-for-New-IDE): This is the document for linking Google Cloud Platform Project to Google Apps Script Project for New IDE. And also, several sample scripts using Google Apps Script API and Google Photos API are introduced.

- [Redeploying Web Apps without Changing URL of Web Apps for new IDE](https://gist.github.com/tanaikech/ebf92d8f427d02d53989d6c3464a9c43): At March 15, 2021, one endpoint is created for one deployment. [Ref](https://developers.google.com/apps-script/releases/#march_15_2021) By this, when you redeploy "Web Apps", the endpoint is changed. Because the deployment ID is changed. It seems that this it the new specification. In this report, I would like to introduce the method for redeploying Web Apps without changing the URL of Web Apps for new IDE.

<br>

<a name="clitool"></a>

# CLI tools for GAS

- [ggsrun](https://github.com/tanaikech/ggsrun) : Execute Google Apps Script (GAS) at own terminal on local PC.
- [gislack](https://github.com/tanaikech/gislack) : Submit files to both Gist and Slack.
- [goris](https://github.com/tanaikech/goris) : Search for images with Google Reverse Image Search (goris).
- [gogauth](https://github.com/tanaikech/gogauth) : Easily retrieve access token for using APIs on Google.
- [gorearrange](https://github.com/tanaikech/gorearrange) : Interactively rearrange a text data on a terminal.
- [goodls](https://github.com/tanaikech/goodls) : Download shared files from Google Drive.

<br>

<a name="webapps"></a>

# Web Applications

- [Search Google Apps Script Libraries](https://sites.google.com/view/search-gas-libraries) : This is an application for searching Google Apps Script libraries from [the database](https://github.com/tanaikech/Google-Apps-Script-Library-Database).
- [Fields Builder For Google APIs](https://sites.google.com/view/fields-builder) : FieldsBuilderForGoogleAPIs is a Web Application for building the fields value for using Google APIs. This is mainly used for developing the scripts for using Google APIs. [GitHub](https://github.com/tanaikech/FieldsBuilderForGoogleAPIs)

<br>

<a name="gaslibraries"></a>

# GAS libraries

You can search the GAS libraries at [Search Google Apps Script Libraries](https://sites.google.com/view/search-gas-libraries)

- [BatchRequest](https://github.com/tanaikech/BatchRequest) : This is a library for running Batch Requests using Google Apps Script (GAS).
- [ConvertNFDtoNFC](https://github.com/tanaikech/ConvertNFDtoNFC) : This is a script for converting strings from NFD (Normalization Form Decomposition) to NFC (Normalization Form Composition) using Google Apps Script.
- [FilesApp](https://github.com/tanaikech/FilesApp) : FilesApp is a GAS library for retrieving file and folder list in Google Drive using Google Apps Script (GAS). Also this can create a tree from all files and folders in Google Drive.
- [ImgApp](https://github.com/tanaikech/ImgApp) : This is a library of image tools for Google Apps Script.
- [ManifestsApp](https://github.com/tanaikech/ManifestsApp) : This is a Manifests library for Google Apps Scripts.
- [ProjectApp](https://github.com/tanaikech/ProjectApp) : This is a project library for Google Apps Script (GAS).
- [ProjectApp2](https://github.com/tanaikech/ProjectApp2) : This is a GAS project library for Google Apps Script (GAS). This library can be used for the projects of both standalone script type and container-bound script type.
- [OnedriveApp](https://github.com/tanaikech/OnedriveApp) : This is a library of Google Apps Script for using Microsoft OneDrive.
- [Resumable_Upload_For_WebApps](https://github.com/tanaikech/Resumable_Upload_For_WebApps) : This is a sample script for uploading files with large size (> 50 MB) at Web Apps using Google Apps Script (GAS). The resumable upload method is used for uploading files. This script can be also applied to the script using gapi of javascript.
- [RunAll](https://github.com/tanaikech/RunAll) : This is a library for running the concurrent processing using only native Google Apps Script (GAS).
- [SOUWA_GAS](https://github.com/tanaikech/SOUWA_GAS) : GAS library for summing string elements in an array at the high speed
- [ZipFolder](https://github.com/tanaikech/ZipFolder) : This is a library for zipping a folder using Google Apps Scripts.
- [RangeListApp](https://github.com/tanaikech/RangeListApp) : RangeListApp is a GAS library for retrieving, putting and replacing values for Spreadsheet by a range list with a1Notation using Google Apps Script (GAS).
- [DownloadLargeFilesByUrl](https://github.com/tanaikech/DownloadLargeFilesByUrl) : DownloadLargeFilesByUrl is a GAS library for downloading large files from URL to Google Drive using Google Apps Script (GAS).
- [ArrangeStackingOrder](https://github.com/tanaikech/ArrangeStackingOrder) : ArrangeStackingOrder is a GAS library for arranging the stacking order of page elements on Google Slides using Google Apps Script (GAS).
- [ProcessApp](https://github.com/tanaikech/ProcessApp) : This is a library for retrieving the process and information of Google Apps Script. For example, one of methods retrieves the total execution time of all functions executed by the time-driven trigger at owner's account.
- [GistChecker](https://github.com/tanaikech/GistChecker) : This is a GAS library for notifying the change of number of comments, stars and forks of own Gists as an email using Google Apps Script.
- [FetchApp](https://github.com/tanaikech/FetchApp) : This is a GAS library for creating and requesting the type of multipart/form-data using Google Apps Script. This library enhances Class UelFetchApp of Google Apps Script.
- [GetEditType](https://github.com/tanaikech/GetEditType) : GetEditType is a GAS library for retrieving the edit types of the OnEdit event trigger of Spreadsheet using Google Apps Script (GAS).
- [UnzipGs](https://github.com/tanaikech/UnzipGs) : This is a GAS library for unzipping a Zip file protected by a password using Google Apps Script.
- [GmailToList](https://github.com/tanaikech/GmailToList) : This is a library for exporting all messages of Gmail as a list using Google Apps Script (GAS).
- [EncodeApp](https://github.com/tanaikech/EncodeApp) : EncodeApp is a GAS library for retrieving the encoding set (charset) and doing URL encode with the specific encoding set using Google Apps Script (GAS).
- [DateFinder](https://github.com/tanaikech/DateFinder) : DateFinder is a GAS library for searching the date objects from the cell range on the sheet in the Spreadsheet and retrieving the searched range as the RangeList object using Google Apps Script (GAS).
- [RichTextApp](https://github.com/tanaikech/RichTextApp) : This is a GAS library for copying the rich text with the text styles from Google Document to Google Spreadsheet or from Google Spreadsheet to Google Document using Google Apps Script (GAS). And, also the rich texts in the cells can be converted to HTML format.
- [GPhotoApp](https://github.com/tanaikech/GPhotoApp) : This is a GAS library for retrieving and creating the albums and media items using Google Photo API using Google Apps Script (GAS).
- [CopyFolder](https://github.com/tanaikech/CopyFolder) : This is Google Apps Script library for copying folder on Google Drive.
- [OwnershipTransfer](https://github.com/tanaikech/OwnershipTransfer) : This is a Google Apps Script library for achieving the ownership-transfer of the specific folder including the files and sub-folders using Drive API.
- [GASProjectApp](https://github.com/tanaikech/GASProjectApp) : This is a Google Apps Script library for creating, updating and exporting Google Apps Script project of the standalone type using Drive API. In this case, Apps Script API is not used.
- [DocsServiceApp](https://github.com/tanaikech/DocsServiceApp) : This is a Google Apps Script library for supporting Document service, Docs API, Spreadsheet service, Sheets API, Slides service and Slides API. The aim of this library is to compensate the processes that they services cannot achieve.

<br>

<a name="gaslibrarydatabase"></a>

# GAS library database

- [Google Apps Script Library Database](https://github.com/tanaikech/Google-Apps-Script-Library-Database) : This is for the Google Apps Script Library Database.

<br>

<a name="golibraries"></a>

# Go libraries

- [go-getfilelist](https://github.com/tanaikech/go-getfilelist) : This is a Golang library to retrieve the file list with the folder tree from the specific folder of Google Drive.
- [go-gettokenbyserviceaccount](https://github.com/tanaikech/go-gettokenbyserviceaccount) : This is a Golang library to retrieve access token from Service Account of Google without using Google's OAuth2 package.
- [go-gdoctableapp](https://github.com/tanaikech/go-gdoctableapp) : This is a Golang library for managing tables on Google Document using Google Docs API.

<br>

<a name="nodemodules"></a>
Node.js modules
=====

- [node-getfilelist](https://github.com/tanaikech/node-getfilelist) : This is a Node.js module to retrieve the file list with the folder tree from the specific folder of Google Drive.
- [node-gdoctableapp](https://github.com/tanaikech/node-gdoctableapp) : This is a Node.js module to manage the tables on Google Document using Google Docs API.

<br>

<a name="pythonlibrary"></a>
Python library
=====

- [getfilelistpy](https://github.com/tanaikech/getfilelistpy) : This is a python library to retrieve the file list with the folder tree from the specific folder of Google Drive.
- [gdoctableapppy](https://github.com/tanaikech/gdoctableapppy) : This is a python library to manage the tables on Google Document using Google Docs API.

<br>

<a name="javascriptlibrary"></a>
Javascript library
=====

- [GetFileList_js](https://github.com/tanaikech/GetFileList_js) : This is a Javascript library to retrieve the file list with the folder tree from the specific folder (publicly shared folders and own folders) of Google Drive.
- [syncGoogleScriptRun](https://github.com/tanaikech/syncGoogleScriptRun) : This is a Javascript library to use "google.script.run" with the synchronous process.
- [ResumableUploadForGoogleDrive_js](https://github.com/tanaikech/ResumableUploadForGoogleDrive_js) : This is a Javascript library to achieve the resumable upload for Google Drive.
- [BatchRequest_js](https://github.com/tanaikech/BatchRequest_js) : This is a library for running Batch Requests for Google APIs using Javascript.
- [HtmlFormObjectParserForGoogleAppsScript_js](https://github.com/tanaikech/HtmlFormObjectParserForGoogleAppsScript_js) : This is a Javascript library for sending the HTML form object to Google Apps Script using `google.script.run`.

<br>

<a name="addons"></a>

# Add-ons

- [RearrangeScript](https://chrome.google.com/webstore/detail/rearrangescripts/ndaicidjkbcpajgejcclgfdcncpoekml) : Rearranging Google Apps Scripts (GAS) in a project which can be seen at the script editor. [GitHub](https://github.com/tanaikech/RearrangeScripts)
- [ShapeApp](https://chrome.google.com/webstore/detail/shapeapp/nmbimbgfafgmkhioolneofjchigbpkhf) : Manipulating shapes on Google Slide. It can create and update shapes by inputting parameters, and can arrange shapes. This is made of Google Apps Scripts (GAS). [GitHub](https://github.com/tanaikech/ShapeApp)

<br>

<a name="reports"></a>

# Reports

### [Improved Algorithms for Summation of Array](https://tanaikech.github.io/2016/10/13/improved-algorithms-for-summation-of-array-elements/)

> I considered an efficient algorithm for summation of array elements. All elements in an array are string. When those elements are summed using scripts, a standard method is to add each element in order. If the script is run without any optimize, the process becomes gradually sluggish, because the total amount of active data during the summation process is proportional to the square of the number of array elements. This leads directly to the high process-cost. Such phenomenon notably appears at Google Apps Script (GAS). This report says about the solution of this problem using a new algorithm of a pyramid method. The pyramid method achieves that the total amount of active data increases proportional to the linear of the number of array elements. By this, the processing time becomes much shorter than that of the process using the standard method. The pyramid method achieved the process-cost reduction of 99.7% compared with the standard method at GAS. I realized again that new discoveries are hidden into the familiar scenes of every-day life.

### [Taking Advantage of Manifests by GAS Library](https://gist.github.com/tanaikech/23ddf599a4155b66f1029978bba8153b)

> By recent Google update (Google update at October 24, 2017), various new winds to GAS developers were blown. There is "Manifests" as one of the new winds. "Manifests" makes us manage the project using JSON. Especially, the special scopes which have to use OAuth2 process can be used by only setting them to the Manifests. I think that this is the largest modification. However, when scopes are added to a project using Manifests, users who use the project can use only added scopes. This means that when users create scripts in the project, if there are some scopes which is required to be added, such scopes cannot be automatically added. So the error of "Insufficient Permission" occurs. In this report, I would like to introduce the workaround for avoiding this problem.

### [Difference Between Given Values and Retrieved Values for Shapes on Google Slides](https://gist.github.com/tanaikech/953e630855e65de55d8e5bd448ad764f)

> This is a document for explaining the difference between given values and retrieved values for shapes on Google Slides.

### [Taking advantage of Web Apps with Google Apps Script](https://github.com/tanaikech/taking-advantage-of-Web-Apps-with-google-apps-script)

> There is Web Apps as one of applications using Google Apps Script (GAS). I sometimes use this Web Apps. But I have only a little the information for the specification of Web Apps. So in order to take more advantage of Web Apps, I investigated and summarized about this. The aim of this report is to become one of the basic information for creating various applications using Web Apps with GAS.

### [Limitation of Images for Inserting to Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/825f1ebfe7822780316d7c15f89dea11)

> Here I would like to introduce about the limitation of images for inserting to Spreadsheet using Google Apps Script (GAS). When you want to insert the images to Spreadsheet using GAS, insertImage() of class Sheet is usually used for this situation. At this time, an error sometimes occurs. This indicates that there is the limitation for inserting images to Spreadsheet. So I investigated the limitation. As a result, it was found that the limitation depends on the image area (pixels^2) rather than the file size of it. The maximum area of image which can be inserted was 1,048,576 pixels^2.

### [Asynchronous Processing using Event Triggers](https://gist.github.com/tanaikech/88f7fd5ed14da5e9afde18310da61cb5)

> This is a report about the possibility of asynchronous process using event triggers. `onEdit()` which is a simple trigger is often used as a trigger when the values are modified on Spreadsheet. When users want to use the script including some methods which are required to be authorized as the onEdit event, a installable trigger of onEdit is used. If the trigger is installed for the function of `onEdit()`, when the event trigger is run, `onEdit()` is run 2 times. In order to avoid this, the installable trigger is installed to the functions except for the functions of simple triggers. The functions of simple triggers which is the same events are not used in the project. When I thought about this situation, I thought that both `onEdit()` which is run by the simple trigger and the function which is run by the installable trigger might be able to be used, simultaneously. So I investigated about this situation. As the result, it was found that the following simple triggers and installable triggers work as the asynchronous process.

### [Limitation of Array.prototype.push.apply under V8 for Google Apps Script](https://gist.github.com/tanaikech/3e3c16b58f6b30de366eba99de84c861)

> When V8 is enabled, `Array.apply` has the limitation for the number of elements. When it is over the limitation, an error like `RangeError: Maximum call stack size exceeded` occurs, while the issue didn't occur when V8 is disabled. In this case, this issue occurs at both Google Apps Script and Javascript. So please be careful this.

### [When // in template literal is used in a HTML file in script editor, it is used as a comment start](https://gist.github.com/tanaikech/5a6b92f9fcce4046ae4c3c79c28fe958)

> When `//` in template literal is used in a HTML file in script editor, it is used as a comment start.

### [Characteristics of Response for onSelectionChange](https://gist.github.com/tanaikech/ca5812ed19dd6858879246bd2304266f)

> I have already reported about "Change Tab Detection on Google Spreadsheet using onSelectionChange Event Trigger with Google Apps Script". [Ref](https://tanaikech.github.io/2020/05/18/change-tab-detection-on-google-spreadsheet-using-onselectionchange-event-trigger-with-google-apps-script/) It is considered that when the situation which uses the event trigger of `onSelectionChange` is thought, the response speed is important. So, here, I investigated the characteristics of response for the event trigger of `onSelectionChange`.

### [Detecting Quickly Checked Checkboxes on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/7b1a18a5b768e4d69d519069f4aff440)

> This is a report for detecting quickly checked checkboxes on Google Spreadsheet using Google Apps Script. It supposes that when the checkbox is checked, a function of Google Apps Script is run by the event trigger. In this case, when the multiple checkboxes on Google Spreadsheet are checked quickly, the script cannot be run for all checked checkboxes, because of the response speed of the event trigger. It is considered that to understand the response of event trigger is useful for creating the application for Spreadsheet. In this report, the detection of quickly checked checkboxes on Google Spreadsheet using Google Apps Script has been investigated. From this result, it led to understanding the response of event trigger.

### [Report: Processing to Create New File to Specific Folder using Drive API](https://gist.github.com/tanaikech/d034e38169503c2c22eb0c3352ae30b6)

> In this report, I would like to report for processing to create new file to the specific folder using Drive API. When the new file is created to the specific folder using Drive API, the property of `parents` with the value of folder ID is included in the request body of the method "Files: create". About this process, I had thought that the file is directly created to the specific folder. But, I could confirm that the new file is created by the following process.
>
> 1. Create new file to the root folder.
> 2. Move the created file to the specific folder.
>
> These process is done by one API call. In this report, I would like to introduce the experimental result for confirming above process. In this case, Drive API v3 is used with Google Apps Script.

### [Statistical Analysis of Duplicated Questions for `google-apps-script` tag in Stackoverflow](https://gist.github.com/tanaikech/fa8e7002678a377748ae35a33fa5b6eb)

> At Stackoverflow, a lot of people post the questions and answer to the questions every day. By this, there are a lot of important information in Stackoverflow. I have already reported "Trend of google-apps-script Tag on Stackoverflow" using the data retrieved from Stackoverflow. [Ref](https://github.com/tanaikech/taking-advantage-of-google-apps-script#trend-of-google-apps-script) It is found that the important statistical result can be obtained by analyzing the data on Stackoverflow. In this report, I would like to introduce the statistical analysis of duplicated questions for the google-apps-script tag in Stackoverflow. When the duplicated question is analyzed, it is considered that the important issues for users can be known. As the result, it was found that there are the trend that the duplicated questions related to Javascript, Google Spreadsheet, the process cost and the cooperation with HTML and Javascript are posted.

### [Safe-Uploading for Google Drive by HTML in External Server using Google Apps Script](https://github.com/tanaikech/Safe-Uploading-for-Google-Drive-by-HTML-in-External-Server-using-Google-Apps-Script)

> This is a report for safe-uploading files to Google Drive by HTML put in the external server using Google Apps Script.

> When you want to make the user upload a file to your own Google Drive using the HTML put in the external server of Google side, when the file size is smaller than 50 MB, this can be achieved without using the access token. [Ref](https://tanaikech.github.io/2020/08/13/uploading-file-to-google-drive-from-external-html-without-authorization/) (When the HTML is put in the internal server of Google side, you can also use [`google.script.run`](https://tanaikech.github.io/2020/02/18/uploading-file-to-google-drive-using-html-and-google-apps-script/).) But, when the file size is over 50 MB, it is required to upload the file with the resumable upload. In this case, the access token is required to be used. In this case that the user uploads to your own Google Drive, when the access token is used in the upload, it is considered that this is the weak point of the security. In this report, I would like to propose the method for safe-uploading files to Google Drive by HTML put in the external server using Google Apps Script. Please think of this as one of several methods.

### [Specification of Search Query for File List Method in Drive API](https://gist.github.com/tanaikech/268baf07f92f3b3962c86c6ea75b786a)

> In this report, I would like to report about the current specification of the search query for the file list method in Drive API.

> Recently, I noticed that the specification of the search query for the file list method in Drive API might have been changed. I thought that to know the change of specification of the search query is important for creating the application using Drive API. In this report, I would like to introduce the current specification of the search query.

<br>

<a name="benchmarks"></a>

# Benchmarks

### [Event Objects for Google Apps Script](https://gist.github.com/tanaikech/4892c97df7ac0504ffd715c2dd6cd546)

> - It was found that the process cost of `e.range.getA1Notation()` was 20 % and 10 % for those of `e.source.getActiveCell().getA1Notation()` and `SpreadsheetApp.getActiveSheet().getActiveCell().getA1Notation()`, respectively.

### [Loop for Array Processing using Google Apps Script without V8](https://gist.github.com/tanaikech/848aeafaac1ec676900bb78e3ce220b6)

> - In the case of the sample script for retrieving the multiple of 5 from the array, the loop using "map, filter" is the most suitable way.
> - Ascending order of cost for each method is "map, filter", "Comprehension", "forEach", "for in", "for loop" and "while".
> - Cost for "forEach", "Comprehension" and "map, filter" is lower than that for "for in", "for loop" and "while".
> - Cost of push() and new Array() is almost the same.
> - When the array is changed from 1 dimensional array to 2 dimensional array, the increasing ratio of the cost for "Comprehension", "forEach" and "map, filter" is much lower than that for "for in", "for loop" and "while".
> - For the conventional method using "for loop", a new method could be proposed using the result of this report.
> - For "reduce", the process costs between 1 and 2 dimensional array are almost the same.

### [fetchAll method in UrlFetch service for Google Apps Script](https://gist.github.com/tanaikech/c0f383034045ab63c19604139ecb0728)

> - It was found that the fetchAll method is worked by the asynchronous processing.
> - After it worked by the asynchronous processing, the returned values is reordered by the order of requests.
> - It was also found that if you want to retrieve the data from the several URL, the process cost of `UrlFetchApp.fetchAll()` is much lower than that of `UrlFetchApp.fetch()` using for loop.

### [Search for Array Processing using Google Apps Script](https://gist.github.com/tanaikech/eda9234822b5dec80549216a43c52652)

> - Process cost of search by indexOf() was the lowest of all methods.
> - 2nd and last one were the search by for loop and the search by the hash, respectively.
> - About the search by hash, although the cost of search by the hash from the object is very low, the cost for creating the object to search the hash was the highest of all. By this, the search by hash became the lowest rank. If the object for searching has already been created, the cost of search by the hash will be the lowest of all.
> - Search using indexOf can reduce the process cost of more than 99 % from the linear search and the search using hash.
> - From these results, it is considered that the scan for indexOf() may be different from the general for loop.

### [Conditional Branch using Google Apps Script](https://gist.github.com/tanaikech/cef47530a58f2d8692cdb1a9d257907b)

> - It was found that the cost of "Ternary operator" was the lowest of all methods and conditions.
> - For the single conditional branch, 2nd one was "If". But for the multiple conditional branches, "Switch" was the 2nd one. This indicates that "If" and "Switch" are suitable for the single and multiple conditional branches (more than 2 branches), respectively.
> - In the case of the multiple conditional branches, the process cost can be reduced by put the condition with the high possibility of "true" to the fore.
> - "Logical operator" was the lowest rank for the single and multiple conditional branches. It is considered that "Logical operator" is not suitable for the general use, because of the high cost and low readability.

### [Decreasing Loop for Array Processing using Google Apps Script](https://gist.github.com/tanaikech/fdd8462a46179efb156cfa0550695c6e)

> - "filter using reversed array" makes the process cost be 43 % lower compare with "Decreasing for loop".
>   - "reversed array" was obtained using "Array.prototype.reverse()" for the created a sample array.
> - "Decreasing for loop" is almost the same with "Increasing for loop".
> - Cost of "reverse()" is sufficiently small for "for loop" and "filter".

### [Reading and Writing Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/d102c9600ba12a162c667287d2f20fe4)

> In this report, the process cost for reading and writing Spreadsheet has been investigated. From this investigation, the following results were obtained.

> - For the process costs for reading values from Spreadsheet
>   1. Process costs of getValues() and getSheetValues() of Spreadsheet Service are almost the same.
>   1. Process costs of values.get and values.batchGet of Sheets API are almost the same.
>   1. Methods of Sheets API can reduce the process costs from those of Spreadsheet Service by about 35 %.
> - For the process costs for writing values from Spreadsheet
>   1. Process costs of values.update, values.batchUpdate and values.append of Sheets API are almost the same.
>   1. Methods of Sheets API can reduce the process costs from those of Spreadsheet Service by about 19 %.
>   1. There is the inversion point between setValues() of Spreadsheet Service and the methods of Sheets API.
>      - When the data size is small, setValues() is suitable for writing values.
>      - When the data size becomes large, the methods of Sheets API are suitable for writing values.

> From these results, it is considered that the methods for reading and writing Spreadsheet of Sheets API are using the different algorithm and/or process from those of Spreadsheet service.

### [Importing CSV Data to Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/030203c695b308606041587e6da269e7)

> In this report, the process cost for importing CSV data to Spreadsheet using GAS has been investigated. As the result, the following results were obtained.

> - It was found that pattern4, which uses `pasteData` of Sheets API, was the lowest cost of all.
> - When pattern4 is used for importing CSV data to Spreadsheet, the cost can be reduced by 56 % from pattern1 and pattern2, which use the method parsing and putting values.
> - When pattern4 is used for importing CSV data to Spreadsheet, the cost can be reduced by 72 % from pattern3, which use the method converting mimeType from CSV to Spreadsheet.

### [Benchmark: Loop for Array Processing using Google Apps Script with V8](https://gist.github.com/tanaikech/3331e1e631d619abef8f32c4be14ba3a)

> In this report, the process cost of "loop" for the array processing using GAS with using V8 runtime has been investigated. As the result, it was found the following important features for GAS with V8.

> - In the case of the sample script for retrieving the multiple of 5 from the array, the loop costs using "for loop", "while", "forEach", "map, filter" and "reduce" are almost the same.
> - In the case of "for in", the process cost is higher than those of "for loop", "while", "forEach", "map, filter" and "reduce". But when that is compared with the condition without V8, the cost of "for in" with V8 is much lower than those without V8.
> - Costs of `push()` and `new Array()` are almost the same.
> - When v8 runtime is used for the loop process, the process cost could be largely reduced when it is compared with the script without V8.
>   - For all methods of "for loop", "for in", "while", "forEach", "map, filter" and "reduce", the process costs of 97.0 % for 1D array and 98.4 % for 2D array could be reduced.

### [Benchmark: Process Costs under V8 using Google Apps Script](https://gist.github.com/tanaikech/7198bc9019202f4080de8fd2e1b278fb)

> In this report, the process costs of 7 situations under V8 were measured. As the result, the following results could be obtained.

> 1. Process cost with and without the arrow function was almost the same.
> 2. Process cost "includes" and "indexOf" was almost the same.
> 3. When the destructuring assignment is used, the cost was about 15 % higher than that without the destructuring assignment.
> 4. Process cost with and without Map object was almost the same.
>    - But in this case, the cost of `Object.fromEntries` is added for retrieving the result as the object. And when `Object.fromEntries` is not used, the cost with Map object was about 20 % lower than that without Map object.
> 5. Process cost of `Array.prototype.push` was the lowest of `Array.prototype.push.apply`, Spread syntax and `concat`. The costs of Spread syntax and `concat` were about 3,040 % and 36,666 % higher than that of `Array.prototype.push`, respectively.
> 6. Process cost of only `reduce` was the lowest of only `reduce`, `Object.assign` and Spread syntax. The costs of `Object.assign` and Spread syntax were about 265 % and 448,063 % higher than that of only `reduce`, respectively.
> 7. Process costs of `Array.from` and only map were almost the same. The cost of `Object.entries` was about 131 % higher than that of `Array.from`.

### [Benchmark: Process Costs for Searching Values in Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/0a6f03970b471ffa286f1dac0b79359e)

> Here, I would like to report the process costs for searching values in Spreadsheet using Google Apps Script (GAS). When the values are searched in Google Spreadsheet, the following 3 patterns can be considered. [Ref](https://stackoverflow.com/a/56663884)
>
> 1. Retrieve all values using getValues, and the values are searched from the retrieved array.
> 2. Use TextFinder.
> 3. Use Query language.
>
> In these cases, it has already been found that the lowest process cost is to use the Query language. And about finding values from an array, I have already been reported as "[Benchmark: Search for Array Processing using Google Apps Script](https://gist.github.com/tanaikech/eda9234822b5dec80549216a43c52652)". But I had never summarized the process costs for TextFinder and find values from an array. So in this report, I would like to introduce this. As the result, the importance of TextFinder for retrieving the row numbers and the row values by searching a value could be understand.

### [Benchmark: Process Costs for Retrieving Values from Arrays for Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/6333d797149ab9d69382d1b368f96e80)

> Here, I would like to report the process costs for retrieving the values from the arrays for Spreadsheet using Google Apps Script (GAS). When Spreadsheet is used with Google Apps Script, we have the following situations.

> 1. Retrieve values from the multiple rows in a column.
> 2. Retrieve values from the multiple columns in a row.

> When the values are retrieved from above situations, it is required to retrieve the values from 1 dimensional array in the 2 dimensional array. In this report, the process costs for retrieving the values from the 2 dimensional array of above situations have been measured.

> As the result, it was found that when the values are retrieved from the arrays with n rows in a column and n columns in a row, to use the destructuring assignment and to use the index are suitable, respectively.

### [Benchmark: Measuring Process Costs for Formulas in Cells on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/b00be25a02ec283689480ac8138cbfeb)

> When Google Spreadsheet is used, there is the case that the built-in functions and the custom functions in the cells are used. For the functions of Google Apps Script, there is the method for measuring the process cost. [Ref](https://github.com/tanaikech/taking-advantage-of-google-apps-script#benchmarks) But for the built-in functions, it is required to create the script for it. In this report, the script for measuring a function put in a cell has been proposed, and the process cost of the built-in functions has been measured. The proposed script can measure the process cost for the built-in functions and custom functions on Google Spreadsheet. The script is created with using Google Apps Script. When the process cost can be known for the built-in functions and custom functions, it is considered that it will be useful for the developers using Google Spreadsheet.

### [Benchmark: Process Costs for Retrieving 1st Empty Cell and 1st Non Empty Cell of Specific Column in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/61cbda29436795f199a9e4244e0bf5fe)

> Here, I would like to report the process costs for retrieving the 1st empty cell or 1st non empty cell of the specific column of Google Spreadsheet using Google Apps Script (GAS). For this situations, the following 2 patterns can be considered.

> 1. Retrieving 1st empty cell of specific column by searching from **TOP** of sheet

> 2. Retrieving 1st NON empty cell of specific column by searching from **BOTTOM** of sheet

> Actually, when I create the applications using GAS, there is the case that it's required to retrieve the 1st empty cell or 1st non empty cell of the specific column. But, in such case, I would like to make the process cost of this as low as possible comparing with other part of the application. From such my experience, I thought that when the process cost of this can be reduced, it will be also useful for other users. So in this report, I would like to introduce the process cost of this situation. And, the following results were obtained.

> - In order to retrieve the 1st empty cell of the specific column by searching from **TOP** of sheet, the process cost of method using `getNextDataCell` is the lowest of all methods.

> - In order to retrieve 1st NON empty cell of specific column by searching from **BOTTOM** of sheet, the process cost of method using `TextFinder` is the lowest of all methods.

<br>

<a name="communities"></a>

# Communities

### [Communities for Google Apps Script](https://gist.github.com/tanaikech/6b42d86414c5529fee56367d6bf67516)

> Consumer (personal) version of Google+ is closed on April 2, 2019. By this, [Apps Script community of Google+](https://plus.google.com/communities/102471985047225101769/) is also closed. This is one of important communities for discussing. So in this post, I would like to introduce the other communities related to Google Apps Script.

<br>

<a name="samplescripts"></a>

# Sample Scripts

<a name="filesingoogledrive"></a>

#### Files in Google Drive

- [File upload using doPost on Google Web Apps](https://tanaikech.github.io/2017/02/05/file-upload-using-dopost-on-google-web-apps/)
- [Retrieving Access Token for Google Drive API using GAS](https://gist.github.com/tanaikech/64175178489d1d72a6090b79be901c23)
- [Create Folder Tree on Google Drive](https://tanaikech.github.io/2017/03/13/create-folder-tree-on-google-drive/)
- [Download Files Without Authorization From Google Drive](https://tanaikech.github.io/2017/03/20/download-files-without-authorization-from-google-drive/)
- [How to use "fields" of Drive APIs](https://tanaikech.github.io/2017/03/30/how-to-use-fields-of-drive-apis/)
- [File Transfer for Google Drive Without Authorization](https://github.com/tanaikech/FileTransfer)
- [Converting PDF to TXT](https://gist.github.com/tanaikech/825f4b848a8cbff7018f71d33399e99b)
- [Retrieving Access Token for Google APIs](https://gist.github.com/tanaikech/247e4db66098e94f9e7da1b857f0a9be)
- [Downloading Files From Google Drive Under No Authorization Using Browser](https://gist.github.com/tanaikech/c5b2811bce01cbcc26ffa357df496379)
- [(NEW) Retrieve old revision file from Google Drive](https://gist.github.com/tanaikech/9ab6683e78de0044b4f670ff3761af19)
- [Get File List Under a Folder on Google Drive](https://gist.github.com/tanaikech/8e9b6fd667efcb483c9c742da9cd4e19)
- [Retrieving Access Token From OneDrive using Google Apps Script](https://gist.github.com/tanaikech/d9674f0ead7e3320c5e3184f5d1b05cc)
- [Interconversion Between Google Docs and Microsoft Docs](https://gist.github.com/tanaikech/8d639542577a594f6104b7f6fb753064)
- [Retrieving Files with Filename Included Special Characters using Google Apps Script](https://gist.github.com/tanaikech/e74ead2537b7b3718fc824b6ca60a531)
- [Selecting Files in Google Drive using Select Box for Google Apps Script](https://gist.github.com/tanaikech/96166a32e7781fee22da9e498b2289d0)
- [Uploading Local Files to Google Drive without Authorization using HTML Form](https://gist.github.com/tanaikech/2f16f467c94612dc83920a3158614d95)
- [Retrieving latest created file from PDF files on Google Drive](https://gist.github.com/tanaikech/0f452b2f951dddb57363dbb816487c33)
- [Downloading File Using Button of Dialog Box on Google Docs](https://gist.github.com/tanaikech/0f1fd11b7e4d45b016d45bbeeb06aa46)
- [Which of Drive API v2 or v3 is used for DriveApp.searchFiles()?](https://gist.github.com/tanaikech/242f644026837dd071f0ce95b2fd107a)
- [Resumable Conversion from CSV File with Large Size (> 50 MB) to Several Spreadsheets by Splitting File](https://gist.github.com/tanaikech/3e44c779f05374d19333444c9a4dd5ba)
- [Upload Files to Google Drive using Javascript](https://gist.github.com/tanaikech/bd53b366aedef70e35a35f449c51eced)
- [Enhanced makeCopy() using Google Apps Script](https://gist.github.com/tanaikech/ac1b0d50fe1ffaa40e95bbe9faf908b9)
- [Retrieving file list with folder structure under a specific folder in Google Drive](https://gist.github.com/tanaikech/4fca197b8ec45c8ac6300b1531c2489d)
- [Uploading Multiple Files From Local To Google Drive using Google Apps Script](https://gist.github.com/tanaikech/88fcae255abb4aac5bec81ad5ca213ef)
- [tarUnarchiver for Google Apps Script](https://github.com/tanaikech/tarUnarchiver-for-Google-Apps-Script)
- [Converting Many Files to Google Docs using Google Apps Script](https://gist.github.com/tanaikech/d60700b523af7aaf89b9e7c92e35c3c2)
- [Creating Google Document by Converting PDF and Image Files with OCR using Google Apps Script](https://gist.github.com/tanaikech/b73396314254f7a5bf571af6b65eac07)
- [Overwriting Several Google Documents by 2 Text Files using Google Apps Script](https://gist.github.com/tanaikech/55f0a57ed98ff11e7d8780cc773b6dce)
- [Modifying Revisions of a File on Google Drive using Google Apps Script](https://gist.github.com/tanaikech/9508a9007c1a5196e4b234ea40528f96)
- [One Time Download for Google Drive](https://github.com/tanaikech/One_Time_Download_for_Google_Drive)
- [Resumable Upload of Multiple Files with Asynchronous Process for Google Drive](https://github.com/tanaikech/AsynchronousResumableUploadForGoogleDrive)
- [Moving File to Specific Folder using Google Apps Script](https://gist.github.com/tanaikech/84dd9e9f79cad87bedb45e21342c0121)
- [Uploading File to Google Drive using HTML and Google Apps Script](https://gist.github.com/tanaikech/280b782ee0518aa083a4fe0d71384823)
- [Retrieving Files and Folders without Parents in Google Drive](https://gist.github.com/tanaikech/459089e678bad943f0f33e497e04c36f)
- [Creating Shortcut on Google Drive using Google Apps Script](https://gist.github.com/tanaikech/4639cccc8130cea10d753fee9f900041)
- [Batch Requests for Drive API using Google Apps Script](https://github.com/tanaikech/Batch-Requests-for-Drive-API-using-Google-Apps-Script)
- [Converting SVG Format to PNG Format using Google Apps Script](https://gist.github.com/tanaikech/8a6d46ca43665aa7e62965ed32336598)
- [Uploading File to Google Drive from External HTML without Authorization](https://gist.github.com/tanaikech/d3e62002e522f9e3f2b35bc56c64b2c9)
- [Using Values Submitted from HTML Form using Google Apps Script](https://gist.github.com/tanaikech/58d96c023468fc1922d67764251b25e0)
- [Achieving Search of Files by 'is:unorganized owner:me' using Google Apps Script](https://gist.github.com/tanaikech/ec6aa9f2967d2f837df7c87276a0c168)
- [Safe-Uploading for Google Drive by HTML in External Server using Google Apps Script](https://github.com/tanaikech/Safe-Uploading-for-Google-Drive-by-HTML-in-External-Server-using-Google-Apps-Script)

<a name="projects"></a>

#### Projects

- [Retrieving ClientId using Google Apps Script](https://gist.github.com/tanaikech/4656b1b01128d27f291cee317553ea6d)
- [Copying and Overwriting GAS Project](https://gist.github.com/tanaikech/3e7608bd8ba87dd6019aedbd09224bd3)
- [Remove Third-party Apps with Account Access using Google Apps Script](https://gist.github.com/tanaikech/608e65fee105989df1a7b645c20572c2)
- [Retrieving Reformatted Scripts without Comments in a Project using Google Apps Script](https://gist.github.com/tanaikech/61f69fd2ce181865d3430c260c6a5d0b)
- [Backup Project as zip File using Google Apps Script](https://gist.github.com/tanaikech/035aa9f6603e7a8698c1cc67ab43e132)

<a name="spreadsheets"></a>

#### Spreadsheets

- [Download a CSV File from Spreadsheet Using Google HTML Service](https://tanaikech.github.io/2017/02/16/download-a-csv-file-from-spreadsheet-using-google-html-service/)
- [Send E-mail with Excel file converted from Spreadsheet](https://tanaikech.github.io/2017/02/16/send-e-mail-with-excel-file-converted-from-spreadsheet/)
- [Export CSV File from Spreadsheet and Make Download Button](https://tanaikech.github.io/2017/02/20/export-csv-file-from-spreadsheet-and-make-download-button/)
- [Creating Downloaded Excel file as Spreadsheet](https://tanaikech.github.io/2017/04/14/creating-downloaded-excel-file-as-spreadsheet/)
- [Creating Spreadsheet from Excel file](https://tanaikech.github.io/2017/04/15/creating-spreadsheet-from-excel-file/)
- [Converting Spreadsheet to PDF](https://tanaikech.github.io/2017/04/20/converting-spreadsheet-to-pdf/)
- [Overwriting Spreadsheet to Existing Excel File](https://tanaikech.github.io/2017/04/21/overwriting-spreadsheet-to-existing-excel-file/)
- [Retrieving User Information with Shared Spreadsheet](https://gist.github.com/tanaikech/a4a23d66134a900ddcb1652a4d420a58)
- [Embedding a Map to a Cell using Custom Function on Spreadsheet](https://gist.github.com/tanaikech/408f0eb58b18b08c4aa3783e5ee7463e)
- [Embedding Animation GIF in A Cell on Spreadsheet](https://gist.github.com/tanaikech/9b540220a9f408c05213c82e085c891a)
- [Search Route and Embedding Map using Custom Function on Spreadsheet](https://gist.github.com/tanaikech/e2d49b88b5d45cf2f26e6aaa14eafe91)
- [Pseudo Browser with Google Spreadsheet](https://gist.github.com/tanaikech/a290509e3d3f6997d248b88763fc69b9)
- [Retrieving Images on Spreadsheet](https://gist.github.com/tanaikech/d6594dc5c6c49a015c7d408c90e58bdc)
- [Converting a1Notation to GridRange for Google Sheets API](https://gist.github.com/tanaikech/95c7cd650837f33a564babcaf013cae0)
- [Retrieving Values By Header Title for Spreadsheet](https://gist.github.com/tanaikech/3036ee0199e2261f377aacbd7e458d1c)
- [Retrieving Spreadsheet ID from Range using Google Apps Script](https://gist.github.com/tanaikech/d4b033014c36c3506ad3ec38ce1eae4f)
- [Enhanced onEdit(e) using Google Apps Script](https://gist.github.com/tanaikech/73edaed1268a6d07118aed538aa5608d)
- [Measuring Execution Time of Built-In Functions for Google Spreadsheet](https://gist.github.com/tanaikech/1e7df0d6991d4e39330cd2b353573e72)
- [Retrieving Instance of User-Interface Environment](https://gist.github.com/tanaikech/f05e7d82b754b0348463b8dec1c741ad)
- [Automatic Recalculation of Custom Function on Spreadsheet Part 1](https://gist.github.com/tanaikech/b8ea7bd7fd87bcd7bb28ddede1781889)
- [Open Site with New Window using Google Apps Script](https://gist.github.com/tanaikech/9115c70eb83558d3af2eea656e4d9c67)
- [Append Values by Inserting Rows using Google Sheets API](https://gist.github.com/tanaikech/7846ebcafbab8318ff74c9955a99e06b)
- [Retrieves All Named Ranges in Spreadsheet as a1Notation](https://gist.github.com/tanaikech/aa744c9a15818c002d90eaea6b4efd03)
- [CLEAN method for Google Apps Script](https://gist.github.com/tanaikech/585597adda7954ba1cde3e724582bac5)
- [Retrieve Last of Specific Row and Column](https://gist.github.com/tanaikech/044d8651aed41c886f3379fdf5165aa2)
- [Parsing A1Notations using Google Apps Script](https://gist.github.com/tanaikech/c59b90324c90935b13f9e7b26cbf436a)
- [Closing Existing Sidebar using Google Apps Script](https://gist.github.com/tanaikech/c1b5fb20342dae623139ca0f48c8c12c)
- [Opening Dialog Box during Calculation and Retrieving Calculated Result using Google Apps Script](https://gist.github.com/tanaikech/3a4837d4ef0d31522cd9ff29c085c786)
- [Creating One-time Writing Cells using Google Apps Script](https://gist.github.com/tanaikech/4ba859167a84ed625fcbab392c8d34cd)
- [Limitations for Inserting Images to Google Docs](https://gist.github.com/tanaikech/9414d22de2ff30216269ca7be4bce462)
- [Possibility of Real Time Processes In a Cell on Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/52e7bbdabf8bfc34ac16d5f27fd8cb80)
- [Fixing Value Putting by Custom Function of Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/6ebf4bafbdc35116470bd197d00fe614)
- [Protecting Cells of Spreadsheet that Users Copied from Your Google Drive to User's Google Drive using Google Apps Script](https://gist.github.com/tanaikech/847ea7e3e27a4a22004faa88d7b4dedb)
- [Retrieving Values from Filtered Sheet in Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/053d3ebbe76fa7c0b5e80ea9d6396011)
- [Automatic Recalculation of Custom Function on Spreadsheet Part 2](https://gist.github.com/tanaikech/cb5447616bfc6a01de8a49131c0d2db0)
- [Retrieving Values from Sheet Filtered by Slicer in Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/7cc9efb29ba6063da04f81e50d858f52)
- [Dynamically Updating Custom Menu of Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/1232a8fd1ffbd84c96ebbb97051c5b59)
- [Rearranging Columns on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/59dc1398785803d188393fb04673f1bc)
- [Retrieving Overwrapped Cells Between 2 Ranges on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/492cc2bb0b978fdb344aa821962baf53)
- [Updated: Expanding A1Notations using Google Apps Script](https://gist.github.com/tanaikech/4fd7d66771d552ed83166df314cb0024)
- [Workaround for Retrieving Direct Links of All Sheets from URL of 2PACX-### of Web Published Google Spreadsheet](https://gist.github.com/tanaikech/e6251657d425d2827fee6dd3daf47976)
- [Hiding and Deleting Rows and Columns on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/a1e6c0b49043cbf92f8b3c25d18ebeed)
- [Change Tab Detection on Google Spreadsheet using onSelectionChange Event Trigger with Google Apps Script](https://gist.github.com/tanaikech/524c16dbef722763f80312357d0e4368)
- [Enhanced Custom Function for Google Spreadsheet using Web Apps as Wrapper](https://github.com/tanaikech/Enhanced-Custom-Function-for-Google-Spreadsheet-using-Web-Apps-as-Wrapper)
- [Disabling Buttons Put on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/28102d28b929e102f6fe88e7d42e2d64)
- [Highlighting Row and Column of Selected Cell using Google Apps Script](https://gist.github.com/tanaikech/3e6b6bbc13cd9814aa918c9933fb862f)
- [Workaround: Putting Multiple Hyperlinks to a Cell using Sheets API](https://gist.github.com/tanaikech/b18c0189a5d0266a849090fdbe6750a5)
- [Search Dialog Sample using TextFinder with Google Apps Script](https://gist.github.com/tanaikech/64ab751e8fd8727d23e5f159c00e1579)
- [Adjusting Text Length to Fit in Cell Width on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/784bae8c41b7d9bcba5b581920dda3f4)
- [Switching Buttons for Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/2e6cadc1f65d42aa161bcbd24e6cadb7)
- [Converting Range in Google Spreadsheet as Image using Google Apps Script](https://gist.github.com/tanaikech/6ec4f2278510311ea06b838c69828692)
- [Creating Spreadsheet with Custom Header and Footer using Google Apps Script](https://gist.github.com/tanaikech/0430c7a8cf28508aa3cb80c22136f7f9)
- [Google Apps Script: Running Specific Function When Specific Sheet is Edited on Google Spreadsheet](https://gist.github.com/tanaikech/bc09d1e03a0ebed3af894a6ed61cf12d)
- [Setting Alternate Background Colors for Rows in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/89aaa3adcd3a1fc37187ca61f389cbe9)
- [Sorting Cells on Google Spreadsheet with Background colors using Google Apps Script](https://gist.github.com/tanaikech/8e531fdb4125c843b58cf7bef6165786)
- [Retrieving All Values from All Sheets from URL of 2PACX- of Web Published Google Spreadsheet using Google Apps Script and Javascript](https://gist.github.com/tanaikech/1876f19638e329253cf352225bd180cd)
- [Creating Multiple Buttons on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/17d48dbcf4c1a39663424cae658e50cb)
- [User Runs Script for Range Protected by Owner using Google Apps Script](https://gist.github.com/tanaikech/5ebf492b53de40fe254dba63c8520391)
- [Downloading Google Spreadsheet as XLSX and PDF file by Clicking Button](https://gist.github.com/tanaikech/61dea338dfba386f87c592d4ee6c68af)
- [Replacing Multiple Values in Google Spreadsheet with Low Process Cost using Google Apps Script](https://gist.github.com/tanaikech/3030603299d1e302821611c834420258)
- [Downloading Active Sheet in Google Spreadsheet as CSV and PDF file by Clicking Button](https://gist.github.com/tanaikech/114dad7d31dde402b4892787e9cceaad)
- [Copying Protections for Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/b22a76d419a6bdbfa064f5b31f6eae8e)
- [Creating Colorful Buttons on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/5eedf04fa0f7727570b8e4c45b84a1f1)

<a name="documents"></a>

#### Documents

- [Retrieving Number of Lines of Google Document](https://gist.github.com/tanaikech/37def8eeeaf7780bb99d3289ee32385e)
- [Replacing Text to Image for Google Document using Google Apps Script](https://gist.github.com/tanaikech/f84831455dea5c394e48caaee0058b26)
- [Modify Shading Color of Paragraph on Google Document using Google Apps Script](https://gist.github.com/tanaikech/aadeca550943d07ee25d90d3bda3c9b9)
- [Modify Searched Text to Small Capital Letters using Google Apps Script](https://gist.github.com/tanaikech/30e8c778eb1102f651550b2345b6f3c0)
- [Deleting Positioned Images on Google Document using Google Apps Script](https://gist.github.com/tanaikech/02c4c4ec7cb0ac83771e4306afcd422c)
- [Limitations for Inserting Images to Google Docs](https://gist.github.com/tanaikech/9414d22de2ff30216269ca7be4bce462)
- [Retrieving Total Page of Google Document using Google Apps Script](https://gist.github.com/tanaikech/c78087c647dc9b5547b580ccd3629974)
- [Deleting Pages of Google Document using Google Apps Script](https://gist.github.com/tanaikech/6d33c3ce00cd46e45d3551a587b2ae17)
- [Creating New Table and Putting Values to Cells using Google Docs API with Google Apps Script](https://gist.github.com/tanaikech/3b5ac06747c8771f70afd3496278b04b)
- [Deleting Last Empty Page of Google Document using Google Apps Script](https://gist.github.com/tanaikech/8e018892ebb417779e9a7fedfc6a4a7d)
- [Updated Specification of Google Spreadsheet: Multiple Hyperlinks to a Cell](https://gist.github.com/tanaikech/d39b4b5ccc5a1d50f5b8b75febd807a6)
- [Modifying 1st-Page Header in Google Document using Google Apps Script](https://gist.github.com/tanaikech/d430543089cc687e5d9c2bc96d3178ff)
- [Retrieving All URLs in Google Document using Google Apps Script](https://gist.github.com/tanaikech/d3ce0c2186885ee27d23e02ddd2696b7)
- [Changing Font of Selected Text to 'Google Sans' on Google Document using Google Apps Script](https://gist.github.com/tanaikech/4700361cc060ae4333672da905d272c7)

<a name="slides"></a>

#### Slides

- [Retrieving Size of Tables in Google Slides using Google Apps Script](https://gist.github.com/tanaikech/3143be7e7df8cc595d73427d22ae2e0e)
- [Summarizing Slides as Thumbnails](https://gist.github.com/tanaikech/79749b9fc411da91f932608b5c01ea5b)
- [Limitations for Inserting Images to Google Docs](https://gist.github.com/tanaikech/9414d22de2ff30216269ca7be4bce462)
- [Managing Texts on Google Slides using Google Apps Script](https://gist.github.com/tanaikech/04e7b7657f97ddd7c68b6a9ddc3cdf98)
- [Cropping Images in Google Slides using Google Apps Script](https://gist.github.com/tanaikech/a86781b425fe3f14edd5058ca8d46fe7)
- [Retrieving Data from QR code on Google Slides using Google Apps Script](https://gist.github.com/tanaikech/4fc0b33493d375e589d61312d2f028b7)
- [Adding Slide Page Link to Shape using Google Apps Script](https://gist.github.com/tanaikech/444379309f1d0f69287c5a8becdc271d)
- [Creating Custom Grid View of Google Slides as Image and Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/c94b79819167e96f6d9268d066989112)
- [Simple Photo Gallery Created by Google Slides and Web Apps using Google Apps Script](https://github.com/tanaikech/SimplePhotoGalleryUsingGoogleAppsScript)

<a name="gmail"></a>

#### Gmail

- [How to Retrieve Replied Emails for Gmail](https://gist.github.com/tanaikech/a047e5f67f30b93482986039daa16dbc)
- [Adding a Label to a Message using Message ID for Gmail](https://gist.github.com/tanaikech/69c7daf910fdad0d6a296ea19f612089)

<a name="calendar"></a>

#### Calendar

- [Running Google Apps Script by Event Notification from Google Calendar](https://gist.github.com/tanaikech/fbbfaa8f2a8a770424974aa16b9b6f3b)
- [Retrieving Event ID from Event URL of Google Calendar using Google Apps Script](https://gist.github.com/tanaikech/b366be5995be04f689c3d80b18363f5e)
- [Managing A Lot Of Google Calendar Events using Batch Requests with Google Apps Script](https://github.com/tanaikech/Managing-A-Lot-Of-Google-Calendar-Events-using-Batch-Requests-with-Google-Apps-Script)
- [Sample Scripts for Creating New Event with Google Meet Link to Google Calendar using Various Languages](https://gist.github.com/tanaikech/94791d48823e9659aa376cf7f0161d9b)

<a name="chart"></a>

#### Chart

- [Making charts at spreadsheet](https://tanaikech.github.io/2017/02/13/making-charts-at-spreadsheet/)
- [Embedding a Chart to a Cell using Custom Function on Spreadsheet](https://gist.github.com/tanaikech/52da88484851ce2e0dea9881bf49f6fa)
- [Changing Line to Bars for Combo Chart using GAS](https://gist.github.com/tanaikech/bff89176cd269e392c45500274b40810)
- [Adding Title of vAxis to Embedded Chart on Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/4125cc280e15c0fc726cb2fe4f35a3f7)

<a name="analytics"></a>

#### Analytics

- [Retrieving Users, Sessions and PageViews of User Summary Report from Google Analytics using Google Apps Script](https://gist.github.com/tanaikech/dc3e9c8dfec9403ed0b1935605ea1476)

<a name="slack"></a>

#### Slack

- [Changing Slack Status using Google Apps Script](https://tanaikech.github.io/2017/05/09/changing-slack-status-using-google-apps-script/)
- [Uploading Image Files to Slack Using Incoming Webhooks by Google Apps Script](https://gist.github.com/tanaikech/159cec05583c6f206e144f33b4042559)
- [Using Dialog Box of Slack by Google Apps Script](https://gist.github.com/tanaikech/c111f5560d21a07529e0da870af06a7d)

<a name="virtualcurrency"></a>

#### Virtual Currency

- [Bitfinex API for Google Apps Script](https://gist.github.com/tanaikech/1104d039341f198f95eee66af57c0abf)
- [Binance API for Google Apps Script](https://gist.github.com/tanaikech/175067567819577fd8eba9b82eabd1a6)
- [Bittrex API for Google Apps Script](https://gist.github.com/tanaikech/07fb768cf6d8256b3a72716a72e99f91)
- [Zaif API for Google Apps Script](https://gist.github.com/tanaikech/77481c2621dc7429449194c0f1dbd58c)
- [Cryptopia API for Google Apps Script](https://gist.github.com/tanaikech/58f092a544eb1cfbb19bc0252f36e4cb)

<a name="stackoverflow"></a>

#### Stackoverflow

- [Notifying Comments at Stackoverflow by Email using Google Apps Script](https://github.com/tanaikech/Notifying-Comments-at-Stackoverflow-by-Email)

<a name="netatmo"></a>

#### Netatmo

- [Notifying with email when Netatmo was down](https://github.com/tanaikech/Notifying-with-email-when-Netatmo-was-down)

<a name="figma"></a>

#### Figma

- [Figma to Google Slides using Google Apps Script](https://gist.github.com/tanaikech/6aeb3ff13765cfba465862e2e2c3dd3b)

<a name="etc"></a>

#### Etc

- [OCR using Google Drive API](https://gist.github.com/tanaikech/8c808bf8c060455fe5401ecacad07b94)
- [Multipart-POST Request Using Google Apps Script](https://gist.github.com/tanaikech/d595d30a592979bbf0c692d1193d260c)
- [Changing Values by Checking Duplicated Values of JSON for Javascript](https://gist.github.com/tanaikech/4c659fbb7cf8df0bc2c063dafa10e36c)
- [Straightening Elements in 2 Dimensional Array using Google Apps Script](https://gist.github.com/tanaikech/6a8b169cdcbda5a84f19964b81e447d9)
- [Batching Requests for Google Apps Script](https://gist.github.com/tanaikech/f167b9280a8e710804e4061571b53fb9)
- [Transposing JSON Object using Google Apps Script](https://gist.github.com/tanaikech/806fe728f8cf964078ef1354307a433d)
- [Retrieve Difference Between 2 Dimensional Arrays using Google Apps Script](https://gist.github.com/tanaikech/2abf57eefc667d6c71310db6aa95a44d)
- [About Updated Utilities.computeHmacSignature()](https://gist.github.com/tanaikech/9e9ab42ad225e127c59ae8ae598aacac)
- [Retrieving a Key with Maximum Value from Object](https://gist.github.com/tanaikech/fcbc0204e92d8f1cdde74dc5ac820753)
- [Adding Query Parameters to URL using Google Apps Script](https://gist.github.com/tanaikech/70503e0ea6998083fcb05c6d2a857107)
- [Retrieving Screen Shots of Sites using Google Apps Script](https://gist.github.com/tanaikech/a434b4ed50d91fe5f56fffcf6bcb3f78)
- [Retrieving Access Token for Service Account using Google Apps Script](https://gist.github.com/tanaikech/20ea127a8e23a7c609f8d764c8b7ed7c)
- [Parsing Query Parameters from URL using Google Apps Script](https://gist.github.com/tanaikech/34437522f3ce777bd060458b9cc02bdf)
- [Split Array by n Elements using Google Apps Script](https://gist.github.com/tanaikech/c1fd2b4bce19597abc609b72818c1d8e)
- [Processing Duplicated Rows of 2 Dimensional Arrays using Google Apps Script](https://gist.github.com/tanaikech/5c2d6187c08b2d7b2f7a561de0c75c5e)
- [Retrieving Values with and without Duplicating from JSON Object using Google Apps Script](https://gist.github.com/tanaikech/16ba2c77cdc8caa6a02958c9a4006e8a)
- [Parsing HTML using Google Apps Script](https://gist.github.com/tanaikech/e85193a89d041fed6122583739309786)
- [Examples of How to Derive a Signing Key for Signature Version 4 (AWS) for Google Apps Script](https://gist.github.com/tanaikech/97a2787db7be94180a64e1f4c194d415)
- [Running Functions by Specifying Function Names with Web Apps for Google Apps Script](https://gist.github.com/tanaikech/b2e0325a28efe7c609e4688ec22ee22c)
- [URL Encode with Shift-JIS using Google Apps Script](https://gist.github.com/tanaikech/f23755d7e024fea9c0f0e036853484d4)
- [Retrieving Difference Between 2 Arrays using Google Apps Script](https://gist.github.com/tanaikech/cc7bdfe67c3b72c48c290fc11c231e72)
- [Sample Scripts for Requesting to Web Apps by Various Languages](https://gist.github.com/tanaikech/a72aab0242012362c46ec69031c720d5)
- [Logs in Web Apps for Google Apps Script](https://gist.github.com/tanaikech/3ccb4dd8ce43de21fdb764a68c14a4d7)
- [Workaround: Showing Log in Web Apps to Apps Script Dashboard using Javascript](https://gist.github.com/tanaikech/e27581278f8cb464dff1dd83d6f887a7)
- [IMPORTANT: reduceRight with and without v8 runtime for Google Apps Script](https://gist.github.com/tanaikech/7f13f4297d7307a47ad78f0254ce3353)
- [Inserting Text on Image using Google Apps Script](https://gist.github.com/tanaikech/835642df109731a559e52d831bd3342d)
- [Request of multipart/form-data with Simple Request Body using Google Apps Script](https://gist.github.com/tanaikech/5cd0dc9ea7d75e4a2ff65049ed3d78c3)
- [Converting Texts to Bold, Italic and Bold-Italic Types of Unicode using Google Apps Script](https://gist.github.com/tanaikech/39797ccd1b9280f967fe62b3328d782a)
- [Xpath Tester using Web Apps Created by Google Apps Script](https://gist.github.com/tanaikech/8a596d235205ba443452aeb510220477)
- [Plotting Points on Image using Google Apps Script](https://gist.github.com/tanaikech/fbb16f1eb43b3bafa93323461a500640)
- [Creating PNG Image with Alpha Channel using Google Apps Script](https://github.com/tanaikech/Creating-PNG-Image-with-Alpha-Channel-using-Google-Apps-Script)

<a name="nodejs"></a>

#### Node.js

- [Downloading Files Under Specific Folder using Node.js](https://gist.github.com/tanaikech/38b536923b1765da052c21aab093649d)
- [Send mails from Gmail using Nodemailer](https://gist.github.com/tanaikech/d225c7adab818a6dc1dfd7783f8c8e4d)
- [Create Folder Tree of Google Drive using Node.js](https://gist.github.com/tanaikech/97b336f04c739ae0181a606eab3dff42)
- [Directly Using Access Token by googleapis for Node.js](https://gist.github.com/tanaikech/ca11c53356c5466e60109f79d9e4d9c9)
- [Creating New Google Docs and Overwriting Existing Google Docs by Text with Node.js without using googleapis](https://gist.github.com/tanaikech/915f1034749b8b2f451556167663ea19)
- [Retrieving Access Token using Service Account for Node.js without using googleapis](https://gist.github.com/tanaikech/7aaf2276e4e6104b89802e85957e75ae)
- [Creating a Table to Google Document by Retrieving Values from Google Spreadsheet for Node.js](https://gist.github.com/tanaikech/e64342de7011228f5fb639d7d1123ebb)
- [Music Streaming Player for Discord with Google Drive using Node.js](https://gist.github.com/tanaikech/6029cb2422dd58fe24c3a16a43ce7c35)
- [Simple Script of Resumable Upload with Google Drive API for Node.js](https://gist.github.com/tanaikech/ae451679e8220f3b2d48edb3f8c1a8d3)
- [Uploading Files of multipart/form-data to Google Drive using Drive API with Node.js](https://gist.github.com/tanaikech/33563b6754e5054f3a5832667100fe91)
- [Retrieving All Values from All Sheets from URL of 2PACX- of Web Published Google Spreadsheet using Node.js](https://gist.github.com/tanaikech/49e1e6515225d810e849b3487142a90d)
- [Downloading and Uploading File to Google Drive without Saving File with Stream and Resumable Upload using Node.js](https://gist.github.com/tanaikech/99187753ceb5fd55d343b52dcbe176a5)
- [Simple Script of Resumable Upload with Google Drive API for Axios](https://gist.github.com/tanaikech/0e33b7a850e8c56d111ed0f32df0b485)

<a name="golang"></a>

#### Golang

- [spreadsheets.values.batchUpdate using Golang](https://gist.github.com/tanaikech/0f5b15fec7f409cdb568b0c2904fccb2)
- [Uploading CSV File as Spreadsheet and Modifying Permissions using Golang](https://gist.github.com/tanaikech/7ee103c80759a8297da198a5d1e92fc8)
- [Using String Values to []googleapi.Field for Golang](https://gist.github.com/tanaikech/27d27a1ac7fa99503e0737c28db53056)
- [Retrieving Access Token using Service Account by Google's OAuth2 package for Golang](https://gist.github.com/tanaikech/4b4cb27ece27573b3f4df0e050b52330)
- [Sorting for Slice using Golang](https://gist.github.com/tanaikech/4d0075dc21b643245be03d661e8d5f54)
- [Creating a Table to Google Document by Retrieving Values from Google Spreadsheet for Golang](https://gist.github.com/tanaikech/0589a673cae9569181def8ccd10793cf)
- [Resumable Uploading Files to Google Drive using Golang](https://gist.github.com/tanaikech/19655a8130bac1ba510b29c9c44bbd97)
- [Setting Number Format of Cells on Google Spreadsheet using batchUpdate in Sheets API with golang](https://gist.github.com/tanaikech/76cde17cecba38f44398c3effe2aedf2)
- [Using Request Body of String JSON for Google APIs with googleapis of golang](https://gist.github.com/tanaikech/3f1c8e9f40e78263ec1ade2cb9461dcc)

<a name="python"></a>

#### Python

- [Updating Thumbnail of File on Google Drive using Python](https://gist.github.com/tanaikech/731c412c271828276bf3e24a25235aab)
- [Uploading Files From Local To Google Drive by Python without Quickstart](https://gist.github.com/tanaikech/8cdfd23807372657dc63d81e25e35153)
- [Creating a Table to Google Document by Retrieving Values from Google Spreadsheet for Python](https://gist.github.com/tanaikech/305e413696bcdf3a2ee3e86cebf3c7dc)
- [Simple Script of Resumable Upload with Google Drive API for Python](https://gist.github.com/tanaikech/f709a952ff6e286027950d0484f6c03e)
- [Retrieving All Values from All Sheets from URL of 2PACX- of Web Published Google Spreadsheet using Python](https://gist.github.com/tanaikech/51628e5e0a2c017329457afdb1936912)

<a name="curl"></a>

#### Curl

- [File Upload and Download with File Convert For curl using Drive API](https://tanaikech.github.io/2017/02/08/file-upload-and-download-with-file-convert-for-curl-using-drive-api/)
- [Downloading Shared Files on Google Drive Using Curl](https://gist.github.com/tanaikech/f0f2d122e05bf5f971611258c22c110f)
- [Updating a File with Resumable Upload using Drive API](https://gist.github.com/tanaikech/bc33a83ac648911d00b43c59a24268fc)

<a name="javascript"></a>

#### Javascript

- [Uploading Image Files to Google Photos using axios](https://gist.github.com/tanaikech/426345c24e46da3ac7268f31b76bb3e4)
- [Retrieving Access Token for Service Account using Javascript](https://gist.github.com/tanaikech/3c7f208cb352a807b3d30b9c1dcf0c82)

<a name="php"></a>

#### PHP

- [Retrieving Access Token using Service Account for PHP without using googleapis](https://gist.github.com/tanaikech/1b47cfec588454963ee40c5a50943194)

[TOP](#top)
