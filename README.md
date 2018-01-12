# Vimeo Upload

Javascript based upload to get a video URL from Vimeo without having
to upload it on Drupal first. The result URL can then be used with
[Media Entity Vimeo](https://www.drupal.org/project/media_entity_vimeo).

**Work in progress**

## Use case

- When you want to improve AX, so authors do not have to connect to
Vimeo and go back to Drupal.
- When you do not want to store the video file on your server.

## Related project

[Vimeo field Uploader](https://www.drupal.org/project/vimeo_field_uploader)

## Installation

1/ Install and enable this module as usual

`composer require drupal/vimeo_upload`

2/ Download [this repository](https://github.com/websemantics/vimeo-upload)
in the libraries directory

So you have /web/libraries/vimeo-upload/vimeo-upload.js

3/ Enable the module 

`drush en vimeo_upload`

## Configuration

### Vimeo

1. Create a [Vimeo](http://vimeo.com/) account
2. Create a [Vimeo app](https://developer.vimeo.com/apps)
3. Request upload access for this application
4. Generate access token for your application on the __Authentication__ tab with
following permissions: Public, Private, Edit, Upload.

### Drupal

@todo WIP
