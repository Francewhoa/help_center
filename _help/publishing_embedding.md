---
layout: default
title: Publishing and Embedding
---

# Publishing and Embedding

#### In this article:

* [Making Documents Public](#making-documents-public)
  - [Changing a document's access level](#to-change-a-documents-access-level)
  - [Setting a publication date](#to-set-a-publication-date)
* [Linking to a document, page, or note](#linking-to-a-document-page-or-note)
- [Embedding documents](#embedding-documents)
    * [Full document embed](#full-document-embed)
    * [Single page embed](#single-page-embed)
    * [Note embed](#note-embed)
    * [Document list embed](#document-list-embed)
* [How to embed documents](#how-to-embed-documents)
    - [Preparing to embed a document](#preparing-to-embed-a-document)
    - [Embed full document viewer](#embed-full-document-viewer)
    - [Embed a single page from a document](#embed-a-single-page-from-a-document)
    - [Embed a note from a document](#embed-a-note-from-a-document)
    - [Embed a list of documents](#embed-a-list-of-documents)
* [Wordpress shortcodes](#wordpress-shortcodes)
* [oEmbed service](#oembed-service)

***

**Ready to share your documents with readers?** Either by embedding our custom viewer or using oEmbed, you can publish individual documents, embed a set of documents that readers can browse, or embed a single page or note from any document.

## Making Documents Public

Before you publish a document, page, note or document set, you'll want to make sure that the document or documents are public. You can either **change the access level of the document** to make it available to the public immediately, or **set an automatic publication date**.

#### To Change a Document's Access Level:

1. Navigate to **"Your Documents"** and right click on the thumbnail of the document you would like to make public.
2. Select **"Set Access Level"** and switch the setting to **"Public Access"**.         

![Changing access levels](./images/publishing_embedding/publishing_embedding1.gif)

#### To Set a Publication Date: 

1. Navigate to **"Your Documents"** and select the document you want to make public.
2. Click **"Publish"**.
3. Click **"Set Publication Date"**.            
    ![Set publication date](./images/publishing_embedding/publishing_embedding2.gif)
4. Select the date you'd like the document to be made public in the dialog box and click **"Save"**. 
5. Your document will now automatically have its display setting changed to "public" at that date and time.

<p class="note"><b>NOTE:</b> DocumentCloud syncs to the time zone of whatever computer you are accessing it from.  For example, if your computer is set in Eastern Standard Time, whatever publication date and time you select will also by default be in Eastern Standard Time. You cannot manually configure your time zone.
</p>

## Linking to a Document, Page, or Note

The most simple way to share your work in DocumentCloud with readers is to **publish a URL to a document.** You can modify the URL to have the document open to a specific page or note. Follow these URL formats:

**Full document:**

`https://www.documentcloud.org/documents/282753-lefler-thesis.html`

**Document open to a specific page:**

`https://www.documentcloud.org/documents/282753-lefler-thesis.html#document/p22)`

**Document open to a specific note:**

`https://www.documentcloud.org/documents/282753-lefler-thesis.html#document/p57/a42283`

Click [here](annotate_documents.html/#linking-to-notes) for more information on how to share a url linking to a specific note.

# Embedding Documents

You have a few different options when it comes to embedding your DocumentCloud documents on a website.

## Full Document Embed

**Good for:** Allowing your readers to browse a multi-page document. If you have annotated the document, readers can click through your annotations in an interactive format just as you can in the DocumentCloud workspace.

![Full document embed example 1](./images/publishing_embedding/fullembed.png)

![Full document embed example 2](./images/publishing_embedding/fullembed2.png)


*** 

## Single Page Embed 

**Good for:** Sharing single-page documents with readers.

![Single page embed example 1](./images/publishing_embedding/pageembed.png)

*** 

## Note Embed

**Good for:** Folding small sections of primary source documents into your published story. 

![Note embed example 1](./images/publishing_embedding/noteembed.png)

![Note embed example 2](./images/publishing_embedding/noteembed2.png)


*** 

## Document List Embed

**Good for:** Sharing an entire collection of documents pertinent to a story or investigation with readers. 

![Document list embed 1](./images/publishing_embedding/listembed.png)

![Document list embed 2](./images/publishing_embedding/listembed2.png)


*** 

## How to Embed Documents

#### Preparing to Embed a Document

Before you embed a document on your site, we encourage you to fill out a couple of additional pieces of information about the document. Open the document to take one more look over the document's **title**, **description**, **source**, and **public notes**. If everything is as you like it, you're ready to continue.

To access embed options, select the document you want to embed and click on **"Publish"** in the toolbar.

![Embedding preparation 1](./images/publishing_embedding/publishing_embedding3.gif)

## Embed Full Document Viewer
1. Select "Embed Document Viewer" from the "Publish" dropdown
![Embedding full document viewer 1](./images/publishing_embedding/embeddocviewer.png)


2. Review Document

    ![Embedding full document viewer 2](./images/publishing_embedding/publishing_embedding5.gif)

    First, you may provide the link to the article referencing the document to enable a **"Related Article"** link within the document viewer. (This guides readers who stumble across the document from a web search to the article's original context, a.k.a your published piece.) You will be alerted if your document needs to be made public.


3. Configure the Document Viewer
![Embedding full document viewer 3](./images/publishing_embedding/publishing_embedding4.gif)

    You can control all of the below settings to customize the particular display of your document viewer embed:    
    • The size of the document viewer (full page layout, fixed size box)    
    • Which page the document opens to by default   
    • Show/hide the sidebar     
    • Show/hide the text tab    
    • Whether or not to link to the original PDF (allowing your readers to download the document)

4. Copy and Paste the Embed Code
![Embedding full document viewer 4](./images/publishing_embedding/publishing_embedding7.gif)

    • DocumentCloud will generate two pieces of code: an **HTML embed code**, and a **Wordpress shortcode**.    
    • Simply **copy and paste** the HTML code to a page on your site. If you have the [DocumentCloud Wordpress plugin](https://wordpress.org/plugins/documentcloud) installed, paste it into the body of your article.


## Embed a Single Page from a Document
1. Select "Embed a Page" from the "Publish" dropdown

    ![Embedding single page 1](./images/publishing_embedding/embedpage.png)

2. Select a Page to Embed

    ![Embedding single page 2](./images/publishing_embedding/publishing_embedding8.gif)
3. Copy and Paste the Embed Code

    ![Embedding single page 3](./images/publishing_embedding/publishing_embedding7.gif)

    • DocumentCloud will generate two pieces of code: an **HTML embed code**, and a **Wordpress shortcode**.    
    • Simply **copy and paste** the HTML code to a page on your site. If you have the [DocumentCloud Wordpress plugin](https://wordpress.org/plugins/documentcloud) installed, paste it into the body of your article.


## Embed a Note from a Document
1. Select "Embed a Note" from the "Publish" dropdown

    ![Embedding notes 1](./images/publishing_embedding/embednote.png)
2. Select a Note to Embed

    ![Embedding notes 2](./images/publishing_embedding/publishing_embedding9.gif)
3. Copy and Paste the Embed Code

    ![Embedding notes 3](./images/publishing_embedding/publishing_embedding7.gif)

    • DocumentCloud will generate two pieces of code: an **HTML embed code**, and a **Wordpress shortcode**.     
    • Simply **copy and paste** the HTML code to a page on your site. If you have the [DocumentCloud Wordpress plugin](https://wordpress.org/plugins/documentcloud) installed, paste it into the body of your article.

## Embed a List of Documents
1. Select "Embed Document List" from the "Publish" dropdown

    ![Embedding lists 1](./images/publishing_embedding/embeddoclist.png)
2. Configure the Embedded Documents

    ![Embedding lists 2](./images/publishing_embedding/publishing_embedding10.gif)

    You can control all of the below to customize how your document list embed appears: 
    • The title of your document list   
    • The order your documents appear in    
    • How many documents thumbnails are shown per page  
    • Enable/disable the search bar

3. Copy and Paste the Embed Code

    ![Embedding lists 3](./images/publishing_embedding/publishing_embedding7.gif)

    • DocumentCloud will generate two pieces of code: an **HTML embed code**, and a **Wordpress shortcode**.    
    • Simply **copy and paste** the HTML code to a page on your site. If you have the [DocumentCloud Wordpress plugin](https://wordpress.org/plugins/documentcloud) installed, paste it into the body of your article.


## Wordpress Shortcodes
Users who publish via Wordpress can install a **Wordpress plugin** that lets you embed DocumentCloud resources using shortcodes.

#### How to embed documents using Wordpress shortcodes
1. **Download** the [DocumentCloud Wordpress plugin](https://wordpress.org/plugins/documentcloud).
    ![Wordpress shortcode 1](./images/publishing_embedding/wordpress.png)
2. **Install and activate** it according to the directions.
3. During the last step of the embed preparation process on DocumentCloud, you will be given both a regular embed code and a Wordpress embed code.
    ![Wordpress shortcode 2](./images/publishing_embedding/wordpress2.png)
4. **Copy and paste** the Wordpress embed code into the body of your Wordpress article.

#### Customizing Wordpress embeds
You also can pass additional parameters to control the size and attributes of the Wordpress embed.

* **To set the embed to a particular width**, add [ `width=____px` ] to the end of the embed code.

    * `~/documents/282753-lefler-thesis.html" width="800"]`

* **To have the embed pre-scroll to a particular page**, add [ `page="__"` ] to the end of the embed code.
    * `~/documents/282753-lefler-thesis.html" page="3"]`

* **For a page, use any page-specific URL:**
    * `~/282753-lefler-thesis.html#document/p22"]`


* **For a note, use any note-specific URL:**
    * `~/documents/282753-lefler-thesis.html#document/p1/a53674"]`

<p class="note"><b>NOTE:</b> If you don't indicate a width (or manually disable responsive widths with `responsive="false"`), then the document will automatically narrow and widen to fill available width.</p>

## oEmbed Service

[**oEmbed**](https://oembed.com) is a Web standard for providing embedded content on a site via a request to the URL of the resource. If a content management system supports oEmbed, you can **simply paste in the URL to a DocumentCloud resource**, and the CMS will fetch it via our oEmbed API and embed it.

* **Example document URL for oEmbed**
    * `https://www.documentcloud.org/documents/1234-document-name.html`

* **Example page URL for oEmbed**
    * `https://www.documentcloud.org/documents/1234-document-name/pages/2.html`

* **Example note URL for oEmbed**
    * `https://www.documentcloud.org/documents/1234-document-name/annotations/220666.html`


<p class="note"><b>NOTE:</b> Check with your organization's systems administrator about whether your CMS supports oEmbed.</p>

