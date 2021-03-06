# 4. Extras

## Table of contents

  1. [Installation and Setup](1-Installation-and-Setup.md)
  2. [Configuration](2-Configuration.md)
  3. [Usage](3-Usage.md)
  4. [Extras](4-Extras.md)
  5. [FAQ](5-FAQ.md)

## [reCaptcha V2] g-recaptcha tag attributes

| Attributes            | Value            | Default | Description                                                                                                                                                                                      |
| --------------------- | ---------------- |:-------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| data-sitekey          |                  |         | Your sitekey                                                                                                                                                                                     |
| data-theme            | dark / light     | light   | Optional. The color theme of the widget.                                                                                                                                                         |
| data-type             | audio / image    | image   | Optional. The type of CAPTCHA to serve.                                                                                                                                                          |
| data-size             | compact / normal | normal  | Optional. The size of the widget.                                                                                                                                                                |
| data-tabindex         |                  | 0       | Optional. The tabindex of the widget and challenge. If other elements in your page use tabindex, it should be set to make user navigation easier.                                                |
| data-callback         |                  |         | Optional. Your callback function that's executed when the user submits a successful CAPTCHA response. The user's response, `g-recaptcha-response`, will be the input for your callback function. |
| data-expired-callback |                  |         | Optional. Your callback function that's executed when the recaptcha response expires and the user needs to solve a new CAPTCHA.                                                                  |

## [Invisible reCaptcha] g-recaptcha tag attributes.

| Attributes    | Value                             | Default     | Description                                                                                                                                                                                      |
| ------------- | --------------------------------- |:-----------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| data-sitekey  |                                   |             | Your sitekey                                                                                                                                                                                     |
| data-badge    | bottomleft / inline / bottomright | bottomright | Optional. Reposition the reCAPTCHA badge. 'inline' allows you to control the CSS.                                                                                                                |
| data-type     | audio / image                     | image       | Optional. The type of CAPTCHA to serve.                                                                                                                                                          |
| data-size     | compact / normal                  | normal      | Optional. The size of the widget.                                                                                                                                                                |
| data-tabindex |                                   |             | Optional. The tabindex of the widget and challenge. If other elements in your page use tabindex, it should be set to make user navigation easier.                                                |
| data-callback |                                   | onSubmit    | Optional. Your callback function that's executed when the user submits a successful CAPTCHA response. The user's response, `g-recaptcha-response`, will be the input for your callback function. |

## Examples

Check the [examples folder](https://github.com/ARCANEDEV/noCAPTCHA/tree/master/examples) for more usage details.
