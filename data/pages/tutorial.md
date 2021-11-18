---
title: "Rosco Wiki Tutorial"
---
# Rosco Wiki Tutorial

  
===== Page =====

### Page Name

Each page has its own unique "address" which is the URL in Docuwiki. For example, the "address" for this page is:

    https://wiki.roscocloud.com/tutorial

And its page name is "tutorial".  

#### Page Name Requirements

1.  The page names in Rosco Wiki are always **lowercase** by default.  
    - The page names should be the same as the main topic/title.  
    - Allowed characters are letters, digits and some special characters.  
    - The **colon(":")** symbol is used to identify namespaces.  
    - The **underscore("\_")** symbol is strongly preferred over whitespace, plus, slash, percent, etc. And in fact, all those special characters will be changed to underscore by default.

#### Page Name Example

<u>*Installation Guide Portal*</u>

    https://wiki.roscocloud.com/installation_guide

<u>*Dual-Vision Homepage*</u>

    https://wiki.roscocloud.com/product:dual-vision_recording

<u>*Firmware page for Dual-Vision XC4*</u>

    https://wiki.roscocloud.com/product:dual-vision_recording:dual-vision_xc4:firmware

### Create & Edit a Page

\<color #ed1c24>***Before you create the page, you have to categorize the topic and determine where to put it.***\</color>

In Rosco Wiki, the way of creating new page is pretty intuitive.

Firstly, you need to choose a pagename. It's recommended to use the same name as the title. In this case, the example pagename will be:"example".  
Secondly, create an URL with the pagename and assign it in the desired layer. For example, if we want to create a example page in top layer,then the URL should be:

    https://wiki.roscocloud.com/example

If you want to put it under the product layer,then the URL should be:

    https://wiki.roscocloud.com/product:example

When you enter the page, the page will be displayed as following: <img src="/capture.png" class="align-center" width="800" />

Thirdly, click on the pen icon on the top right of the page to start editing the page. As long as the content is not empty, the new page will be created and you can go back to edit the page anytime you want.

\<color #ed1c24><u>***Please edit the existing page only if you can improve it. If you want to test something, please make your first steps on the playground.***</u>\</color>

If you have any other questions regarding the page section, you can always go to <https://www.dokuwiki.org/page>.

## Formatting Syntax

Rosco Wiki supports some simple markup language, which tries to make the datafiles to be as readable as possible. This page contains all possible syntax you may use when editing the pages. Simply have a look at the source of this page by pressing "Edit this page". If you want to try something, just use the [playground](/playground/playground) page.

### Basic Text Formatting

Rosco Wiki supports **bold**, *italic*, <u>underlined</u> and `monospaced` texts. Of course you can **<u>*`combine`*</u>** all these.

    Rosco Wiki supports **bold**, //italic//, __underlined__ and ''monospaced'' texts.
    Of course you can **__//''combine''//__** all these.

You can use ~subscript~ and ^superscript^, too.

    You can use <sub>subscript</sub> and <sup>superscript</sup>, too.

You can mark something as <s>deleted</s> as well.

    You can mark something as <del>deleted</del> as well.

**Paragraphs** are created from blank lines. If you want to **force a newline** without a paragraph, you can use two backslashes followed by a whitespace or the end of line.

This is some text with some linebreaks  
Note that the two backslashes are only recognized at the end of a line  
or followed by  
a whitespace \\\\this happens without it.

    This is some text with some linebreaks\\ Note that the
    two backslashes are only recognized at the end of a line\\
    or followed by\\ a whitespace \\this happens without it.

You should use forced newlines only if really needed.

### Links

DokuWiki supports multiple ways of creating links.

#### External

External links are recognized automagically: <http://www.google.com> or simply www.google.com - You can set the link text as well: [This Link points to google](http://www.google.com). Email addresses like this one: <boh@roscovision.com> are recognized, too.

    Rosco Wiki supports multiple ways of creating links. External links are recognized
    automagically: http://www.google.com or simply www.google.com - You can set
    link text as well: [[http://www.google.com|This Link points to google]]. Email
    addresses like this one: <boh@roscovision.com> are recognized, too.

The easiest way to insert an external link is using the "insert external link" icon in the tool bar when you are editing a page.

#### Internal

Internal links are created by using square brackets. It's recommended to use the "insert internal link" function in the toolbar on the top of the editing box.

Linking to a specific section is possible, too. Just add the section name behind a hash character as known from HTML. This links to [this Section](tutorial#internal).

    This links to [[tutorial#Formatting Syntax|This Section]].

Notes:

-   Links to [existing pages](https://wiki.roscocloud.com/wiki:syntax) are shown in a different style from [nonexisting](nonexisting) ones.
-   When a section's heading is changed, its bookmark changes, too. So don't rely on section linking too much.

For syntax, [Formatting Syntax](/wiki/syntax) is always the best place to go.

## Media Manager

### Introduction

In Roscowiki, you can insert files or pictures via Media Manager easily. To open the media manager, click the ![](https://www.dokuwiki.org/lib/images/toolbar/image.png) button in the page editing toolbar. When you want to manage media, but have no need for inserting media links, you can use the fullscreen media manager too. It is located on the top left hand-side under the search bar.  
<u>The current size limit is **2MB**.</u>

### Insert Images

When you click the ![](https://www.dokuwiki.org/lib/images/toolbar/image.png) button in the page editing toolbar,you'll see: <img src="/insert_picture.png" class="align-center" width="600" />  

#### Step 1

If you want to upload a image or file, just click the "select files" button and follow the instruction. When you click the "done" button after you finish uploading, the image will show up.  
All uploaded images will go to the same layer as the page do.  
If you want to use an existing image, you will find it directly like the DVXC3 image. Please make sure you choose the correct layer from the left hand-side.

#### Step 2

When you click on the image, a window as shown below will pop up: <img src="/capture1.png" class="align-center" width="400" />

***Link Target***:

-   Link to detailed page: it'll open the detailed information for this image(date,name,format etc.)
-   Direct link to original: it'll open the original image.
-   No link: Nothing linked to this image.
-   Show only the link: It'llshow the link of the image instead of the image itself.

  
***Alignment***:  
  
By using left or right whitespaces you can choose left, right or center alignment. Or you can choose the location from the alignment option above.

<img src="/wiki/dokuwiki-128.png" class="align-right" alt="dokuwiki-128.png" />

<img src="/wiki/dokuwiki-128.png" class="align-left" alt="dokuwiki-128.png" />

<img src="/wiki/dokuwiki-128.png" class="align-center" alt="dokuwiki-128.png" />

    {{ wiki:dokuwiki-128.png}}
    {{wiki:dokuwiki-128.png }}
    {{ wiki:dokuwiki-128.png }}

  
***Image size***:  

-   Small: **200** pixel in width
-   Medium: **400** pixel in width
-   Large: **600** pixel in width
-   Original: original size

## Tips

-   Almost every page requires a table of content on the top right hand-side. So section will be created via title hierarchies.The title hierarchies are controlled by the number of "=".  
    \* The basic formatting can be combined,like <u>**this**</u>, `this`,and \<color #ed1c24><s>this</s>\</color>.  
    \* The image and links to pages can be combined also.

## Troubleshooting Structure

Please see ***[SD Error (SD_E)](/rosco/product/dual-vision_recording/dual-vision_xc4/troubleshooting/sd_error)*** as an example. All problems should follow the same logic:

-   Document Last Revision
-   Observations
    -   Error Code
    -   Customer Environment
    -   Description (brief explanation of the issue and a picture if necessary)  
        \* Potential Possibilities  
        \* Diagnosis  
        \* Solutions
