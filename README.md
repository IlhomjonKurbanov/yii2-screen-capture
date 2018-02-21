<p align="center">
    <a href="http://www.yiiframework.com/" target="_blank">
        <img src="http://static.yiiframework.com/files/logo/yii.png" width="400" alt="Yii Framework" />
    </a>
</p>

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=contact@inquid.co&item_name=Yii2+extensions+support&item_number=22+Campaign&amount=5%2e00&currency_code=USD)


# Screen capture and sharing

This repo is an exploration of screen capture in browsers, including using screen capture streams in WebRTC sessions with [Twilio Video](https://www.twilio.com/docs/api/video).

## Chrome extension

In the `/extension` directory is a minimal implementation of a Chrome extension that will give access to strams from the [`chrome.desktopCapture` API](https://developer.chrome.com/extensions/desktopCapture).

## Screen capture in Chrome

In the `/chrome` directory is an HTML page that takes advantage of the extension and captures the desktop to show within a `<video>` element on the page.

*Note*

You will need to load your own version of the Chrome extension into your browser and replace `YOUR_EXTENSION_ID_HERE` with your own extension ID.

You will also need to serve the file from a local web server so that you can visit it on localhost.

SUPPORT
-----
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=contact@inquid.co&item_name=Yii2+extensions+support&item_number=22+Campaign&amount=5%2e00&currency_code=USD)
