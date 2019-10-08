---
class: projects
title: Wireframes — Folio for Verso Books
header: Wireframes
---

## 📕 Folio

Folio is the web-based CMS and fulfillment software used by Verso Books, the largest radical publishing house in the English-speaking world. The purpose of this project was to begin investigating a redesign of CMS to improve the user experience for Verso site administrators. Specifically, I wanted to address tools, functionality, and information organization so that the CMS seamlessly performs the tasks admins need it to perform; support a logical workflow; and modernize the look-and-feel. 

Originally, I demonstrated these wireframes in an interactive InVision prototype, but that project has since been deleted from my previous employer's account. 

### Books

![Edit books screen](ssets/docs/images/edit-book-persistent-nav.png)

I suggested that we merge functionality of two content types: _Books_ and _Editions_. All book-creation work would happen under the guise of Books site content type. An edition is a subset of a book, not an entirely independent content type. This design made it easier to access editions of a book with the an "edition switcher," so Verso needed only one index for one content type.

{: .info}
Foundational changes:

- Page organization. Most editorial content (title, description, press clippings) in the left column, and metadata (ISBN, subjects) in the right
Publication tools. Box on top right shows status of this entry in the CMS (Published/Draft), allows admins to edit slug, set expiration dates, etc. Moves “Delete” functionality away from its old, easily-clickable spot. On other, non-book screens (like blog post), you will be able to see who created the entry, and create parent-child relationships. Added “Preview” button to open page preview in a new window. New calendar selection tool.
- Edition switcher. A simple way to save changes between one edition of a book and another. Switcher allows user to select an existing edition, save, and switch, or create a new edition, save, and switch. 

Editorial changes: 

- Required fields. Required fields are now marked, friendly error messages display when user forgets to fill them out.
- WYSIWYG and mini-WYSIWYG. Much more flexible and modern content editing tools, including block quote, strikethrough, highlight, special characters, etc. (Not everything is seen here in the wire.) Spellcheck markers available. The teaser/keynote field supports a stripped down version of this tool for minimal edits, eliminating the need to use HTML. 
- Helper text. Simple help text for fields where the intent might not be totally clear to new users. Inline or on hover, for longer text. See Teaser, Images. Visibility.

Image management changes:

- Click to edit image metadata, or delete
- Click to drag-and-drop reorder
- Drag-and-drop to image area to upload new image (dashed button)

Content management changes:

- Modal. Open when user is choosing from existing primary content in CMS to associate with current content
	- Contributors: choose; add new stub or edit
	- Images: choose, drag-and-drop, edit metadata
	- Other books of interest
- Inline field. Open inline when user is creating or associating new content (e.g., press clippings) or secondary content (subjects)
	- Press clippings
	- Subjects/Regions
	- Inline fields are reorderable
	- Cog menu shows inline field options, add new above/below, delete, etc.




