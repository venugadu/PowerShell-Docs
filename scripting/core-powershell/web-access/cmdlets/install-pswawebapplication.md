---
description:  
manager:  carmonm
ms.topic:  article
author:  jpjofre
ms.prod:  powershell
keywords:  powershell,cmdlet
ms.date:  2016-12-12
title:  install pswawebapplication
ms.technology:  powershell
---

<div id="page">

<div id="ux-header" class="ltr powershell" dir="ltr" ms.pgarea="header">

<span id="singleCol"></span> <span id="doubleCol"></span> <span
id="isMobile"></span>
<div>

<div class="row topRow" role="banner">

<div class="top">

<div class="left">

[](https://msdn.microsoft.com/en-us "MSDN home"){.msdnLogoImg}
<div class="clip70x15">

![Microsoft
Logo](https://i-technet.sec.s-msft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636146814338182722){#msft-logo
.msft-logo}

</div>

<div class="GrayPipeDiv clip1x18">

![Gray
Pipe](https://i-technet.sec.s-msft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636146814338182722){.GrayPipe}

</div>

<div class="MegaBladeNavigation">

<div class="megaBladeToc">

-   [Developer Network](javascript:void(0) "Developer Network")
    -   [Downloads](javascript:void(0) "Downloads")
        -   [Visual
            Studio](https://www.visualstudio.com/downloads/download-visual-studio-vs "Visual Studio")
        -   [MSDN subscription
            access](https://msdn.microsoft.com//subscriptions "MSDN subscription access")
        -   [SDKs](https://msdn.microsoft.com/microsoft-sdks-msdn "SDKs")
        -   [Trial
            software](https://msdn.microsoft.com/evalcenter "Trial software")
    -   [Programs](javascript:void(0) "Programs")
        -   [Subscriptions](https://msdn.microsoft.com/msdn-subscriptions-overview "Subscriptions")
        -   [Students](https://msdn.microsoft.com/students-overview-msdn "Students")
        -   [ISV](https://msdn.microsoft.com/applicationbuilder "ISV")
        -   [Startups](https://www.microsoft.com/bizspark "Startups")
        -   [TechRewards](https://rewards.msdn.microsoft.com/ "TechRewards")
        -   [Events](http://events.msdn.microsoft.com/ "Events")
    -   [Community](javascript:void(0) "Community")
        -   [Magazine](https://msdn.microsoft.com/magazine/dd767791 "Magazine")
        -   [Forums](https://social.msdn.microsoft.com/forums/ "Forums")
        -   [Blogs](https://blogs.msdn.microsoft.com/ "Blogs")
        -   [Channel 9](http://channel9.msdn.com/ "Channel 9")
    -   [Documentation](javascript:void(0) "Documentation")
        -   [APIs and
            reference](https://msdn.microsoft.com/library "APIs and reference")
        -   [Dev
            centers](https://msdn.microsoft.com/developer-centers-msdn "Dev centers")
        -   [Samples](https://code.msdn.microsoft.com/ "Samples")
        -   [Retired
            content](https://msdn.microsoft.com/retiredcontent "Retired content")

</div>

</div>

[Developer
Network](https://msdn.microsoft.com/en-us){.DevCenterFullName}
[Developer](https://msdn.microsoft.com/en-us){.DevCenterShortName}

</div>

<div class="right" ms.cmpgrp="aux nav">

<div id="signIn" aria-label="Profile button">

<div class="profileImage">

</div>

[Sign
in](https://login.live.com/login.srf?wa=wsignin1.0&rpsnv=13&ct=1481155779&rver=6.7.6640.0&wp=mcmbi&wlcxt=technet%24technet%24technet&wreply=https%3a%2f%2ftechnet.microsoft.com%2fen-us%2flibrary%2fjj592894%2528v%3dwps.630%2529.aspx&lc=1033&id=254354&mkt=en-us){.scarabLink}

</div>

<div class="auxNav">

<div>

<div id="Fragment_Subscriptions" data-fragmentname="Subscriptions"
xmlns="http://www.w3.org/1999/xhtml">

[MSDN
subscriptions](https://msdn.microsoft.com/subscriptions/manage/hh442900){#Subscriptions_2153_1}

</div>

<div id="Fragment_GetTools" data-fragmentname="GetTools"
xmlns="http://www.w3.org/1999/xhtml">

[Get
tools](http://go.microsoft.com/fwlink/?LinkId=309297&clcid=0x409&slcid=0x409&campaign=o~msft~msdn~gettools-header~dn308572){#GetTools_2153_3}

</div>

</div>

<div>

<div id="Fragment_SocialLinks" data-fragmentname="SocialLinks"
xmlns="http://www.w3.org/1999/xhtml">

</div>

</div>

</div>

</div>

</div>

</div>

<div class="row middleRow">

<div class="expandTop">

<div class="left">

</div>

<div class="right">

</div>

</div>

</div>

</div>

<div id="buttomRowWrapper" class="bg_gray1">

<div class="row buttomRow bg_gray1">

<div class="bottom">

<div class="left" role="navigation" aria-label="header toc"
ms.cmpgrp="main nav">

[](javascript:void(0)){#grip .menu-icon}
<div id="Fragment_SiteLogo" data-fragmentname="SiteLogo"
xmlns="http://www.w3.org/1999/xhtml">

<div class="LinkWithImage leftImage">

[![PowerShell](https://i-technet.sec.s-msft.com/en-us/Powershell/ux/library/dn966235.Powershell_32.png?isResponsive=true&Segments=http%3a%2f%2ftechnet.microsoft.com%2flibrary&isLibrary=true&OverwriteHostBase=https%3a%2f%2fmsdn.microsoft.com%2f&isMtpsRequest=true&ThemeBranding=Powershell&HideProfileLink=true&HideProfileText=true "PowerShell"){#Powershell_32}
<span>PowerShell</span>](https://msdn.microsoft.com/powershell){#SiteLogo_15502_1}

</div>

</div>

<div id="drawer">

<div class="toc">

-   [Gallery](https://www.powershellgallery.com/ "Gallery")
-   [Documentation](javascript:void(0))
    -   [Windows
        PowerShell](https://msdn.microsoft.com/en-us/powershell/scripting/powershell-scripting "Windows PowerShell")
    -   [Desired State
        Configuration (DSC)](https://msdn.microsoft.com/en-us/powershell/dsc/overview "Desired State Configuration (DSC)")
    -   [Just Enough
        Administration (JEA)](https://msdn.microsoft.com/powershell/jea/readme "Just Enough Administration (JEA)")
    -   [PowerShell Modules
        Reference](https://msdn.microsoft.com/powershell/reference/readme "PowerShell Modules Reference")
    -   [Windows PowerShell
        SDK](https://msdn.microsoft.com/library/dd835506.aspx "Windows PowerShell SDK")
    -   [PowerShell
        Gallery](https://msdn.microsoft.com/en-us/powershell/gallery "PowerShell Gallery")
    -   [Azure
        PowerShell](https://msdn.microsoft.com/en-us/library/azure/jj156055.aspx "Azure PowerShell")
-   [Community](javascript:void(0))
    -   [Announcements](https://msdn.microsoft.com//powershell/mt757324 "Announcements")
    -   [Community
        Links](https://msdn.microsoft.com//powershell/mt270381 "Community Links")
-   [Feedback](javascript:void(0))
    -   [UserVoice](http://windowsserver.uservoice.com/forums/301869-powershell "UserVoice")
    -   [Q&A
        Submissions](https://www.surveymonkey.com/r/wcq7hf9 "Q&A Submissions")

</div>

</div>

</div>

<div class="right" ms.title="search" role="search">

<div id="Fragment_SearchBox" data-fragmentname="SearchBox"
xmlns="http://www.w3.org/1999/xhtml">

<div class="SearchBox">

<div id="search-finder-div" class="clip16x20">

![search
finder](https://i-technet.sec.s-msft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636146814338182722){#search-finder
.search-finder}

</div>

<div id="searchSplitter">

</div>

<div id="searchCloseIconDiv" class="clip16x20" tabindex="0">

![search
clear](https://i-technet.sec.s-msft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636146814338182722){#searchCloseIcon
.search-clear-x}

</div>

<div id="searchTextContainer" style="width: 0;">

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div id="jumpInfo" style="display: none">

We’re sorry. The content you requested has been removed. You’ll be auto
redirected in 1 second.

</div>

<div id="breadcrumbs" ms.pgarea="body" ms.cmpgrp="breadcrumbs">

<div id="breadcrumbDesktop" class="breadCrumb">

<span
class="breadcrumbEllipsis">[](https://technet.microsoft.com/en-us/library/bb978526.aspx "Scripting with Windows PowerShell")</span>
<span>[<span>Windows and Windows Server Automation with Windows
PowerShell</span>](https://technet.microsoft.com/en-us/library/mt156946.aspx "Windows and Windows Server Automation with Windows PowerShell")</span>
<span>[<span>Windows Server 2012 R2 and Windows
8.1</span>](https://technet.microsoft.com/en-us/library/dn249523(v=wps.630).aspx "Windows Server 2012 R2 and Windows 8.1")</span>
<span class="breadcrumbDropSmall"> [<span>Windows PowerShell Web Access
Cmdlets</span>](# "Windows PowerShell Web Access Cmdlets"){#breadcrumbDropDownButton}
</span>

</div>

<div id="breadcrumbDropDownMenu">

</div>

<div id="breadcrumbTablet" class="breadCrumb">

<span
class="breadcrumbEllipsis">[](https://technet.microsoft.com/en-us/library/dn249523(v=wps.630).aspx "Windows Server 2012 R2 and Windows 8.1")</span>
<span>[<span>Windows PowerShell Web Access
Cmdlets</span>](https://technet.microsoft.com/en-us/library/jj592887(v=wps.630).aspx "Windows PowerShell Web Access Cmdlets")</span>
<span
class="breadcrumbDropSmall">[<span>Install-PswaWebApplication</span>](# "Install-PswaWebApplication"){#tocDropDownButton}</span>

</div>

<div id="tocDropDownMenu">

</div>

<div id="breadcrumbMobile" class="breadCrumb">

<span
class="breadcrumbEllipsis">[](https://technet.microsoft.com/en-us/library/jj592887(v=wps.630).aspx "Windows PowerShell Web Access Cmdlets")</span>
<span
class="breadcrumbDropSmall">[<span>Install-PswaWebApplication</span>](# "Install-PswaWebApplication"){#tocPopupButton}</span>

</div>

</div>

<div id="tocPopupMenu">

<div id="tocPopMenuClose" class="tocCloseLarge">

</div>

<div id="tocTitle">

Install-PswaWebApplication

</div>

</div>

<div id="body" ms.pgarea="body">

<span id="tabletView_large"></span> <span id="tabletView_small"></span>
<span id="mobileView"></span>
<div id="leftNav" ms.cmpgrp="left toc" role="navigation"
aria-label="left toc">

<div id="tocnav" class="ArchiveV2">

<div class="tocunselected">

<div id="tocExpandArea">

<span class="toc_empty"></span> <span
id="tocExpandButton">[](javascript:void(0))</span>

</div>

<div id="tocExpand">

</div>

</div>

<div class="tocselected">

</div>

<div class="tocunselected">

<div class="toclevel" data-toclevel="1">

[Add-PswaAuthorizationRule](https://technet.microsoft.com/en-us/library/jj592890(v=wps.630).aspx "Add-PswaAuthorizationRule")

</div>

<div class="toclevel" data-toclevel="1">

[Get-PswaAuthorizationRule](https://technet.microsoft.com/en-us/library/jj592891(v=wps.630).aspx "Get-PswaAuthorizationRule")

</div>

<div class="toclevel current" data-toclevel="1">

[Install-PswaWebApplication](https://technet.microsoft.com/en-us/library/jj592894(v=wps.630).aspx "Install-PswaWebApplication")

</div>

<div class="toclevel" data-toclevel="1">

[Remove-PswaAuthorizationRule](https://technet.microsoft.com/en-us/library/jj592893(v=wps.630).aspx "Remove-PswaAuthorizationRule")

</div>

<div class="toclevel" data-toclevel="1">

[Test-PswaAuthorizationRule](https://technet.microsoft.com/en-us/library/jj592892(v=wps.630).aspx "Test-PswaAuthorizationRule")

</div>

<div class="toclevel" data-toclevel="1">

[Uninstall-PswaWebApplication](https://technet.microsoft.com/en-us/library/jj592889(v=wps.630).aspx "Uninstall-PswaWebApplication")

</div>

</div>

[<span id="tocMenuTogglerIcon" class="tocMenuCollapse" role="button"
aria-expanded="true"
aria-label="Table of contents menu"></span>](javascript:void(0)){#tocMenuToggler}
<div id="tocMenuTogglerLabel">

TOC

</div>

</div>

<div style="display:none">

<div id="CollapseLocalizeString">

Collapse the table of content

</div>

<div id="ExpandLocalizeString">

Expand the table of content

</div>

</div>

<div>

[](javascript:void(0)){#isd_archiveControlResponsive}
<div id="isd_archiveInstrument" style="display:none">

This documentation is archived and is not being maintained.

</div>

</div>

</div>

<div id="content" class="content" ms.cmpgrp="content body" role="main">

<div id="archiveDisclaimerText" style="display:none">

This documentation is archived and is not being maintained.

</div>

<div xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" xmlns="http://www.w3.org/1999/xhtml"
mtps="http://msdn2.microsoft.com/mtps"
msxsl="urn:schemas-microsoft-com:xslt"
cs="http://msdn.microsoft.com/en-us/">

<div class="lw_vs">

<div id="curversion">

**Windows Server 2012 R2 and Windows 8.1**

</div>

<div id="versionclick">

<div id="vsseperator" class="cl_lw_vs_seperator">

</div>

<div>

<div>

[Other Versions](javascript:void(0)){#vsLink}

</div>

<div class="cl_vs_arrow clip10x10">

![](https://i-technet.sec.s-msft.com/Areas/Epx/Content/Images/ImageSprite.png?v=636146814391620512){#vsArrow
.cl_lw_vs_arrow}

</div>

</div>

-   [Windows Server 2012 and Windows
    8](/en-us/library/jj592894(v=wps.620).aspx)

</div>

</div>

<div style="clear:both;">

</div>

<div id="mainSection">

<div id="mainBody">

Install-PswaWebApplication {#install-pswawebapplication-1 .heading}
--------------------------

<div id="sectionSection0" class="section">

Configures the Windows PowerShell®Web Access web application in IIS.

</div>

Syntax {#syntax .heading}
------

<div id="sectionSection1" class="section">

<div id="code-snippet-1" class="codeSnippetContainer" xmlns="">

<div class="codeSnippetContainerTabs">

</div>

<div class="codeSnippetContainerCodeContainer">

<div class="codeSnippetToolBar">

<div class="codeSnippetToolBarText">

[Copy](javascript:if%20(window.epx.codeSnippet)window.epx.codeSnippet.copyCode('CodeSnippetContainerCode_229c23a0-ac4a-497a-97e2-f2141524fc1b'); "Copy to clipboard.")

</div>

</div>

<div id="CodeSnippetContainerCode_229c23a0-ac4a-497a-97e2-f2141524fc1b"
class="codeSnippetContainerCode" dir="ltr">

<div style="color:Black;">

    Parameter Set: Default
    Install-PswaWebApplication [[-WebApplicationName] <String> ] [-UseTestCertificate] [-WebSiteName <String> ] [-Confirm] [-WhatIf] [ <CommonParameters>]

</div>

</div>

</div>

</div>

\
\

</div>

Detailed Description {#detailed-description .heading}
--------------------

<div id="sectionSection2" class="section">

The **Install-PswaWebApplication** cmdlet configures Windows PowerShell
Web Access web application. This cmdlet installs the web application,
associates it with a web site, and optionally creates a test SSL
certificate using the **useTestCertificate** parameter. For security
reasons web administrators should not use a test certificate for
production environments.

</div>

Parameters {#parameters .heading}
----------

<div id="sectionSection4" class="section">

### -UseTestCertificate {#usetestcertificate .subHeading}

<div class="subSection">

Specifies that a test certificate is created. If this parameter is set
to true, then this cmdlet creates a test certificate and configures the
Windows PowerShell Web Access web application to use the certificate for
HTTPS requests. If this parameter is set to false, then no certificate
or binding is created. Set this value to false if another certificate is
used for Windows PowerShell Web Access.

\
+--------------------------------------+--------------------------------------+
| Aliases                              | none                                 |
+--------------------------------------+--------------------------------------+
| Required?                            | false                                |
+--------------------------------------+--------------------------------------+
| Position?                            | named                                |
+--------------------------------------+--------------------------------------+
| Default Value                        | true                                 |
+--------------------------------------+--------------------------------------+
| Accept Pipeline Input?               | false                                |
+--------------------------------------+--------------------------------------+
| Accept Wildcard Characters?          | false                                |
+--------------------------------------+--------------------------------------+

</div>

### -WebApplicationName&lt;String&gt; {#webapplicationnamestring .subHeading}

<div class="subSection">

Specifies the name for your web application. This is displayed as the
last part of the Windows PowerShell Web Access URL.

\
+--------------------------------------+--------------------------------------+
| Aliases                              | none                                 |
+--------------------------------------+--------------------------------------+
| Required?                            | false                                |
+--------------------------------------+--------------------------------------+
| Position?                            | 1                                    |
+--------------------------------------+--------------------------------------+
| Default Value                        | pswa                                 |
+--------------------------------------+--------------------------------------+
| Accept Pipeline Input?               | false                                |
+--------------------------------------+--------------------------------------+
| Accept Wildcard Characters?          | false                                |
+--------------------------------------+--------------------------------------+

</div>

### -WebSiteName&lt;String&gt; {#websitenamestring .subHeading}

<div class="subSection">

Specifies the name of the Web Server (IIS) website on which to install
this Windows PowerShell Web Access web application.

\
+--------------------------------------+--------------------------------------+
| Aliases                              | none                                 |
+--------------------------------------+--------------------------------------+
| Required?                            | false                                |
+--------------------------------------+--------------------------------------+
| Position?                            | named                                |
+--------------------------------------+--------------------------------------+
| Default Value                        | Default Web Site                     |
+--------------------------------------+--------------------------------------+
| Accept Pipeline Input?               | false                                |
+--------------------------------------+--------------------------------------+
| Accept Wildcard Characters?          | false                                |
+--------------------------------------+--------------------------------------+

</div>

### -Confirm {#confirm .subHeading}

<div class="subSection">

Prompts you for confirmation before running the cmdlet.

\
+--------------------------------------+--------------------------------------+
| Required?                            | false                                |
+--------------------------------------+--------------------------------------+
| Position?                            | named                                |
+--------------------------------------+--------------------------------------+
| Default Value                        | false                                |
+--------------------------------------+--------------------------------------+
| Accept Pipeline Input?               | false                                |
+--------------------------------------+--------------------------------------+
| Accept Wildcard Characters?          | false                                |
+--------------------------------------+--------------------------------------+

</div>

### -WhatIf {#whatif .subHeading}

<div class="subSection">

Shows what would happen if the cmdlet runs. The cmdlet is not run.

\
+--------------------------------------+--------------------------------------+
| Required?                            | false                                |
+--------------------------------------+--------------------------------------+
| Position?                            | named                                |
+--------------------------------------+--------------------------------------+
| Default Value                        | false                                |
+--------------------------------------+--------------------------------------+
| Accept Pipeline Input?               | false                                |
+--------------------------------------+--------------------------------------+
| Accept Wildcard Characters?          | false                                |
+--------------------------------------+--------------------------------------+

</div>

### &lt;CommonParameters&gt; {#commonparameters .subHeading}

<div class="subSection">

This cmdlet supports the common parameters: -Verbose, -Debug,
-ErrorAction, -ErrorVariable, -OutBuffer, and -OutVariable. For more
information, see    about\_CommonParameters
(http://go.microsoft.com/fwlink/p/?LinkID=113216).

</div>

</div>

Inputs {#inputs .heading}
------

<div id="sectionSection5" class="section">

The input type is the type of the objects that you can pipe to the
cmdlet.

-   **None**

</div>

Outputs {#outputs .heading}
-------

<div id="sectionSection6" class="section">

The output type is the type of the objects that the cmdlet emits.

-   **None**

</div>

Examples {#examples .heading}
--------

<div id="sectionSection8" class="section">

### EXAMPLE 1 {#example-1 .subHeading}

<div class="subSection">

This example installs the PSWA web application using the default values
for the **WebApplicationName** (*pswa*) and **WebSiteName** (*Default
Web Site*) parameters .

\
<div id="code-snippet-2" class="codeSnippetContainer" xmlns="">

<div class="codeSnippetContainerTabs">

<div class="codeSnippetContainerTabSingle" dir="ltr">

[Windows PowerShell]()

</div>

</div>

<div class="codeSnippetContainerCodeContainer">

<div class="codeSnippetToolBar">

<div class="codeSnippetToolBarText">

[Copy](javascript:if%20(window.epx.codeSnippet)window.epx.codeSnippet.copyCode('CodeSnippetContainerCode_3d415aca-7fa3-4208-8139-b3e55e9156e7'); "Copy to clipboard.")

</div>

</div>

<div id="CodeSnippetContainerCode_3d415aca-7fa3-4208-8139-b3e55e9156e7"
class="codeSnippetContainerCode" dir="ltr">

<div style="color:Black;">

    PS C:\> Install-PswaWebApplication

</div>

</div>

</div>

</div>

</div>

### EXAMPLE 2 {#example-2 .subHeading}

<div class="subSection">

This example installs the PSWA web application with a test certificate,
and using the default values for the **WebApplicationName** and
**WebSiteName** parameters.

\
<div id="code-snippet-3" class="codeSnippetContainer" xmlns="">

<div class="codeSnippetContainerTabs">

<div class="codeSnippetContainerTabSingle" dir="ltr">

[Windows PowerShell]()

</div>

</div>

<div class="codeSnippetContainerCodeContainer">

<div class="codeSnippetToolBar">

<div class="codeSnippetToolBarText">

[Copy](javascript:if%20(window.epx.codeSnippet)window.epx.codeSnippet.copyCode('CodeSnippetContainerCode_10ba9b1a-c88c-4e80-a65c-75c55f09a828'); "Copy to clipboard.")

</div>

</div>

<div id="CodeSnippetContainerCode_10ba9b1a-c88c-4e80-a65c-75c55f09a828"
class="codeSnippetContainerCode" dir="ltr">

<div style="color:Black;">

    PS C:\> Install-PswaWebApplication -UseTestCertificate

</div>

</div>

</div>

</div>

</div>

</div>

Related topics {#related-topics .heading}
--------------

<div id="seeAlsoNoToggle" class="section">

\
[Add-PswaAuthorizationRule](https://technet.microsoft.com/library/fc8a7d82-4ab5-4d43-8163-c96fb2af4180)\
\
[Get-PswaAuthorizationRule](https://technet.microsoft.com/library/d89f4961-9e6d-48c7-91f7-300b341a73fa)\
\
[Remove-PswaAuthorizationRule](https://technet.microsoft.com/library/f42295dd-6f00-4aae-9019-15d095b8c6ef)\
\
[Test-PswaAuthorizationRule](https://technet.microsoft.com/library/5e389837-af44-4df2-9389-126db205e0e1)\
\

</div>

</div>

</div>

</div>

</div>

<div class="communityContentContainer" ms.cmpgrp="community">

<div id="CommunityContentHeader" class="communityContentHeader">

<div class="communityContentHeaderTitleContainer">

Community Additions
-------------------

[<span class="communityContentAddButton" title="Add"> ADD
</span>](https://technet.microsoft.com/en-us/library/community/add/jj592894(v=wps.630).aspx){.communityContentAddLink}

</div>

<div style="clear: both;">

</div>

</div>

<div id="CommunityComments"
data-url="/en-us/library/community/comments/jj592894(v=wps.630).aspx">

</div>

</div>

<div class="libraryMemberFilter">

<div class="filterContainer">

<span>Show:</span> Inherited Protected

</div>

</div>

</div>

<div id="rightNavigationMenu" ms.cmpgrp="right nav">

<div id="mobileButtons">

<div id="navigationButtons">

Print
Export (<span class="count">0</span>)

</div>

</div>

<div id="navMain">

<div id="closeNavigation">

[](){#closeButton .tocCloseSmall}

</div>

<div id="navigationButtons">

Print
Export (<span class="count">0</span>)
Share
<div id="socials" style="display: none">

</div>

</div>

<div id="indoc_toc" style="display: none" ms.cmpgrp="indoc toc">

<div id="indoc_title">

IN THIS ARTICLE

</div>

</div>

</div>

</div>

<div id="rightNavigationMenuThumbnail"
class="rightNavigationMenuThumbnail">

</div>

</div>

<div class="clear">

</div>

<div id="lib-footer">

<div id="standardRatingBefore" class="clear stdr-container-before">

</div>

<div id="standardRating" class="stdr-container" ms.pgarea="body">

<div class="stdr-close">

</div>

<div class="stdr-vote stdr-content">

<div class="stdr-content">

<span class="stdr-votetitle">Is this page helpful?</span>
Yes
No

</div>

</div>

<div class="stdr-feedback" style="display: none">

<div class="stdr-form">

<div class="stdr-fieldtitle">

Additional feedback?

</div>

<div>

<span class="stdr-count"><span class="stdr-charcnt">1500</span>
characters remaining</span>
<div class="stdr-buttons">

Submit
Skip this

</div>

</div>

<div class="clear">

</div>

</div>

</div>

<div class="stdr-thanks" style="display: none">

<div class="stdr-content">

<span class="stdr-thankyou">Thank you!</span> <span
class="stdr-appreciate">We appreciate your feedback.</span>

</div>

</div>

<div id="contentFeedbackQAContainer" style="display: none;">

</div>

</div>

<div id="standardRatingPlaceholder" style="display: none">

</div>

<div id="ux-footer" style="" dir="ltr" ms.pgarea="footer">

<div id="standardRatingBefore" class="clear stdr-container-before">

</div>

<div id="standardRating" class="stdr-container" ms.pgarea="body">

<div class="stdr-close">

</div>

<div class="stdr-vote stdr-content">

<div class="stdr-content">

<span class="stdr-votetitle">Is this page helpful?</span>
Yes
No

</div>

</div>

<div class="stdr-feedback" style="display: none">

<div class="stdr-form">

<div class="stdr-fieldtitle">

Additional feedback?

</div>

<div>

<span class="stdr-count"><span class="stdr-charcnt">1500</span>
characters remaining</span>
<div class="stdr-buttons">

Submit
Skip this

</div>

</div>

<div class="clear">

</div>

</div>

</div>

<div class="stdr-thanks" style="display: none">

<div class="stdr-content">

<span class="stdr-thankyou">Thank you!</span> <span
class="stdr-appreciate">We appreciate your feedback.</span>

</div>

</div>

<div id="contentFeedbackQAContainer" style="display: none;">

</div>

</div>

<div id="standardRatingPlaceholder" style="display: none">

</div>

<div id="Fragment_LeftLinks" data-fragmentname="LeftLinks"
xmlns="http://www.w3.org/1999/xhtml">

<div class="linkList">

#### Dev centers {#dev-centers .linkListTitle}

-   [Windows](https://dev.windows.com){#LeftLinks_2148_1 .windowsBlue}
-   [Office](http://dev.office.com){#LeftLinks_2148_3 .office}
-   [Visual
    Studio](https://msdn.microsoft.com/vstudio){#LeftLinks_2148_4
    .visualStudio}
-   [Microsoft
    Azure](http://azure.microsoft.com/en-us/documentation/){#LeftLinks_2148_12}
-   [More...](https://msdn.microsoft.com/developer-centers-msdn){#LeftLinks_2148_5}

</div>

</div>

<div id="rightLinks">

<div id="Fragment_CenterLinks2" data-fragmentname="CenterLinks2"
xmlns="http://www.w3.org/1999/xhtml">

<div class="linkList">

#### Top PowerShell Sites {#top-powershell-sites .linkListTitle}

-   [PowerShell
    Gallery](https://www.powershellgallery.com/){#CenterLinks2_15503_14}
-   [Announcements](https://technet.microsoft.com/en-us/powershell/ux/library/mt757324){#CenterLinks2_15503_15}
-   [Latest WMF Download](http://aka.ms/wmf){#CenterLinks2_15503_16}
-   [PowerShell on
    Github](https://github.com/powershell){#CenterLinks2_15503_17}

</div>

</div>

<div id="Fragment_CenterLinks3" data-fragmentname="CenterLinks3"
xmlns="http://www.w3.org/1999/xhtml">

<div class="linkList">

#### Related Microsoft Sites {#related-microsoft-sites .linkListTitle}

-   [Microsoft Operations Management
    Suite (OMS)](https://www.microsoft.com/oms){#CenterLinks3_15503_23}
-   [OMS
    Automation](https://www.microsoft.com/en-us/cloud-platform/automation-and-control){#CenterLinks3_15503_24}
-   [Windows Server
    Docs](https://msdn.microsoft.com/library/dn636873(v=vs.85).aspx){#CenterLinks3_15503_19}
-   [Office Deployment
    Scripts](https://github.com/OfficeDev/Office-IT-Pro-Deployment-Scripts){#CenterLinks3_15503_20}

</div>

</div>

<div id="Fragment_CenterLinks4" data-fragmentname="CenterLinks4"
xmlns="http://www.w3.org/1999/xhtml">

<div class="linkList">

#### Feedback {#feedback .linkListTitle}

-   [PowerShell
    UserVoice](https://windowsserver.uservoice.com/forums/301869-powershell){#CenterLinks4_15503_21}
-   [Windows Server
    UserVoice](https://windowsserver.uservoice.com/){#CenterLinks4_15503_22}

</div>

</div>

</div>

<span class="localeContainer"> </span>
[United States (English)](# "Change your language")
<div id="Fragment_BottomLinks" data-fragmentname="BottomLinks"
xmlns="http://www.w3.org/1999/xhtml">

<div class="linkList">

-   [Newsletter](https://msdn.microsoft.com/newsletter.aspx){#BottomLinks_2148_7}
-   [Privacy &
    cookies](https://msdn.microsoft.com/dn529288){#BottomLinks_2148_8}
-   [Terms of
    use](https://msdn.microsoft.com/cc300389){#BottomLinks_2148_9}
-   [Trademarks](https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/){#BottomLinks_2148_10}

</div>

</div>

<span class="logoLegal"> <span class="logoSpan clip67x13" role="img"
tabindex="0" aria-label="microsoft logo">
![logo](https://i-technet.sec.s-msft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636146814338182722){.logo}
</span> <span class="copyright">© 2016 Microsoft</span> </span>

</div>

</div>

<div class="footerPrintView">

<div class="footerCopyrightPrintView">

© 2016 Microsoft

</div>

</div>

Third party scripts and code linked to or referenced from this website
are licensed to you by the parties that own such code, not by Microsoft.
See ASP.NET Ajax CDN Terms of Use –
http://www.asp.net/ajaxlibrary/CDN.ashx. WebTrends view model not
available or IncludeLegacyWebTrendsScriptInGlobal feature flag is off
<div id="globalRequestVerification">

</div>

</div>

