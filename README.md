# Introduction

This Github is about the VVBL association, for Volley Ball in Vertou. The code is OpenSource (EPL license)

The website is at (http://www.vvbl.org).

# Development

It uses [Bootstrap](http://startbootstrap.com/). So, it is plain HTML/CSS/JS files.

VVBL Website was created by Etienne Juliot ([@ejuliot](https://github.com/ejuliot) and is maintained by Olivier Varloud [@varloud](https://github.com/ovarloud/) and Josselin Lafay


## How to install?

To modify any part of this site, you can use any IDE you want:
* Eclipse IDE
* Eclipse CHE hosted on Redhat OpenShift (https://www.eclipse.org/che/getting-started/cloud/ or a direct to a pre-configured workspace at https://che.openshift.io/dashboard/#/ide/ejuliot/VVBL.github.ionq0kg)
* GitPod (https://gitpod.io/#https://github.com/VVBL/VVBL.github.io/tree/master) 
* Github CodeSpaces
* A plain text editor with Git

## What to modify?

The core of the site is in the index.html file. Thanks to Bootstrap, it is easy to read with raw HTML. You can update any part of this page by copy/paste the existing code (such as the carousel). 
If you use the right css class of bootstrap, the website will continue to work on any device and screen sizes.

Every year, you have to update:
* the contact wizards (search telephoneModal and inscriptionModal)
* dates of the first training sessions in septembre
* the yearly season
* the inscription file for the next season

The downloaded file are stored in ressources folder. Originals have to be stored in the VVBL drive (those are just copies).
Images are stored in img folder.

When the site is updated with a significative change, announce it on the VVBL's facebook page.

## How to test?

You can test locally in you work with a local IDE by just open a browser on .html file.
If you are using a web ide, you can just open a preview.

When the doc is push on the official branch (https://github.com/VVBL/VVBL.github.io), it is automaticly live and testable on http://www.vvbl.org.

## How to push your contribution?

Two solutions: 
* directly push to https://github.com/VVBL/VVBL.github.io or 
* push to your own fork then create a pull request. The workflow is up to the yearly dev team.