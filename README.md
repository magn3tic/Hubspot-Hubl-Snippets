# hubspot-hubl-snippets

We created this extension for a better Hubspot developer experience.

## Features

We currently support the following all Hubl modules. More information here: http://designers.hubspot.com/docs/hubl/hubl-supported-modules

## Supported Modules

## Blog Comments - hubbc

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#blog-comments)

#### Description: A blog comments module renders the comments embed code on a blog template. This Javascript embed code loads the comments form and comments, based upon your configuration in Content  Settings. 

## Blog social sharing - hubbss

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#blog-social-sharing)

#### Description: Blog social sharing renders share counters on your blog posts (if enabled in Content Settings).

## Blog subscription - hubbs

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#blog-subscription)

#### Description: A blog subscription module renders the blog subscriber form for a particular blog. This form is automatically created whenever a blog is created in Content Settings, and there is always one subscription form per blog. Please note that the subscribe form's fields are configured within the Forms editor UI.

## Boolean - hubbool

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#boolean)

#### Description: A boolean module creates a checkbox in the UI that prints "true" or "false." In addition to printing the value, this module is useful for defining conditional template logic, when combined with the parameter export_to_template_context. 

## Choice - hubch

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#choice)

#### Description: A choice module creates a dropdown in the content editor UI that prints the value selected by the user. Choice modules are great for giving your users a preset set of options, such as printing the type of page as a page header. In addition to printing the choice value, this module is useful for defining conditional template logic, when combined with the parameter export_to_template_context.

## Color - hubclr

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#color)

#### Description: The color module generates a color picker in the page editor UI that prints a HEX color value to a template. Please note that this module can only be used in templates, not CSS files.  If using this tag in a `<style>` or inline CSS, you will want to use the `no_wrapper=True` parameter to remove the wrapper `<span>` wrapper.

## CTA - hubcta

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#cta)

#### Description: A Call to Action or CTA module allows users to add a HubSpot Call to Action button to a predefined area of a page. 

## Custom HTML - hubhtml

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#custom-html)

#### Description: A custom HTML module allows users to enter raw HTML into the content editor. If you need to add extensive default HTML to the module, you may want to use block syntax. 

## Custom modules - hubcmod

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#custom-modules)

#### Description: Custom Modules allow HubSpot designers to create a custom group of editable content objects to be used across templates and pages on HubSpot’s COS, while still allowing marketers to control the specific content appearing within those modules on a page-by-page basis. Custom modules must be built in the Custom Module editor, but they can be included into coded templates and HubL modules. Custom modules require two parameters in order to specify which module to load

## Email Backup Unsubscribe - hubeunsub

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#email-backup-unsubscribe)

#### Description: The backup unsubscribe module renders for email recipients, if HubSpot is unable to determine their email address, when that recipient tries to unsubscribe. This module renders a form for the contact to enter his or her email address to unsubscribe from email communications. It should be used on an Unsubscribe Backup system template.

## Email subscriptions - hubesub

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#email-subscriptions)

#### Description: This module renders when an email recipient goes to edit his or her subscription preferences. It should be used on a Subscription Preference system template.

## Email subscriptions confirmation - hubesubcon

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#email-subscriptions-confirmation)

#### Description: The email subscriptions update confirmation is a module that can be added to the thank you template for when a recipient updates his or her subscription preferences or unsubscribes. It should be used on a Subscription Update system template.

## Flexible column - hubflexcol

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#flexible-column)

#### Description: Flexible columns are vertical columns in a template that allow the end user to insert and remove a variety of modules of their choosing into the template, while editing in the content editor. When coding a flexible column with HubL, you can choose to wrap other HubL modules to make them appear in the flexible column by default. The sample code below shows the basic syntax and an sample flex column with a rich-text and form module contained as default content. Please note that flexible columns can only be added to page templates, not blog or email templates.

## Follow me - hubfollow

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#follow-me)

#### Description: Follow me modules render icons that link to your various social media profiles. The icons that display are based upon your Social Settings.

## Form - hubform

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#form)

#### Description: Allows users to select a HubSpot form to add to their page.

## Gallery - hubgal

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#gallery)

#### Description: Generates a HubSpot gallery module. This gallery module is based on Slick. While you can create a gallery module with standard module HubL syntax, If you want to predefine default slides using HubL, you must use block syntax

## Global Module - hubgmod

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#global-module)

#### Description: Add a predefined global module to coded template or HubL module. Global modules are created using the drag and drop template builder UI. Please note that using a global module tag is different than including an html file or global group, in a template. The global module is associated with the HubL tag based on its unique name

## Footer - hubfooter

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#footer)

#### Description: Renders copyright information with the year and company name specifed in Content Settings (Email > Footer Information).

## Google Search - hubgsearch

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#google-search)

#### Description: This module creates a search field that redirects to a Google page of search results for your site. If you want to redirect to a search results page hosted on your site, you would need to set up a Custom Search Engine with Google or use a third-party search provider like Swiftype.

## Header - hubheader

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#header)

#### Description: Generates a header module that will render text as an h1-h6 tag.

## Image - hubimg

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#image)

#### Description: Creates a image module that allows users to select an image from the content editor.

## Image src - hubimgsrc

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#image-src)

#### Description: An image src module creates a image selector in the content editor, but rather than printing a img tag, it renders the URL of the image. This tag is generally used with no_wrapper=True parameter, so that the image src can be added to inline CSS or other markup. An alternative to using this tag is to use the export_to_template_context parameter.

## Linked Image - hublinkimg

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#linked-image)

#### Description: Creates a user-selectable image that is wrapped in a link. This module has all of the parameters of an image module with two additional parameters that specify the link destination URL and whether the link opens in a new window.

## Logo - hublogo

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#logo)

#### Description: A logo module renders your company's logo image from Content Settings. 

## Menu - hubmenu

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#menu)

#### Description: Generates an advanced menu based on a menu tree in Content Settings > Advanced Menus.

## Password Prompt - hubpassp

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#password-prompt)

#### Description: Adds a password prompt to password-protected pages.

## Post Filter - hubpostfil

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#post-filter)

#### Description: Creates a linked listing of posts by topic, posts by month, or posts by author.

## Post Listing - hubpostlist

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#post-listing)

#### Description: Adds a listing of most popular or top posts.

## Require_css - hubreqcss

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#require-css)

#### Description: A HubL tag that enqueues an inline style to be rendered.

## Require_js - hubreqjs

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#require-js)

#### Description: A HubL tag that enqueues an inline script to be rendered.

## Rich text - hubrt

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#rich-text)

#### Description: Creates a WYSIWYG content editor. 

## RSS listing - hubrsslist

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#rss-listing)

#### Description: Loads a list of content from an internal or external RSS feed.

## Section header - hubsech

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#section-header)

#### Description: Generates an h1 header and <p> subheader.

## Simple menu - hubsmenu

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#simple-menu)

#### Description: Simple menus allow you to create basic navigation menus that can be modified at the page level. Unlike regular menu modules, simple menus are not managed from the Advanced Menus screen in Content Settings, but rather from the template and page editors. You can use block syntax to set up a default menu tree.

## Social sharing - hubsocs

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#social-sharing)

#### Description: Social sharing modules generate social media icons that can be used to share a particular page. This module can be used with block syntax to customize the icon images and more.

## Spacer - hubspacer

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#spacer)

#### Description: A spacer module generates an empty span tag. This tag can be styled to act as a spacer. In drag and drop layouts, the spacer module is wrapped in a container with a class of span1-span12 to determine how much space the module should take up in the twelve column responsive grid. 

## Text - hubt

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#text)

#### Description: Creates a single line of text. This module can be useful to be mixed into your markup, when used in conjunction with the no_wrapper=True parameter. For example, if you wanted your end users to be able to define a destination of a predefined anchor, you could populate the href with a text module with no_wrapper=True.

## Textarea - hubta

#### [Docs](http://designers.hubspot.com/docs/hubl/hubl-supported-modules#textarea)

#### Description: A textarea is similar to a text module in that it allows users to enter plain text, but it gives them a larger area to work in the content editor. This module does not support HTML. If you want to use directly within a predefined wrapping tag,  add the no_wrapper=true parameter.



## Known Issues

None currently

## Release Notes

Version 0.0.2 now features full support for Hubl Modules.

-----------------------------------------------------------------------------------------------------------

**Enjoy!**