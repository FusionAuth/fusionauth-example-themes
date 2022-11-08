# FusionAuth Example Themes

This is a set of customizable FusionAuth themes. These should be production ready.

## Installation

To install a sample theme: 

* Install FusionAuth. (More here: https://fusionauth.io/docs/v1/tech/installation-guide/ )
* Log in to FusionAuth and copy the default theme. Name it something else, like 'My Theme'.
* Review the different sample themes contained in this repository. 
* When you find one you like, copy the CSS from the CSS file into the **Stylesheet (CSS)** section of the 'My Theme'.
* Customize the sample theme as detailed below (optional).
* Save the theme.
* Enjoy your new look and feel.

## Customization

You can tweak the colors of this theme by editing the CSS file and modifying the CSS variables at the top:

```
:root {
  --main-text-color: #424242;
  --main-accent-color: #083b94;
  --input-background: #fbfbfb;
  --body-background: #f7f7f7;
  --tooltip-background: #e2e2e2;
  --error-color: #ff0000;
  --error-background: #ffe8e8;
  --border-color: #dddddd;
  --logo-url: url(https://fusionauth.io/assets/img/samplethemes/changebank/changebank.svg);
  --font-stack: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
```

Of course, if needed, you have the full flexibility of FusionAuth themes as well. Learn more about that here: https://fusionauth.io/docs/v1/tech/themes/

## Eye Candy

Change Bank

<img src="/change-bank/change-bank-example.png" />
