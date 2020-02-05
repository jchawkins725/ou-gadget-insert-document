# OU-Gadget-Insert-PDF

A custom OmniUpdate gadget created for our users.

### Typical Workflow

Typically, our users would navigate to the pdf folder and upload their pdf. Then, they would go to their page, into an editable region WYSIWYG, type in the link text, highlight text, and link that text to their uploaded pdf. This workflow caused problems for users who would upload into the wrong folder, and/or they were not comfortable outside of the WYSIWYG.

### New Workflow

This custom gadget allows users to remain in the WYSIWYG while uploading and linking their pdf. It also greatly speeds up the process.

## Install
 
- Follow typical [OU Gadget installation](https://support.omniupdate.com/learn-ou-campus/administration/setup/gadgets.html)
- Change this variable: `var path = "/WebFiles/PDFs"` to your pdf folder
- Change hidden div to your site specifics
