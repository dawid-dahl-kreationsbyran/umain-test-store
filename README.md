# UMAIN TEST STORE

## Getting started

To start working with the Shopify themes for development or testing, create a "config.yml" file in the root of the project. You'll find an example with dummy data in the config.example.yml file. Fill in the correct information by logging into Shopify.

To get the **password**, go to Apps. Then download Theme Kit Acces. When you have it, send the password to an email of your choice. Previously one had to use a private app for this, but Theme Kit Access is the more recent method of authenticting, recommended by Shopify.

To get the **theme_id**, you'll find instructions under "To work with a theme for testing/development" below.

To get the **store**, you'll find that in the URL of the store.

<br>

## To download a theme for development

`theme download --env=development --dir=development`

Make sure you've set the **theme_id** correctly in config.yml.

This will download the theme into development directory.

## To work with a theme for development

In Shopify, go Online Store/Themes and find the theme you want to use for development. Then press Customize and find the ID in the URL, for example: "125548593291".

This command will push and overwrite the pre-existing development theme code on every save.

`theme watch --env=development --dir=development`

<br>

## To download a theme for testing

`theme download --env=test --dir=test`

Make sure you've set the **theme_id** correctly in config.yml.

This will download the theme into test directory.

## To work with a theme for testing

In Shopify, go Online Store/Themes and find the theme you want to use for development. Then press Customize and find the ID in the URL, for example: "125548593291".

This command will push and overwrite the pre-existing test theme code on every save.

`theme watch --env=test --dir=test`

<br>

## To download a theme for production

`theme download --env=production --dir=production`

Make sure you've set the **theme_id** correctly in config.yml.

This will download the theme into production directory.

## To work with a theme for production

Please do not work directly on a production theme here. Instead, when you are done developing in the development theme, publish it instead and regard it as the new production theme.

For hotfixes,

<br>

## To deploy a theme to production

In Shopify, go Online Store/Themes and find the development theme you are using. Make sure to commit to Git. Then press Actions/Publish.
