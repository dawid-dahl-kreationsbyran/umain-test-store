# UMAIN TEST STORE

To work with the Shopify themes

</br>

---

## To download a theme for development

`theme download --env=development --dir=development`

</br>

## To work with a theme for development

In Shopify, go Online Store/Themes and find the theme you want to use for development. Then press Customize and find the ID in the URL, for example: "125548593291".

This command will push and overwrite the pre-existing development theme code on every save.

</br>

`theme watch --env=development --dir=development`

</br>

---

</br>

## To download a theme for testing

`theme download --env=test --dir=test`

</br>

## To work with a theme for testing

In Shopify, go Online Store/Themes and find the theme you want to use for development. Then press Customize and find the ID in the URL, for example: "125548593291".

This command will push and overwrite the pre-existing test theme code on every save.

</br>

`theme watch --env=test --dir=test`

</br>

---

</br>

## To deploy a theme to production

In Shopify, go Online Store/Themes and find the development theme you are using. Make sure to commit to Git. Then press Actions/Publish.
