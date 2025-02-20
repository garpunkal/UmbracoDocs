# Rich Text Editor Styles

It is possible to define specific styles and fonts for the Rich Text Editor (RTE). Once you've defined the styles, and enabled them on the RTE Data Type, the styles can be accessed directly in the content section.

![Rich Text Editor Styles](../../built-in-property-editors/rich-text-editor/images/rte-Formats.png)

## Creating RTE Styles

The RTE styles are created and managed in the Umbraco backoffice.

Find the **Stylesheets** folder in the Settings section. Right-click the folder, select '**Create...**' and choose _New Rich Text Editor style sheet file_. Give the new stylesheet a name and **Save** it - this will generate an empty CSS file.

At this point, you can start adding specific styles, that your editors can then use in the content section when creating and writing new content.

![Add specific RTE styles](../../../../../../../11/umbraco-cms/fundamentals/backoffice/property-editors/built-in-property-editors/rich-text-editor/images/rte-create-style.png)

The image above is an example of how an RTE style can be configured. When working with these styles, the **Preview** feature will show you how the style will look when applied.

Every style you add, will automatically be added to the CSS file. The file will be placed in the same location as the rest of your CSS files. It's possible to edit the file directly from the backoffice as well. Access it from the **Code** tab in the top-right corner.

![Edit CSS file directly in the backoffice](../../../../../../../11/umbraco-cms/fundamentals/backoffice/property-editors/built-in-property-editors/rich-text-editor/images/rte-code-tab.png)

## Using RTE Styles

In order for your editors to be able to use the styles when working with content, two things needs to be done.

### 1. Enable "Style select"

The styles will be accessed by the editors using the "Formats" dropdown in the toolbar of the RTE. In order the enable the dropdown, the "Style select" toolbar option needs to be checked.

This can be done through the Content section using infinite editing, or by finding and editing the RTE Data Type in the Settings section of the backoffice. Learn more about the configuration options in the [RTE Config](configuration.md) article.

### 2. Select the styles

You can have as many different styles for your RTEs as you want. You might want to have different styles for different RTE Data Types.

When configuring your RTE Data Types, you can select which stylesheets your content editors should be able to use.

![Choose stylesheets on the Data Type](../../../../../../../11/umbraco-cms/fundamentals/backoffice/property-editors/built-in-property-editors/rich-text-editor/images/rte-choose-stylesheet.png)
