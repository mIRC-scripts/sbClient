# Overview

sbClient is a [SearchBot](http://dukelupus.com/searchbot) client for mIRC.

sbClient automatically opens downloaded search results; you can use sbClient to make very fast local searches in downloaded lists and it can group @find/@locator results. 

sbClient is capable of automatically requesting SearchBot triggers from channel and can combine results from different search types.

## How to install

1. Unzip to mircdir/sbClient
2. In mIRC type: /load -rs1 sbClient\sbClient.mrc

## Setup

1. Open sbClient Options from the channel or command menus
2. Goto the searchbot tab
3. Click on a channel that has a searchbot in it, then click "Add"
4. Click on "Request Triggers"
5. Press "Ok"

## Usage

Press F4 to open the search dialog.

## Significant changes

### v2.24+

Within the search results window there some keyboard shortcuts you can use:
* You can request a file by pressing `r` or `ctrl-r` to request the file & remove from the results list.
  This will call the default autoget method set in options.
* You can search within the results by pressing `ctrl-z` & entering a wildcard search pattern. (NB: ctrl-f wont work in a @custom window)
* You can now send results to an internal queue to be downloaded.

## Acknowledgements

Code written by Duke Lupus and Ook.

mUnzip.dll presumably comes from [Info-ZIP](http://www.info-zip.org/) and is licensed under their own BSD-like license: http://www.info-zip.org/pub/infozip/license.htm
