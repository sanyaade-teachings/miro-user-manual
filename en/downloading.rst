===================
 Downloading items
===================

.. index:: downloading; item from podcast

Downloading an item from a podcast
==================================

To download an item from a podcast:

1. Select the tab for the podcast in the sidebar.

2. Browse through the list of items in that podcast in the main view.

3. Find the item you want to download and click on the **Download**
   button.

.. SCREENSHOT
   Screenshot of Miro showing the download button of an item in 
   an item list.

.. image:: _static/downloading_podcast_item.png
   :width: 800px


.. index:: downloading; item from video search

Downloading an item from a video search
=======================================

1. Perform the video search.

2. Click on the **Download** button for the item you want to download.

.. SCREENSHOT
   Screenshot of Miro showing the download button of an item in the
   video search list.

.. image:: _static/downloading_video_search_item.png
   :width: 800px


.. index:: downloading; item from source 

Downloading an item from Miro Guide or a Source
===============================================

While browsing around in a website, you will find links to media items.
Clicking on one of these links will download the item in Miro.

.. SCREENSHOT
   Screenshot of Miro showing a website with links.

.. image:: _static/downloading_site_with_links.png
   :width: 800px

Miro may recognize media items on websites like YouTube and you will
see a **Download this video** button in the browser navigation bar.
Clicking on that button will download the item.

.. SCREENSHOT
   Screenshot of Miro showing a website with the "Download this video"
   button showing.

.. image:: _static/downloading_download_this_video.png
   :width: 800px


.. index:: downloading; from url

Downloading an item
===================

Miro can also download items that aren't in feeds that you've
subscribed to or from video search.

1. Select the **File** -> **Download from a URL** menu item.  This will
   launch the **New Download** dialog window.

2. Fill in the url of the item.

   *On Windows and GTKX11 platforms*, you can press Shift+Insert or
   Ctrl+V to paste a url from the system clipboard into this dialog
   box.

   *On OSX*, you can press Apple+V to paste a url from the system
   clipboard into this dialog box.

3. Click on the **OK** button.

Miro will now attempt to download this item.  If the download is
successful, then the item will show up in the sidebar in the
**Videos** or **Music** tab of the **Library** depending on whether
the media item is video or audio.

If the url leads to something that's not a media item, Miro will pop
up a dialog box telling you as such and asking you what you want it to
do.

.. SCREENSHOT
   Screenshot of "This is not downloadable" dialog

.. image:: _static/downloading_this_is_not_downloadable.png

.. Note::

   Miro can handle YouTube page urls as well.  For example, this url
   is the YouTube page for Nicholas Reville talking about
   Participatory Culture Foundation and Democracy Player (the old name
   for Miro) back in 2006:

   http://www.youtube.com/watch?v=wuGbLY-l930


.. index:: downloading; torrents

Torrents
========

Miro is a torrent client and can download torrents.  You can download
a torrent with Miro in the same ways that you can download any other
media item.

Once a torrent has completed downloading, it switches to seeding.

The torrent will continue seeding until you press the **Stop seeding**
button on the item.

If you want to set an upload ratio so that Miro will automatically
stop seeding an item when a specified upload to download ratio has
been reached, you can set that in the :ref:`configuring-chapter`.

