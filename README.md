# Taking Advantage of Google Apps Script (Tanaike's list)

<a name="top"></a>
Here, CLI tools, libraries, Reports, Benchmarks and Sample Scripts for taking advantage of Google Apps Script which are publishing in my [blog](https://tanaikech.github.io/), [Gists](https://gist.github.com/tanaikech), [GitHub](https://github.com/tanaikech) and [my answers on Stackoverflow](https://stackoverflow.com/users/7108653/tanaike?tab=answers) are summarized. I hope that you have the chance for knowing the possibilities of Google Apps Script from my contents. If these are useful for you, I'm glad.

Japanese version of this list is [here](https://github.com/tanaikech/taking-advantage-of-google-apps-script/blob/master/Japanese_version/README.md).

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
  - [Form](#form)
  - [YouTube](#youtube)
  - [Chart](#chart)
  - [Analytics](#analytics)
  - [Slack](#slack)
  - [Virtual Currency](#virtualcurrency)
  - [Stackoverflow](#stackoverflow)
  - [Netatmo](#netatmo)
  - [Figma](#figma)
  - [Microsoft](#microsoft)
  - [Etc](#etc)
  - [Node.js](#nodejs)
  - [Golang](#golang)
  - [Python](#python)
  - [Curl](#curl)
  - [Javascript](#javascript)
  - [PHP](#php)
  - [Generative AI](#generativeai)

<br>
<br>

<a name="news"></a>

# News

- **December 13, 2023:** [Drive API v3 has been released to Advanced Google services](https://tanaikech.github.io/2023/12/13/drive-api-v3-has-been-released-to-advanced-google-services/)
- **August 12, 2023:** [My report has been featured in Google Workspace Developer Newsletter on July 2023](https://tanaikech.github.io/2023/08/12/my-report-has-been-featured-in-google-workspace-developer-newsletter-on-july-2023/)
- **June 11, 2023:** [My report has been published at Champion Innovators Content Library and Google Cloud Medium Publication](https://tanaikech.github.io/2023/06/11/my-report-has-been-published-at-champion-innovators-content-library-and-google-cloud-medium-publication/)
- **May 21, 2023:** [My report has been published at Champion Innovators Content Library and Google Cloud Medium Publication](https://tanaikech.github.io/2023/05/21/my-report-has-been-published-at-champion-innovators-content-library-and-google-cloud-medium-publication/)
- **May 16, 2023:** [My report has been published at Champion Innovators Content Library and Google Cloud Medium Publication](https://tanaikech.github.io/2023/05/16/my-report-has-been-published-at-champion-innovators-content-library-and-google-cloud-medium-publication/)
- **April 20, 2023:** [My report "Enriched Management of Rich Text on Google Spreadsheet using Google Apps Script" has been published at Champion Innovators Content Library](https://cloud.google.com/innovators/champions/content#/?q=tanaike)
- **January 31, 2023:** [My report has been published at Champion Innovators Content Library](https://tanaikech.github.io/2023/01/31/my-report-has-been-published-at-champion-innovators-content-library/)
- **November 15, 2022:** [My report has been featured by Google Workspace Developer Newsletter](https://tanaikech.github.io/2022/11/15/my-report-has-been-featured-by-google-workspace-developer-newsletter/)
- **November 3, 2022:** [My report has been published at Champion Innovators Content Library](https://tanaikech.github.io/2022/11/03/my-report-has-been-published-at-champion-innovators-content-library/)
- **October 3, 2022:** [My report has been published on the Blog of Google Cloud](https://tanaikech.github.io/2022/10/03/my-report-has-been-published-on-the-blog-of-google-cloud/)
- **September 6, 2022:** [My report has been published at Champion Innovators Content Library](https://tanaikech.github.io/2022/09/06/my-3-reports-have-been-published-at-champion-innovators-content-library/)
- **August 17, 2022:** [My report has been published at Champion Innovators Content Library](https://tanaikech.github.io/2022/08/24/my-report-has-been-published-at-champion-innovators-content-library/)
- **June 2, 2022:** [Embed content as a full page in new Google Sites](https://tanaikech.github.io/2022/06/02/embed-content-as-a-full-page-in-new-google-sites/)
- **April 14, 2022:** [Updating Script Editor of Google Apps Script](https://tanaikech.github.io/2022/04/14/updating-script-editor-of-google-apps-script/)
- **March 17, 2022:** [Finally, Google Forms API has been officially released as version 1](https://tanaikech.github.io/2022/03/17/finally-google-forms-api-has-been-officially-released-as-version-1/)
- **March 10, 2022:** [Bug of Create Method of Google Forms API was Removed](https://gist.github.com/tanaikech/dbabd43df594d27cdd1ecc69a7badb52)
- **January 22, 2022:** [On January 19, 2022, 2 Classes of 'CellImageBuilder' and 'CellImage' have been added to Spreadsheet Service](https://tanaikech.github.io/2022/01/22/on-january-19-2022-2-classes-of-cellimagebuilder-and-cellimage-have-been-added-to-spreadsheet-service/)
- **December 9, 2021:** [Google Forms API now available in open beta](https://tanaikech.github.io/2021/12/09/google-forms-api-now-available-in-open-beta/)
- **December 9, 2021:** [[Fixed] Google Apps Script Web App HTML form file-input fields not in blob compatible format](https://tanaikech.github.io/2021/12/09/fixed-google-apps-script-web-app-html-form-file-input-fields-not-in-blob-compatible-format/)
- **October 16, 2021:** [Announcing the Google Forms API](https://tanaikech.github.io/2021/10/16/announcing-the-google-forms-api/)
- **October 14, 2021:** [Google Cloud Innovators Champions](https://tanaikech.github.io/2021/10/14/google-cloud-innovators-champions/)
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

> At Stackoverflow, a lot of people post questions and answers to the questions every day. There are various tags in Stackoverflow. A lot of discussions are performed at each tag. Their discussions bring important information and are much useful for a lot of people. As one of the tags, there is "google-apps-script". I sometimes discuss the questions with that tag. When we see the discussions, we can notice that the discussions are changed and progressed over time, because "Google Apps Script" which is the origin of the tag is updated. This report thinks this change is the trend of the tag of "google-apps-script". This trend includes the number of questions, questioners, answerers, and tags added to the tag of "google-apps-script". The trend of the tag of "google-apps-script" is deeply related to the progression of Google Apps Script and the various applications for Google Apps Script. In this report, as one of several approaches, the trend of Google Apps Script was investigated by statistically analyzing all questions with the tag of "google-apps-script". As the result, it was found that by investigating all questions with the tag "google-apps-script", the tags added to this main tag strongly affected the trend of the tag "google-apps-script". Also, the possibility which can estimate the future trend by investigating the tags added to the tag of "google-apps-script" was indicated.

- [Trend of google-apps-script Tag on Stackoverflow 2019](https://gist.github.com/tanaikech/4e4f1ca20b8dbce08f87289db415df7d)

- [Trend of google-apps-script Tag on Stackoverflow 2020](https://gist.github.com/tanaikech/fd7dbc6d630fd0550c32159635cecc96)

- [Trend of google-apps-script Tag on Stackoverflow 2021](https://gist.github.com/tanaikech/18519c3177e284638dce9113ec7ab5b1)

- [Trend of google-apps-script Tag on Stackoverflow 2022](https://gist.github.com/tanaikech/e258f30182fdd6609d94d87805914caa)

- [Trend of google-apps-script Tag on Stackoverflow 2023](https://gist.github.com/tanaikech/526e5aaed047ca54ece491a2f465f923)

- [Trend of google-apps-script Tag on Stackoverflow 2024](https://gist.github.com/tanaikech/7efec2c872fe2db57539a002d5d25875)

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
- [HtmlFormApp](https://github.com/tanaikech/HtmlFormApp) : This is a Google Apps Script library for parsing the form object from HTML form and appending the submitted values to the Spreadsheet.
- [DocNamedRangeApp](https://github.com/tanaikech/DocNamedRangeApp) : This is a Google Apps Script library for managing the named range on Google Documents.
- [RichTextAssistant](https://github.com/tanaikech/RichTextAssistant) : This is a GAS library for supporting editing RichText in Google Spreadsheet using Google Apps Script.
- [UtlApp](https://github.com/tanaikech/UtlApp) : This is a Google Apps Script library including useful scripts for supporting to development of applications by Google Apps Script.
- [TemplateApp](https://github.com/tanaikech/TemplateApp) : This is a Google Apps Script library for easily managing the template of Google Documents and Google Slides using Google Spreadsheet as a database using Google Apps Script.
- [TriggerApp](https://github.com/tanaikech/TriggerApp) : This is a Google Apps Script library for efficiently managing the time-driven triggers for executing Google Apps Script using Google Apps Script.
- [PDFApp](https://github.com/tanaikech/PDFApp) : This is a Google Apps Script library for managing PDFs.
- [ScriptHistoryApp](https://github.com/tanaikech/ScriptHistoryApp) : This is a Google Apps Script library for managing the histories of the Google Apps Script project.
- [MicrosoftDocsApp](https://github.com/tanaikech/MicrosoftDocsApp) : This is a Google Apps Script library for using Microsoft Docs files (Word, Excel, and PowerPoint files) using [Document service](https://developers.google.com/apps-script/reference/document), [Spreadsheet service](https://developers.google.com/apps-script/reference/spreadsheet), and [Slides Service](https://developers.google.com/apps-script/reference/slides) of Google Apps Script.
- [CorporaApp](https://github.com/tanaikech/CorporaApp) : This is a Google Apps Script library for managing the corpora of Gemini API.
- [ImageBotApp](https://github.com/tanaikech/ImageBotApp) : This is the image bot using Gemini with Google Apps Script and Google Drive.
- [GoogleApiApp](https://github.com/tanaikech/GoogleApiApp) : This is a Google Apps Script library for supporting to use Google APIs with Google Apps Script.
- [GeminiWithFiles](https://github.com/tanaikech/GeminiWithFiles) : A new Google Apps Script library called GeminiWithFiles simplifies using Gemini, a large language model, to process unstructured data like images and PDFs. GeminiWithFiles can upload files, generate content, and create descriptions from multiple images at once. This significantly reduces workload and expands possibilities for using Gemini.

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
- [GetAccessTokenFromServiceAccount_js](https://github.com/tanaikech/GetAccessTokenFromServiceAccount_js) : This is a Javascript library to retrieve the access token from the Google Service Account.
- [Javascript Library for Cropping Image by Border](https://github.com/tanaikech/CropImageByBorder_js) : This is a Javascript library for cropping images by the border.

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

### [Concurrent Writing to Google Spreadsheet using Form](https://gist.github.com/tanaikech/c2f3fccabbf4906a18fdc38463982f31)

> When the users try to write to Spreadsheet using a form, the developers have to consider to the concurrent submission from the form. For example, when the multiple users submit the data with the form simultaneously, all data are possibly not to be saved to the Spreadsheet. So it is considered that it is important to know the information about the concurrent writing to Google Spreadsheet using a form. In this report, such situation was investigated.

> As the result, when the success rate for writing concurrently to Google Spreadsheet is investigated, it was found that the concurrent writing with Google Form is suitable rather than Web Apps created by Google Apps Script. The threshold number of users for succeeding to write all data to Spreadsheet was 35 for Google Form and 26 for Web Apps, respectively. And, when Web Apps is used, it was also found that Lock Service was definitely required to be used for the multiple submission.

### [Large Decimal Numbers and Exponential Notation for Google Spreadsheet](https://gist.github.com/tanaikech/a1b32bdace0ebdd6c92a547b6f4dfbeb)

> In this report, it has investigated the large decimal numbers and the exponential notation for Google Spreadsheet. When the large decimal numbers are put to the Spreadsheet, the Spreadsheet automatically sets the display value using the exponential notation. In this report, the result when the values are retrieved by Spreadsheet service and Sheets API is shown.

### [Report: Images put with IMAGE function on Google Spreadsheet](https://gist.github.com/tanaikech/10c55451caab9e291d5a571b157e8020)

> This is a report about images put with "=IMAGE(IMAGE_URL)" function on Google Spreadsheet.

> When "=IMAGE(IMAGE_URL)" is put to a cell "A1" on Spreadsheet, the image is shown in the cell. For this situation, when the cell "A1" is copied with "range.copyTo(range, { contentsOnly: true })", the formula is removed and an image can be seen. I thought that when the image of the URL is removed, how are those images. In this report, such a situation was investigated.

### [Occurring and Resolving Infinite Loop on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/c385bed8f037d67b154d9c0c8ff7a341)

> Here, I would like to introduce a report for occurring and resolving the infinite loop on Google Spreadsheet using Google Apps Script. I have reported this to Google issue tracker.

### [Applicating Spread Syntax and Destructuring assignment to Google Spreadsheet with Google Apps Script](https://gist.github.com/tanaikech/d0c60aa54fb55fc61a06593e311fa623)

> In this report, I would like to introduce to apply the spread syntax and the destructuring assignment to Google Spreadsheet with Google Apps Script. The destructuring assignment can be used without V8 runtime. But, the spread syntax is required to be used with V8 runtime. Recently, I often saw the script using them at Stackoverflow. And also, I have sometimes gotten the questions related to the spread syntax and the destructuring assignment. So, I thought that I would like to introduce in my blog.

### [Report: Handling 10,000,000 cells in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/cc4380692790150cc090114553e38a0e)

> On March 14, 2022, it reported about "Google Sheets doubles cell limit". [Ref](https://workspaceupdates.googleblog.com/2022/03/ten-million-cells-google-sheets.html) By this update, now, the users can use 10,000,000 cells in a Google Spreadsheet. This is great news for us. When I tried to handle 10,000,000 cells in a Google Spreadsheet using Google Apps Script, it was found that there were various important points. In this report, I would like to introduce the important points for handling 10,000,000 cells in Google Spreadsheet using Google Apps Script.

### [Report: Obtaining Values from GOOGLEFINANCE using Google Apps Script](https://gist.github.com/tanaikech/7bebb7c6d8ed6ddfdd825153ef71c47e)

> This is a report for obtaining the values from GOOGLEFINANCE using Google Apps Script. When I tested to retrieve the values from `GOOGLEFINANCE` function on Google Spreadsheet using Google Apps Script, I noticed that the values can be retrieved.

### [Report: Publishing Various Google Docs with Same URL using Google Apps Script](https://gist.github.com/tanaikech/94810f7947361bef398ac9f301b9afde)

> This is a sample method for publishing various Google Docs files with the same URL using Google Apps Script.

> By updating on May 25, 2022, the content got to be able to be embedded as a full page in the new Google site. [Ref](https://tanaikech.github.io/2022/06/02/embed-content-as-a-full-page-in-new-google-sites/) In this method, this is used.

### [Report: Recent Value of ScriptApp.getService().getUrl() in Google Apps Script](https://tanaikech.github.io/2022/06/11/report-recent-value-of-scriptapp.getservice.geturl-in-google-apps-script/)

### [Report: Documentation Comments including JsDoc for Functions of Google Apps Script](https://gist.github.com/tanaikech/5615cfc34e1d41659e934a7bcbaa27cf)

> This is a report for the documentation comments for the functions of Google Apps Script.

> When the documentation comments for functions of Google Apps Script are considered, you will think JsDoc. At Google Apps Script, a part of JsDoc can be used. But, in this report, I would like to introduce the documentation comments including JsDoc.

### [Report: Management of Images on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/7ecb785ab9d4418d0c48ea853df8d1c8)

> This is a report for management of images on Google Spreadsheet using Google Apps Script.

> At October 30, 2018, Cass OverGridImage and the method of inserImage have been added to Spreadsheet Service. At January 19, 2022, Class CellImageBuilder and Class CellImage have been added to Spreadsheet Service. By these Classes and methods, the images got to be able to be managed on Google Spreadsheet. But, when the image is used to the various situations, there are the cases that it is required to ingenuity to manage the images. So, in this report, I would like to introduce the management of images on Google Spreadsheet using the sample scripts of Google Apps Script.

### [Report: Challenging Exporting Selected Cells on Spreadsheet as Image using Google Apps Script and Javascript](https://gist.github.com/tanaikech/fbf47fe7b8e3e57ee49f24563550c113)

> This is a report for challenging exporting the selected cells on Spreadsheet as an image using Google Apps Script and Javascript.

### [Report: Efficiently Creating Web Apps using a Google Apps Script library](https://gist.github.com/tanaikech/90ac88cf1a74989e649a4e49a5ed1ab9)

> This is a sample script for efficiently creating Web Apps using a Google Apps Script library.

> When a Google Apps Script library is used for creating Web Apps, the following advantage can be obtained.

> - The script of the client-side can be simpler. Because most scripts for constructing Web Apps are included in the Google Apps Script library.
> - When the script of Web Apps (In this case, the script of Google Apps Script library is modified.) is modified, the latest script is reflected in the Web Apps, immediately. Because when the Google Apps Script library is used as the latest version when the script of the library is modified, the client can use the latest script of the library, immediately. So, the downtime of Web Apps can be reduced.
>   - By this, it is not required to manually reflect the latest version of the script to the Web Apps.
> - When you can change the script of Web Apps by changing the deployed version of the library.

### [Report: Process Cost of Google Apps Script During Large Calculations by Formulas on Google Spreadsheet](https://gist.github.com/tanaikech/455ae803fae6a9aba31a928ce5a16c1d)

### [Report: Rule of Item IDs for Questions of Google Forms](https://gist.github.com/tanaikech/f391fd4d596d45bb846d374ff0ded695)

### [Report: Implementing Pseudo 2FA for Web Apps using Google Apps Script](https://gist.github.com/tanaikech/7a15164b1227e2ec2231fce24ae9daf2)

> In Google Apps Script, there is the Web Apps. When Web Apps is used, the users can execute Google Apps Script using HTML and Javascript. This can be applied to various applications. When the Web Apps is deployed with "Anyone", anyone can access the Web Apps. And, there is the case that Web Apps deployed with "Anyone" is required to be used. Under this condition, when 2 Factor Authentication (2FA) can be implemented, it is considered that the security can be higher and it leads to giving various directions for the applications using Web Apps. In this report, I would like to introduce the method for implementing the pseud 2FA for Web Apps deployed with “Anyone” using Google Apps Script.

### [Best Practices for Discontinuous Cells on Google Spreadsheet by Google Apps Script](https://gist.github.com/tanaikech/dba916ae25f7351819e062b42bb5be10)

> It has already been known that Google Apps Script is a strong tool for managing Google Spreadsheets. When the values are retrieved and/or put for Google Spreadsheet, there is a case that the discontinuous cells are required to be used. This report suggests the Best Practices for processing the discontinuous cells on Google Spreadsheet. From the results of process costs, it could understand the usefulness of using the discontinuous cells with low cost using Sheets API and Class RangeList of Spreadsheet service with Google Apps Script.

### [Report: Specification of Properties Service for Google Apps Script](https://gist.github.com/tanaikech/8b057d10fb5f2af014794e57b021c6aa)

> In this report, the detailed specification of PropertiesService has been investigated. It is considered that knowing this specification will be useful for developing applications with Google Apps Script. As a result, it was found that the maximum key and value sizes are 524,287 bytes with a 1-byte key and 8,066 bytes, respectively. And also, it was found that the maximum size of PropertiesService is required to be considered with both the key and value sizes.

### [Report: Easily Implementing HTML Form with Google Spreadsheet as Database using Google Apps Script](https://gist.github.com/tanaikech/7dcadf189d9bdfd7dc0ae330ab0d84f5)

> This report introduces the method for easily implementing HTML forms with a Google Spreadsheet as a database using Google Apps Script. There are 2 patterns for the HTML form using Google Apps Script. One is that an HTML form is put into the same Google Apps Script project. Another is that an HTML form is put to a different server from a Google Apps Script project. In this report, the methods for easily implementing both patterns are introduced using the sample scripts.

### [Trend of google-apps-script Tag on Stackoverflow in first half of 2023](https://gist.github.com/tanaikech/ef5a26a092a0e3b47aced170ead74be9)

> Recently, I felt a change like never before in the questions on Stackoverflow. In order to confirm this, in this report, the trend of "google-apps-script" tag on Stackoverflow in the first half (January 1st to June 1st) of 2023 has been investigated. From this report, in 2023 when the affection of COVID-19 has been reduced socially, the appreciable trend was confirmed to the questions including a tag of "google-apps-script". It is guessed that the origin of this appreciable trend is due to AI chatbots. The appearance of AI chatbots might give us a phase of major change to the method for understanding the statistical data obtained from online sites.

### [Understanding Flow of Request to Web Apps Created by Google Apps Script](https://gist.github.com/tanaikech/131ba814a1f6012fd6a5ffe11789971f)

> Here, I would like to introduce a report for understanding the flow of the request to Web Apps created by Google Apps Script. There might be a case that various applications using the Web Apps are created and the Web Apps are used as the webhook. In that case, it is considered that when you have understood the flow of requests to the Web Apps, your goal might be able to be smoothly achieved. In this report, I would like to introduce the information about it.

### [Report: Values to transfer between Javascript and Google Apps Script with google.script.run](https://gist.github.com/tanaikech/9927dc5c12ebca118ff8f3f4d539c95d)

> This report introduces the values that can be used for transferring between HTML and Google Apps Script with google.script.run.

### [Taking Advantage of Auto-completion of Script Editor for Google Apps Script](https://gist.github.com/tanaikech/b2f0461c1060b54d2edbd43733708f52)

> This is a report for taking advantage of the auto-completion of the script editor for Google Apps Script.

### [Report: How to Run Google Apps Script](https://gist.github.com/tanaikech/f03ab0d9eff7182a57e699fb3fbb32b8)

> Google Apps Script is one of the strong tools with cloud computing, and it is very useful for various situations. Google Apps Script can be run by various methods. This report introduces how to execute Google Apps Script.
> Recently, generative AI has given a lot of new users a chance to use Google Apps Script. If this report helps the users develop applications using Google Apps Script, I'm glad.

### [Dining Reservation System using Google Apps Script](https://github.com/tanaikech/ReservationApp)

> This is the dining reservation system using Google Apps Script.

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

### [Benchmark: Concurrent Writing to Google Spreadsheet using Form](https://gist.github.com/tanaikech/c2f3fccabbf4906a18fdc38463982f31)

### [Benchmark: Process cost for HTML Template using Google Apps Script](https://gist.github.com/tanaikech/f1436d88423077115d2c249862f12f17)

> When we use HTML in the Google Apps Script project, in order to show the values from the Google Apps Script side, the HTML template is used. When I used the HTML template with a large value, I understood that the process cost can be reduced by devising a script. In this report, I would like to introduce the process cost of the HTML template using the benchmark.

> As the result, it was clearly found that when an HTML table is created with Google Apps Script and shows the HTML table with the HTML template, the process cost becomes low. And also, it was found that in order to reduce the process cost for using the HTML template, it is required to prepare the HTML data with the Google Apps Script side.

### [Benchmark: Process cost for Parsing XML data using Google Apps Script](https://gist.github.com/tanaikech/d09fb02c93635c53312aff58a047eb13)

> In order to retrieve the values from XML data, when XML data is parsed using Google Apps Script, there are several methods for parsing the data. Class XmlService, which is a built-in Class for managing XML data, might be the first way to come up with it. At Stackoverflow, it is posted questions that XML data is often parsed using Class XmlService. It is considered that Class XmlService is suitable for managing XML data.

> But, when I have created applications using XML data with Google Apps Script before, I have felt that the process of Class XmlService might be high. So, in this report, the process cost for parsing XML data using Google Apps Script. As the result, it was found that after the V8 runtime had been released, the methods except for Class XmlService in order to parse XML data can be also used.

### [Benchmark: High-Efficiency Finding and Replacing Many Values in Google Spreadsheet with Low Process Cost using Google Apps Script](https://gist.github.com/tanaikech/6fc2f3ea6d09ce2906e7922c76c0b238)

> This is a sample script for high-efficiency finding and replacing many values in Google Spreadsheet with the low process cost using Google Apps Script.

> When the various values are replaced in Google Spreadsheet using Google Apps Script, I'm worried about the process cost. So, in this report, I would like to introduce a sample script for high-efficiency achieving this.

> As the result, using a sample situation, when the process cost of the sample script using Sheets API is compared with that of the sample script using Spreadsheet services (SpreadsheetApp), it was found that the above script using Sheets API could reduce the process cost by about 70 % from the script using Spreadsheet service.

### [Benchmark: Process Costs for Checking Value in Array using Google Apps Script](https://gist.github.com/tanaikech/b7df3cd77a933dba247670f5eda15e4b)

> There is a maximum executing time for Google Apps Script (GAS). That is 6 minutes. And, in the case of the custom function and the simple trigger, it is 30 seconds. So users always have to pay attention to reducing the process cost of the scripts. Especially, it is very important to know the process costs for the array processing, because array processing is often used for spreadsheets and Google APIs. I have already reported about the array processing at "Benchmark: Loop for Array Processing using Google Apps Script with V8" and "Search for Array Processing using Google Apps Script". In this report, the process cost checking a value in a one-dimensional array using Google Apps Script has been investigated.

### [Benchmark: Process Costs for Searching Value using Object with Google Apps Script](https://gist.github.com/tanaikech/e4fcca733a78f7211d80967ac4a35adb)

> When a value is searched from the 1-dimensional array and a 2-dimensional array, after V8 runtime could be used, I use JSON object, Set object, and Map Object. But, I had never measured the process cost of this situation. In this post, I would like to introduce the process cost for searching a value using a JSON object, Set object, and Map object converted from the 1-dimensional array and 2-dimensional array.

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
- [Retrieving Files of 'Shared with Me' in Specific Folder using Google Apps Script](https://gist.github.com/tanaikech/ddebdc6c32937cbe2a525991398f066c)
- [Workaround: createdDate cannot be used with searchFiles of DriveApp in Google Apps Script](https://gist.github.com/tanaikech/2b9d86a7db01f72e88090116cb5fee1f)
- [Workaround: Checking Existence of File ID in Google Drive without Access token and API key](https://gist.github.com/tanaikech/ef51e36e53c5e49d2a8dc3736e8a9386)
- [Retrieving Specific Folders from Google Drive using Google Apps Script](https://gist.github.com/tanaikech/5be73060a7941d73ce7179c6fa77206a)
- [Transferring Owner of File to Other User using Google Apps Script](https://gist.github.com/tanaikech/685929fd4e739c943ab0b4c53348a4af)
- [Retrieving Total File Sizes in Specific Folder of Google Drive using Google Apps Script](https://gist.github.com/tanaikech/bbf37f05f5f5a98d346295f6e4aa3c48)
- [Folder Picker using jsTree with Google Apps Script and Javascript](https://gist.github.com/tanaikech/10edba76a0273c71368b3699d5f64b62)
- [Comparing File Contents of Files on Google Drive using Google Apps Script](https://gist.github.com/tanaikech/ed64668e23c155138baa300a31d7f16f)

<a name="projects"></a>

#### Projects

- [Retrieving ClientId using Google Apps Script](https://gist.github.com/tanaikech/4656b1b01128d27f291cee317553ea6d)
- [Copying and Overwriting GAS Project](https://gist.github.com/tanaikech/3e7608bd8ba87dd6019aedbd09224bd3)
- [Remove Third-party Apps with Account Access using Google Apps Script](https://gist.github.com/tanaikech/608e65fee105989df1a7b645c20572c2)
- [Retrieving Reformatted Scripts without Comments in a Project using Google Apps Script](https://gist.github.com/tanaikech/61f69fd2ce181865d3430c260c6a5d0b)
- [Backup Project as zip File using Google Apps Script](https://gist.github.com/tanaikech/035aa9f6603e7a8698c1cc67ab43e132)
- [Full-text search of Google Apps Script Projects using Google Apps Script](https://gist.github.com/tanaikech/d557d3e239189877e595ed622ce2cb88)
- [Managing History of Google Apps Script](https://gist.github.com/tanaikech/2453685e8e6b272e357b1f5935ca6e53)

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
- [Retrieving Hidden Rows and Showing Rows by Filter View on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/43eee17899a3d0a99817f3a2032ae937)
- [Compiling Continuous Numbers using Google Apps Script](https://gist.github.com/tanaikech/5a43281964b739ead2b7ae2401400630)
- [Taking Advantage of TextFinder for Google Spreadsheet](https://gist.github.com/tanaikech/39f719bd10ccbb27edd694c33242e496)
- [Converting Values of Google Spreadsheet to Object using Google Apps Script](https://gist.github.com/tanaikech/39d6402846c21502d41ecc7f78708e71)
- [Updating Values of Sheet A with Values of Sheet B using Google Apps Script](https://gist.github.com/tanaikech/bd1e9de7cc22f89d3c8c7f90bf07e943)
- [Letting Users Running Google Apps Script on Google Spreadsheet without both Authorizing Scopes and Showing Script](https://gist.github.com/tanaikech/82089f55e9e647bbe965a563ab1ce657)
- [Converting Range ID to Range Object on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/3aa69f1a8e2a944c7df926879fa0f34e)
- [Retrieving Data from Content-Type of 'text/event-stream' using Javascript and Google Apps Script](https://gist.github.com/tanaikech/2ba5f847ae6032d1611875d60cdf79b2)
- [Pseudo OnEdit Trigger for Google Spreadsheet without Simple and Installable Triggers using Google Apps Script](https://gist.github.com/tanaikech/05d9922a947232dbda5143b6ac6dc71f)
- [Checking whether Cells on Google Spreadsheet have Checkboxes using Google Apps Script](https://gist.github.com/tanaikech/763ac2328d60805a3f971537e8b6e7c3)
- [Inverting Selected Ranges on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/c08b9ea7a0f54b3e6074bba510e1efb4)
- [Detecting Operations to Google Spreadsheet by Owner, Specific Users, and Anonymous Users using Google Apps Script](https://gist.github.com/tanaikech/4c0067b5faec34e4c8a4b8d24a9350e5)
- [Importing CSV Data by Keeping Number Formats of Cells on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/909863d8807c9143f4814aa270afe02e)
- [Workaround for Inserting Non-public image of Google Drive using IMAGE Function in a Cell on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/80c1cd268c303edcbd5483211a1b9ea4)
- [Counter in Cell of Google Spreadsheet using Infinite Loop with Google Apps Script](https://gist.github.com/tanaikech/efffc9233aba43922aae6cc93329075d)
- [Merging Columns with Same Header Title in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/41e62d17ca48a5b2f3f57e5e06ea8da0)
- [Merging Rows with Same Header Title in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/89e8825f31f65621332634dcbe9cf503)
- [Merging Rows with Same Header Title in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/89e8825f31f65621332634dcbe9cf503)
- [Increasing Column Letter by One using Google Apps Script](https://gist.github.com/tanaikech/13fc8683114c5ff62b8144c338a1d574)
- [Number of Requests for Sheets API using Google Apps Script](https://gist.github.com/tanaikech/dad5df2403b551f6bdd99221be115bef)
- [Expanding Rows in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/d5d96ce34846110d67f82147b396b2b7)
- [Retrieving and Parsing XML data from Google Workspace Update Blog and Putting it to Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/0ba501fecdfd1ac9b0f6997b370586b4)
- [Retrieving Text Positions in Text Data using Google Apps Script](https://gist.github.com/tanaikech/77fbac03f26e1c1688f54130a683f8c0)
- [Parsing JSON Data Array by Expanding Header Row using Google Apps Script](https://gist.github.com/tanaikech/d905b75175bd297733f807e7bddd33d4)
- [Replacing Values in Cells on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/cedc350cf36865b7a84e260c78762db9)
- [Parsing XML Data in Google Apps Script using IMPORTXML](https://gist.github.com/tanaikech/f4e6091c1de4873695783471e410f07a)
- [Protecting Cells of Spreadsheet by Clicking Checkbox using Google Apps Script](https://gist.github.com/tanaikech/1da4d8e8ebb2cdc62e6c42c6e71f14d7)
- [Converting A1Notation to GridRange and vice versa using Google Apps Script without any Scopes](https://gist.github.com/tanaikech/457b5545a48890ed6dce66d67324ec47)
- [Removing Invalid Named Ranges from Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/f9b993c4a178291324e03eeb5c161c1d)
- [Checking Exchange Rate using GOOGLEFINANCE with Google Apps Script](https://gist.github.com/tanaikech/67e0cd1f5ba4946aa050963a0720ed5f)
- [Creating User's Dashboard by Inputting Name and Password using Web Apps with Google Apps Script](https://gist.github.com/tanaikech/ac2537711bfcf19348b66b454da33196)
- [Clearing Discrete Cell Values on Multiple Sheets using Google Apps Script](https://gist.github.com/tanaikech/6b1ce61475e35416ce0e728a7fd3018c)
- [Using RichTextValues with Custom Function on Google Spreadsheet](https://gist.github.com/tanaikech/1d63fcd5152688da68e9974167ca744f)
- [Moving Cell Detection on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/5939e3de5e24ce389beade94158bdb7d)
- [Updating Destination Sheet by Source Sheet in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/9970ebf1bd3c7475df57126f5d544f89)
- [Detecting Cells with Quote Prefix in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/a17d291c9d3da8fbce0d100139d3c872)
- [Showing Specific Rows and Columns in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/7573fe1aa0bd4fb3d0a1ff9740496ccc)
- [Retrieving Cell Coordinates of Cells with Quote Prefix using Google Apps Script (Single Quote)](https://gist.github.com/tanaikech/89fb802a5ac04bc627c9b6f77476edd9)
- [Retrieving Named Functions from Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/9a9e571ed662e35eec0aa747bb4e025a)
- [Updating Array1 with Array2 using Google Apps Script](https://gist.github.com/tanaikech/fb7149425069ad1138f36162698385df)
- [Putting Multiple Hyperlinks to a Cell using Sheets API with Google Apps Script and Node.js](https://gist.github.com/tanaikech/4c27bf8d1948a5dfa5b0e53ce88c6d30)
- [Workaround: Detecting to Edit Google Spreadsheet using Sheets API with Service Account](https://gist.github.com/tanaikech/5388797761cb92cf1fe325e939c10b25)
- [Copying and Deleting Dimension Groups in Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/bb50f2e188327afd616bd2678ab0b40f)
- [Rearranging Columns on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/5ca3ed56c36cb7b947e14d5b1dbab6a2)
- [Using OnEdit Trigger to Google Spreadsheet by Hiding Google Apps Script from Other Users](https://gist.github.com/tanaikech/848fea29875d5034a2347a5a16306215)
- [Using OnEdit trigger on Google Spreadsheet Created by Service Account](https://gist.github.com/tanaikech/58891b5caaf49ebfdb5f8dde4637d8e6)
- [Workaround: Retrieving Hyperlink from Cell of Number Value using Google Apps Script](https://gist.github.com/tanaikech/82a74e64abcacabd51be8ff92c73691a)
- [Putting Values of All Spreadsheets in Folder to Master Spreadsheet with Low Process cost using Google Apps Script](https://gist.github.com/tanaikech/e65100d2f13c9c6903e1a6c86184d663)
- [Retrieving Start and End Row Numbers of Same Values in a Column on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/eca18c3ccff32065dbe60d5385dd51ab)
- [Removing Quote Prefix of Cell value using Google Apps Script (Single Quote)](https://gist.github.com/tanaikech/ec156204f3a2d96873dce5f6ba4674d6)
- [Importing Microsoft Excel to Google Spreadsheet using Custom Function with Google Apps Script](https://gist.github.com/tanaikech/742c9f8baf488503a66582b985b9d4e5)
- [Enriched Management of Rich Text on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/8082e2bb265d2ad4bd61f9d418504811)
- [Putting TOTP into Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/4de7448903389e0884e2a21cd27abc86)
- [Workaround: Automatically Installing OnEdit Trigger to Copied Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/76bab12742174976d87e2473ae7975f8)
- [Putting Image into Cell of Spreadsheet using Google Apps Scrip](https://gist.github.com/tanaikech/c18715b68a81a8492a13140d9cd3bb6f)
- [Unpivot on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/05e5fd84561080e484bd4df799862f01)
- [Converting Google Spreadsheet to HTML Table using Google Apps Script](https://gist.github.com/tanaikech/61932a6acfe02e53ce9d5bca9078c536)
- [Converting Relative Reference to Absolute Reference and vice versa of A1Notation on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/d9ae71d8736e168e47c56adb203b7e87)
- [Copying Google Spreadsheet by Removing Container-Bound Script Using Google Apps Script](https://gist.github.com/tanaikech/d5f7b0ddd8c8746c4dff67040a436c5f)
- [Automatically Refreshing Basic Filter on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/03308f87b6c9568dd277e43eb646a75e)
- [Overwrapped Cells on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/b56e12dd1f2f15997b113b4738cf7f8b)
- [Benchmark: Efficiently Deleting Rows by Conditions on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/ef8969755f4a00275be7e8fc93dfc00e)
- [Focusing Selected Cell to Top Left on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/9f613d6fec34892dc211f30644e0a5ea)
- [Copy Date Object between Google Spreadsheets with Different Timezone using Google Apps Script](https://gist.github.com/tanaikech/fd525434b51b8b0df3293c0067f071ca)
- [Workaround: Detecting Change of IMPORTRANGE using OnEdit trigger with Google Apps Script](https://gist.github.com/tanaikech/0cf57b2684c2ac2c2562b1ec229c9ace)
- [Uploading Files without Authorizing Scopes by Shared Users with Dialog on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/dbcf9ba8674b898ee61baf5c33825a0b)
- [Technique for Processing Google Spreadsheet Including Merged Cells using Google Apps Script](https://gist.github.com/tanaikech/a03b0bb4218a19b41d507a5b649e3802)
- [Technique of Array Processing for Custom Functions on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/e3f0bf29aad48d6e2e4ca096269e5a9d)
- [Workaround: Making Users Edit Protected Cells using Google Apps Script](https://gist.github.com/tanaikech/a36770c4609fdb73ed1b8ed43c0612fd)
- [Technique for Managing Rich Text on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/f3aa85e41287e329353ec062e8b64483)
- [Allowing Access by IMPORTHTML, IMPORTDATA, IMPORTFEED, IMPORTXML, and IMPORTRANGE on Google Spreadsheet with Google Apps Script](https://gist.github.com/tanaikech/627d86bdea4028c301431443f82f0ac1)
- [Technique for Protecting Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/3f207ffee7bf64fa79c99118e2979e55)
- [Copying Sheet Including Charts from Google Spreadsheet to Another Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/63f59cee0f2c0c8f24e418ca6b3f868b)
- [Technique for Appending Values to Specific Columns on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/434bef051c136bc87e724b033a478bd2)
- [Identifying Colored Cell Regions in Google Sheets with Google Apps Script](https://gist.github.com/tanaikech/15198f6c6872385b4ed6e85498b82733)
- [Consolidate Scattered A1Notations into Continuous Ranges on Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/1241411538d5b4d90e23a8c5f30d0ea6)
- [Inserting Animated GIFs over Cells on Google Sheets using Google Apps Script](https://gist.github.com/tanaikech/fe3a0fd36ee47685b07ce6db2fbae1ce)

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
- [Replacing Template Texts with Array in Google Document using Google Apps Script](https://gist.github.com/tanaikech/7fc15c4e8ecccbedd469d8d778880834)
- [Retrieving Glyph Value from List Items of Google Document using Google Apps Script](https://gist.github.com/tanaikech/5f186b006c4803790318a75e65900c36)
- [Pseudo OnEdit Trigger for Google Document using Google Apps Script](https://gist.github.com/tanaikech/f27d427f07b20ca9fedec21e643c4a3e)
- [Report: Inserting Multiple Paragraphs to Google Document in Order using Google Docs API](https://gist.github.com/tanaikech/6aa646691f6c2224202fa6fb756e3862)
- [Retrieving Summary of Google Document using Google Apps Script](https://gist.github.com/tanaikech/b61ec85a5f0fb4f5a9157fb9f7bd0e84)
- [Replacing Multiple Paragraphs on Google Document with a Regex using Google Apps Script](https://gist.github.com/tanaikech/f32f878c6cc005bbbdec2d9c635fae7b)
- [Retrieving Values of Dropdown List of Smart Chips on Google Document using Google Apps Script](https://gist.github.com/tanaikech/37a8498ecb392e8b23041ce238287e27)
- [Replacing Images on Google Document in Order using Google Apps Script](https://gist.github.com/tanaikech/1f3407674aafcba906a3528e7ec3463d)
- [Updating Same Position on Google Document using Google Apps Script](https://gist.github.com/tanaikech/36a2a9d393f42274a833e5660bfe4ce0)
- [Converting Large images to Google Document by OCR using Google Apps Script](https://gist.github.com/tanaikech/d4efe1c07b99807f63fe7d5c058c0628)
- [Removing Vertical Borders of Table in Google Document using Google Apps Script](https://gist.github.com/tanaikech/811c4f6965346b95b3c507e1feb83177)
- [Retrieving Values of Calendar Events of Smart Chips on Google Document using Google Apps Script](https://gist.github.com/tanaikech/a130a87830ffbde46f160401787e1dff)
- [Set Line Space of Paragraph on Google Document using Google Apps Script](https://gist.github.com/tanaikech/ea68371c1f212d316a8713946e9d8385)
- [Inserting Paragraphs with Checkboxes in Google Documents using Google Apps Script](https://gist.github.com/tanaikech/dec8cf3755e3c2cf294655c605fd6840)
- [Workaround: Exporting Google Documents as HTML with Image Hyperlinks](https://gist.github.com/tanaikech/e6bbb3bf341d7ac021f3bcfa523c4ca3)
- [Managing Footnotes on Google Documents using Google Apps Script](https://gist.github.com/tanaikech/cd7bf2ca7b9109e081bd64ec50db54fc)
- [Convert Soft Breaks to Hard Breaks on Google Documents using Google Apps Script](https://gist.github.com/tanaikech/7de3ed734ac9b103631c3a20452dca74)

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
- [Simply Editing Texts of Texts Boxes on Google Slides using Google Apps Script](https://gist.github.com/tanaikech/aa0a03ba3c440ca72fc1d7e02f038f7c)
- [Reducing Table Height of Table Inserted from Google Spreadsheet to Google Slides using Google Apps Script](https://gist.github.com/tanaikech/659f3687f4ea5282f39ebf9b6d5ae54c)
- [Exporting All Thumbnail Images Retrieved from Google Slides as Zip File using Google Apps Script](https://gist.github.com/tanaikech/66a83c01e1f99829a85f909f8facb834)
- [Inverting Selected Objects on Google Slides using Google Apps Script](https://gist.github.com/tanaikech/8eb87e6499631a79dade7d4f83e372f7)
- [Managing Row Height and Column Width of Table on Google Slides using Google Apps Script](https://gist.github.com/tanaikech/f24abc8e19f525fd4078bdb9762f431b)

<a name="gmail"></a>

#### Gmail

- [How to Retrieve Replied Emails for Gmail](https://gist.github.com/tanaikech/a047e5f67f30b93482986039daa16dbc)
- [Adding a Label to a Message using Message ID for Gmail](https://gist.github.com/tanaikech/69c7daf910fdad0d6a296ea19f612089)
- [Sending Gmail with Title and Body Including Emoji using Google Apps Script](https://gist.github.com/tanaikech/187863d97d2b5e60938d8316574a2850)
- [Sending Multiple Emails using Batch Request with Gmail API using Google Apps Script](https://gist.github.com/tanaikech/44e055214ab470c9b3143a469d7a7d21)
- [Converting Gmail Message to Image using Google Apps Script](https://gist.github.com/tanaikech/12a61cb7e4516acc95ecf15287b3f0f3)
- [Searching Gmail Messages by Gmail Filters using Google Apps Script](https://gist.github.com/tanaikech/bc8788c65afeba42ec2e560bfa5eb8b2)
- [Flexible Labeling for Gmail using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/cdfa63b670b223e482e457703b9cdeb6)

<a name="calendar"></a>

#### Calendar

- [Running Google Apps Script by Event Notification from Google Calendar](https://gist.github.com/tanaikech/fbbfaa8f2a8a770424974aa16b9b6f3b)
- [Retrieving Event ID from Event URL of Google Calendar using Google Apps Script](https://gist.github.com/tanaikech/b366be5995be04f689c3d80b18363f5e)
- [Managing A Lot Of Google Calendar Events using Batch Requests with Google Apps Script](https://github.com/tanaikech/Managing-A-Lot-Of-Google-Calendar-Events-using-Batch-Requests-with-Google-Apps-Script)
- [Sample Scripts for Creating New Event with Google Meet Link to Google Calendar using Various Languages](https://gist.github.com/tanaikech/94791d48823e9659aa376cf7f0161d9b)

<a name="form"></a>

#### Form

- [Directly Submitting Answers to Google Form using Google Apps Script](https://gist.github.com/tanaikech/b4a31a51cbb0ef84c871e6fb96e1502e)
- [Putting All Response Values from Google Form to Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/42ac2d72f62f2107b965f53239c2f398)
- [Using Google Forms API with Google Apps Script](https://gist.github.com/tanaikech/bac38226e863a398f55b5c3d817d86ed)
- [Creating Quizzes in Google Form using Google Forms API with Google Apps Script](https://gist.github.com/tanaikech/eebcb2d71eed1aab5decff64287bcc9a)
- [Creating Quizzes in Google Form using Google Forms Service with Google Apps Script](https://gist.github.com/tanaikech/3e131b55c7947ced19a3dd99410367eb)
- [Analyzing Responses from Grid Items of Google Form using Google Apps Script](https://gist.github.com/tanaikech/97c3cfd5c6e393de6a16ff6465300e4d)
- [Opening and Closing Google Forms on Time using Google Apps Script](https://gist.github.com/tanaikech/84bd91f2927d8c8463b494f712eb1800)

<a name="youtube"></a>

#### YouTube

- [Uploading Movie File on Google Drive to YouTube using Google Apps Script](https://gist.github.com/tanaikech/dc62aeb9a363513d6d27baf119ecfc2d)
- [Retrieving subscriberCount of Channel from Video URLs of YouTube using Google Apps Script](https://gist.github.com/tanaikech/e3b4ac87437a3f358e0577c5854e00a6)
- [Curl Command Uploading Video File to YouTube with Resumable Upload using YouTube API](https://gist.github.com/tanaikech/5f3ce2d002e1b8e5916821ecc1dacbdc)
- [Uploading Video File on Google Drive to YouTube with Resumable Upload using Google Apps Script](https://gist.github.com/tanaikech/e41b1a674f0c3912aa7c29aac28a57cd)

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

<a name="microsoft"></a>

#### Microsoft

In this case, the APIs and resources of Microsoft are used with Google Apps Script.

- [OnedriveApp](https://github.com/tanaikech/OnedriveApp) : This is a library of Google Apps Script for using Microsoft OneDrive.
- [Retrieving List of All Emails of Microsoft Account using Google Apps Script](https://gist.github.com/tanaikech/45a5511cf2a4a42660b52b3409f7b537)
- [Sending Outlook Emails using Microsoft Account with Google Apps Script](https://gist.github.com/tanaikech/0745889227e43c385d190385fff91598)

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
- [Executing Function with Minutes timer in Specific Times using Google Apps Script](https://gist.github.com/tanaikech/6608e901272077cbc3738366ec5fe0b3)
- [Converting from String to Hex, from Hex to Bytes, from Bytes to String using Google Apps script](https://gist.github.com/tanaikech/707b2cd2705f665a11b1ceb2febae91e)
- [Simple Method for using ggsrun](https://gist.github.com/tanaikech/695f7016b04e4c4156ad928e9482ead9)
- [Simply Converting HTML to Plain Text using Google Apps Script](https://gist.github.com/tanaikech/2779ee59a199011e3f48a1fa92879a68)
- [Reducing Image Data Size using Google Apps Script](https://gist.github.com/tanaikech/14c863e225162ec86894d604709d8b35)
- [Splitting and Processing an Array every n length using Google Apps Script](https://gist.github.com/tanaikech/9e6276edb67d0ebde80ea378b6f79e20)
- [Requesting to Gate API v4 using Google Apps Script](https://gist.github.com/tanaikech/d0ea117b1c0e54cf713a8027f6b2fb08)
- [Exporting Tabulator Data to Google Drive using Google Apps Script](https://gist.github.com/tanaikech/b0d83cd2f0a27f9cd778f3a1f167503e)
- [Shortening a Long URL using Firebase Dynamic Links API with Google Apps Script](https://gist.github.com/tanaikech/e439cbaadf363380fe026b380dd4de42)
- [Retrieving Names of Month and Day of Week using Google Apps Script](https://gist.github.com/tanaikech/be6ef51a402aacb9fa24277dffed63bc)
- [Retrieving Icons of each mimeType on Google Drive using Google Apps Script](https://gist.github.com/tanaikech/1c0bd1e88b67f19b77d79c9f631b001d)
- [Requesting with Keeping Cookies using Google Apps Script (SessionFetch)](https://gist.github.com/tanaikech/6202470a2bb4d22d1b195bb20bf8390c)
- [Retrying UrlFetchApp by an Error using Google Apps Script (RetryFetch)](https://gist.github.com/tanaikech/ff431dacecc9af58d5e3c1b2aee53d5a)
- [Retrieving Batch Path for Batch Requests using Google Apps Script](https://gist.github.com/tanaikech/a970943f91c0dd0955d1722743e560df)
- [Using getBatchGet, batchCreateContacts, batchDeleteContacts, batchUpdateContacts of People API with Google Apps Script](https://gist.github.com/tanaikech/70e08b966e2f8095462dffa5760100c9)
- [Workaround: Reflecting Latest Script to Deployed Web Apps Created by Google Apps Script without Redeploying](https://gist.github.com/tanaikech/e46def22cf106b012dfa5ad359b93d24)
- [Encrypting and Decrypting with AES using crypto-js with Google Apps Script](https://gist.github.com/tanaikech/1038c73f028b7595f4e070a0e7d48ff1)
- [Decrypting Salted Base64 of finance.yahoo.com using Google Apps Script](https://gist.github.com/tanaikech/2c13c70e932e84adcf658ca8334f25ab)
- [Filtering JSON object using Google Apps Script](https://gist.github.com/tanaikech/d80131e89ed5025bbd40fe19b9e43beb)
- [Retrieving Start and End of Month in Year using Google Apps Script and Javascript](https://gist.github.com/tanaikech/1153792b17ce29ae86c865e53c999375)
- [Merging Multiple PDF Files as a Single PDF File using Google Apps Script](https://gist.github.com/tanaikech/449ff906b85be18977e47e0d5ea173d5)
- [Converting All Pages in PDF File to PNG Images using Google Apps Script](https://gist.github.com/tanaikech/94ff0713a7bfe2d3e43afbfe54611190)
- [Replacing U+00A0 with U+0020 as Unicode using Google Apps Script](https://gist.github.com/tanaikech/cc470a3b6c49b32e06d908e6d3f96f66)
- [January 27, 2023: Decrypting Salted Base64 of finance.yahoo.com using Google Apps Script](https://gist.github.com/tanaikech/2b1c008d7f8e873cc738d75c7fefaf71)
- [February 15, 2023: Decrypting Salted Base64 of finance.yahoo.com using Google Apps Script](https://gist.github.com/tanaikech/84213e047bc64b50deb7295758e0d971)
- [Issue of HTML form with Input tab of Type File with google.script.run](https://gist.github.com/tanaikech/9590b01e4d363d724c458b5cbc87d041)
- [Exporting Google Docs Files in PDF format with Batch Requests using Google Apps Script](https://gist.github.com/tanaikech/d65d9608e6dd108a0fed31604e7556e7)
- [Split Binary Data with Search Data using Google Apps Script](https://gist.github.com/tanaikech/1d406d997090888cfacdb8e9d295ba34)
- [Directly Retrieving Values from XLSX data using SheetJS with Google Apps Script](https://gist.github.com/tanaikech/7647ac0d4faa8fffb78ff2324be8435c)
- [Workaround: Starting Animation GIF on Google Slide by Clicking](https://gist.github.com/tanaikech/3a34928e74009f9c26a40c121de76d6a)
- [Retrieving Release Notes of Google Apps Script and Google APIs from RSS using Google Apps Script](https://gist.github.com/tanaikech/fc54bb2c640e3c7ee8b168a7aa1431a8)
- [Notifying New Release of Google APIs and Google Apps Script with Email using Google Apps Script](https://gist.github.com/tanaikech/79a40abcc70ca3f57db5b4a739bfa849)
- [Converting Various Formatted Images to PNG Format and JPEG format using Google Apps Script](https://gist.github.com/tanaikech/7ef9536ff3f788238509d9c366ed9aed)
- [Exporting Specific Pages From a PDF as a New PDF Using Google Apps Script](https://gist.github.com/tanaikech/9d77f7d634d2d31914396d7dc84b79c3)
- [Management of PDF Metadata using Google Apps ScriptManagement of PDF Metadata using Google Apps Script](https://gist.github.com/tanaikech/9ee06b508624e252dd0e32efc348a59a)
- [Changing Order of Pages in PDF file using Google Apps Script](https://gist.github.com/tanaikech/9de62573049e72b44a069fc31348524b)
- [Retrieving and Putting Values for PDF Forms using Google Apps Script](https://gist.github.com/tanaikech/a8a387614410b8c6c2c1addbce4dd23c)
- [Creating PDF Forms from Google Slide Template using Google Apps Script](https://gist.github.com/tanaikech/682dec95002f8cc25f1c5f2349966b8c)
- [Embedding Objects in PDF using Google Apps Script](https://gist.github.com/tanaikech/b085cb08d573afa2294e2a8f887cdbd2)
- [Cooking PDF over Google Apps Script](https://gist.github.com/tanaikech/42ad6a83322364d0b99ad11260862f04)
- [Add Header and Footer to Exported PDF from Google Spreadsheet using Google Apps Script](https://gist.github.com/tanaikech/1aac9139666963cb9268082763494218)
- [Executing Google Apps Script with Service Account](https://gist.github.com/tanaikech/304fea821ca36b8e9ccebe9814eaed82)
- [Inserting HTML including Javascript on Web Apps Created by Google Apps Script](https://gist.github.com/tanaikech/a5b5b5646b97934578fbb22ee503e6aa)
- [Retrieve Comments with Emoji Reactions from Google Documents, Google Slides, and Google Spreadsheets using Google Apps Script](https://gist.github.com/tanaikech/7713944094af5643fcf13b8d362d0c68)
- [Automatically Creating Descriptions of Files on Google Drive using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/87dcf5a2ab90bbef983a140ec79f7396)
- [Returning Class Object of Google Apps Script with JSDoc](https://gist.github.com/tanaikech/a42e060d0c049d981ea7a4a5e9da3892)
- [Use Microsoft Docs Files (Word, Excel, and PowerPoint) with Document Service, Spreadsheet Service, and Slides Service of Google Apps Script](https://gist.github.com/tanaikech/288b56aa47f4270f3b96d1421ea3eb36)
- [Convert Contact URL to Resource Name for People API using Google Apps Script](https://gist.github.com/tanaikech/41e71610f03617e131183faac5cf9ad7)
- [Empowering Everyone to Leverage Various Google APIs using Google Apps Script](https://gist.github.com/tanaikech/88c180fa4bb35b74b73203f754db2d3c)
- [Adding Page Numbers to PDF using Google Apps Script](https://gist.github.com/tanaikech/05834ac8e605922637af9a4cfdecc152)
- [Checking API Enabled with Advanced Google Services using Google Apps Script](https://gist.github.com/tanaikech/3f03dac24179f750c013abc39703c4d2)

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
- [Sample Script for Resumable Upload to Google Drive using Axios with Node.js](https://gist.github.com/tanaikech/5212f2a8127e1c0a70c8642e298ae661)
- [Creating and Deleting Multiple Events in Google Calendar by Batch Requests using Calendar API with Node.js](https://gist.github.com/tanaikech/33544a8f56cb5b4c2f96ceb29d6b2855)
- [Putting Multiple Hyperlinks to a Cell using Sheets API with Google Apps Script and Node.js](https://gist.github.com/tanaikech/4c27bf8d1948a5dfa5b0e53ce88c6d30)

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
- [Replacing Template Texts with Array in Google Document using Docs API with Python](https://gist.github.com/tanaikech/f1f9fb91d3432362670c810ae05ba53b)
- [Uploading Files to Google Drive with Asynchronous Process using Python](https://gist.github.com/tanaikech/a4cfbea4935b8c281d1f6abb91016705)
- [Retrieving Access Token from Service Account using oauth2client and google-auth with Python](https://gist.github.com/tanaikech/5196ed237812192539c4369000bc131b)
- [Using Until Expiration Time of Access Token Retrieved By googleapis for Python](https://gist.github.com/tanaikech/b2d877e4e4d274b17876191d48204882)
- [Resumable Download of File from Google Drive using Drive API with Python](https://gist.github.com/tanaikech/dfdad37859d591526b2fba8fb4390cf5)

<a name="curl"></a>

#### Curl

- [File Upload and Download with File Convert For curl using Drive API](https://tanaikech.github.io/2017/02/08/file-upload-and-download-with-file-convert-for-curl-using-drive-api/)
- [Downloading Shared Files on Google Drive Using Curl](https://gist.github.com/tanaikech/f0f2d122e05bf5f971611258c22c110f)
- [Updating a File with Resumable Upload using Drive API](https://gist.github.com/tanaikech/bc33a83ac648911d00b43c59a24268fc)

<a name="javascript"></a>

#### Javascript

- [Uploading Image Files to Google Photos using axios](https://gist.github.com/tanaikech/426345c24e46da3ac7268f31b76bb3e4)
- [Retrieving Access Token for Service Account using Javascript](https://gist.github.com/tanaikech/3c7f208cb352a807b3d30b9c1dcf0c82)
- [Using Google API Client Library (gapi) for JavaScript with Service Account](https://gist.github.com/tanaikech/603102a64587cb9bff2e165994f6b6a1)
- [Retrieving Values from Publicly Shared Google Spreadsheet using API key with Javascript](https://gist.github.com/tanaikech/aeb1a21e1e51a902f903e6363cd1a5db)

<a name="php"></a>

#### PHP

- [Retrieving Access Token using Service Account for PHP without using googleapis](https://gist.github.com/tanaikech/1b47cfec588454963ee40c5a50943194)

<a name="generativeai"></a>

#### Generative AI

- [Automatically Creating Descriptions of Files on Google Drive using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/87dcf5a2ab90bbef983a140ec79f7396)
- [Flexible Labeling for Gmail using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/cdfa63b670b223e482e457703b9cdeb6)
- [Expanding Error Messages of Google Apps Script using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/b86db4d574474cbb079b185271f679ce)
- [Inserting Generated Text to Google Documents, Google Spreadsheets, and Google Slides using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/f1a6042c62e207d22eb5a38140d8484e)
- [Semantic Search using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/c6556dc08ae3dcb013d8909c1f42b16d)
- [Categorization using Gemini Pro API with Google Apps Script](https://gist.github.com/tanaikech/28061e3d5404b4fba23368bbae4611d2)
- [Flexible Labeling for Gmail using Gemini Pro API with Google Apps Script Part 2](https://gist.github.com/tanaikech/811e5c92cf96e8b387ffa9f29da08ec3)
- [Semantic Search using Corpus of Gemini API with Google Apps Script](https://gist.github.com/tanaikech/02415a0056099229525f894ae59dacb5)
- [Applying Gemini Pro API to Flexible Templates using Google Apps Script](https://gist.github.com/tanaikech/ad5bd7eee50c2b9f05995d56679610f7)
- [Guide to Function Calling with Gemini and Google Apps Script](https://gist.github.com/tanaikech/061cca4b9af67abe8c4244c03750ea30)
- [Creating Image Bot using Gemini with Google Apps Script](https://gist.github.com/tanaikech/cf29216cf4b1c127d9213db6079894c7)
- [Similarity Viewer using Gemini API with Google Spreadsheet and Google Apps Script](https://gist.github.com/tanaikech/6a7afe7b145170265ee3cb2d6cb4be58)
- [Enhanced Search using Gemini API](https://gist.github.com/tanaikech/70c28ddff49e8a0cf474f7f48d996b8a)
- [Attempting Reverse Engineering with Gemini API and Google Apps Script](https://gist.github.com/tanaikech/b0cab68b99137de21339d717d8ea1b25)
- [Crafting Bespoke Output Formats with Gemini API](https://gist.github.com/tanaikech/3a659a87673e3e582c880934c8f19e01)
- [Generating Texts using Files Uploaded by Gemini 1.5 API](https://gist.github.com/tanaikech/0ad317503e3a066d715430e7e875abfb)
- [Analyzing Trends of Google Apps Script from Questions on Stackoverflow using Gemini 1.5 API](https://gist.github.com/tanaikech/8621c3b799685fd2db1204d1372e1d73)
- [Parsing Invoices using Gemini 1.5 API with Google Apps Script](https://gist.github.com/tanaikech/165a6a76244a81312f9d398e88c4730d)
- [Specifying Output Types for Gemini API with Google Apps Script](https://gist.github.com/tanaikech/f7e627a286058229aeaaed776743564d)
- [Batch Processing Powerhouse: Leverage Gemini 1.5 API and Google Apps Script for Efficient Content Workflows](https://gist.github.com/tanaikech/f3dbba02a620cfd7a729e13b012ea66f)
- [Taming the Wild Output: Effective Control of Gemini API Response Formats with response_mime_type](https://gist.github.com/tanaikech/0a55011d3e8b8fadebb71b624bb9a8af)
- [Gemini API with JSON schema](https://gist.github.com/tanaikech/45b1a738b9e27236545a3cbcc1479a58)
- [Leveraging Gemini 1.5 API for Automated Test Case Generation in Google Apps Script Reverse Engineering](https://gist.github.com/tanaikech/fc51414e16faa2a26aa39eea487d64a5)

[TOP](#top)
