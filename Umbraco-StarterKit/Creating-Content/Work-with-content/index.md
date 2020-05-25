---
versionFrom: 8.0.0
---

# Working with content

----------
This article should contain all necessary information needed to work with content in an Umbraco Uno project.

* Update content
* Create new content
* Delete content
* Save
* Publish / Schedule for publish
* Preview
* Sort order
* Roll back

This article should link out to more tutorial-like articles; "Create a landing page", "Setup a feed", "Create a frontapge" (or something...)

----------

Whether you're building your website around the sample content or you're setting everything up from scratch, content is the most important part of your website. Every landing page, section and article are created and maintained from the **Content** section of the Umbraco Backoffice.

In Umbraco Uno there are a hand-full of options for creating content along with a long list of customizable elements. This article aims to give you the basics of working with content be it updating, creating or even deleting.

## Overview

* [Creating content](#creating-content)
* [Updating content](#updating-content)
* [Deleting content](#deleting-content)

## Creating content

Whether you're creating a new landing page, a new section or a feed area, the process of creating a new piece of content follows the same flow:

1. In the Content tree, hover over the piece of content that you want to create a new piece of content under - this could be the Start node or another landing page
2. Selecting the three little dots will open a "Create" dialog
3. From the "Create" dialog, choose which type of content you want to create - choose between **Page** and **Feed**
4. Select the chosen type and a workspace area will now display a blank piece of content
5. Give the content item a name
6. Setup the page
7. Finalize the creation of the page by **Saving** it

While working on a piece of content you can use the *Preview* feature to preview how the page looks. Once the page is done you can choose to either publish it right away, or schedule when the page should be published.

When you have a website that uses multiple languages, you can create a new *variant* of the content item for each language you're using. Learn more about how this is done in the [Multi-lingual website] article.

## Updating content

To update and make changes to already existing content, follow these steps:

1. Select the content item the needs updating from the Content tree in the Content section
2. Use the workspace area to make the needed updates to the content item
3. Use the *Preview* feature to preview the new changes
4. Save and/or publish the item

## Deleting content

In some cases you might need to delete page or entire sections of your website. That can be done by following these steps:

1. In the Content tree, locate the content item or section that you need to delete
2. Right-click the content item - when deleting an entire section, right-click the parent item
3. From the dialog, choose "Delete..."
4. Select "OK" to confirm the deletion

Once a piece of content or a section has been deleting, it will be mvoed to the **Recycle Bin** which is accessible from the Content tree. It is possible to **restore** deleted content by either moving the item back under the start node or by right-clicking it in the Content tree and choose "Restore".

:::warning
When deleting a piece of content it is important to note that **all** language variants as well as any sub pages will be deleted as well.
:::