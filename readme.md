[//]: # (header-start)

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
<h1 align="center">
	Axway Amplify End-of-Life Announcement
</h1>
<h2 align="center">
	👇 &nbsp; See notes below  &nbsp; 👇
</h2>	
</a>

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Cloud Services (2012 - 2022)
	</p>
</a>
<hr>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h4 align="center">
🛑 &nbsp;&nbsp; All products affected by the announcements will not be supported by Axway effective their EOL dates in 2022.
</h4>

<h4 align="center">
Some Open-Source versions of Axway products will live on after End-of-Life (EOL) Axway Amplify product announcements.  However, some products are closed-source and will NOT continue after the shut down in 2022.  
	</h4>
</a>
<p>&nbsp;</p>

> 👉 &nbsp;&nbsp; Stay tuned for more info as plans are being made to save the Titanium project and move it under the control of a independent group of developers.

<p>&nbsp;</p>
<hr>
<p>&nbsp;</p>
<p>&nbsp;</p>

[//]: # (header-end)



# @titanium/screenshot

[![@titanium/screenshot](https://img.shields.io/npm/v/@titanium/screenshot.png)](https://www.npmjs.com/package/@titanium/screenshot)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=brentonhouse/titanium-screenshot)](https://dependabot.com)


<br/>

* [📝 Description](#-description)
* [🚀 Getting Started](#-getting-started)
	* [Install `@titanium/screenshot` in root of project](#install-titaniumscreenshot-in-root-of-project)
	* [Usage](#usage)
* [✨Features](#features)
* [Author](#author)
* [📚Learn More](#learn-more)
* [📣 Feedback](#-feedback)
* [©️ Legal](#️-legal)


## 📝 Description

> Native modules that allows you to detect that a screenshot was taken on iOS.   
>     
> This is a repackaging of the compiled iOS module for [de.marcelpociot.screenshot](https://github.com/mpociot/TiScreenshotDetection) to allow for installation via npm.

## 🚀 Getting Started

### Install `@titanium/screenshot` in root of project

```bash
npm install @titanium/screenshot
```

### Usage

```JavaScript
const screenshotDetector = require('@titanium/screenshot');
screenshotDetector.addEventListener("screenshotTaken", function(e)
{
	alert( "Screenshot taken!" );
});

```

## ✨Features

* [x] Includes Titanium native iOS module: `de.marcelpociot.screenshot 1.0.0`



## Author

Marcel Pociot


## 📚Learn More

⭐  [de.marcelpociot.screenshot GitHub Repo](https://github.com/mpociot/TiScreenshotDetection) - Repo for original de.marcelpociot.screenshot module   


## 📣 Feedback

Have an idea or a comment?  [Join in the conversation here](https://github.com/brentonhouse/titanium-screenshot/issues)! 

## ©️ Legal

Alloy is developed by Appcelerator and the community and is Copyright © 2012-Present by Appcelerator, Inc. All Rights Reserved.

Alloy is made available under the Apache Public License, version 2. See their license file for more information.

Appcelerator is a registered trademark of Appcelerator, Inc. Titanium is a registered trademark of Appcelerator, Inc. Please see the LEGAL information about using trademarks, privacy policy, terms of usage and other legal information at http://www.appcelerator.com/legal.