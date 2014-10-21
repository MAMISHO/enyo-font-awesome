enyo-font-awesome
=================

A group of kinds for EnyoJS to add support for font-awesome awesomeness

Two kinds are provided: **fa.Icon** and **fa.IconButton**.

Example of usage:

```js
{kind: "onyx.Toolbar", components: [
    {
        kind: "fa.IconButton",
        name: "button",
        icon: "fa-cog",
        spin: true,
        pull: "left",
        label: "Tap me",
        ontap: "helloWorldTap"
    }
]}
```

The result is:

![Imgur](http://i.imgur.com/KhiEjBF.gifv)

The **fa.Icon** has almos the same properties as the **fa.IconButton** except it has no label or tap event.