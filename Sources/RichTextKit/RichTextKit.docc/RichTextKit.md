# ``RichTextKit``

RichTextKit helps you view and edit rich text in SwiftUI, UIKit and AppKit.


## Overview

![SwiftKit logo](Logo.png)

RichTextKit has a SwiftUI `RichTextEditor` that builds on a multi-platform `RichTextView` that supports text style (bold, italic, underline, strikethrough etc.), font, font sizes, text and background colors, text alignment, images etc.

The online documentation is currently iOS only. To generate documentation for other platforms, open the package in Xcode, select a simulator then run `Product/Build Documentation`.



## Installation

RichTextKit can be installed with the Swift Package Manager:

```
https://github.com/danielsaidi/RichTextKit.git
```

If you prefer to not have external dependencies, you can also just copy the source code into your app.



## Getting started

The <doc:Getting-Started> article has a guide to help you get started with RichTextKit.



## Repository

For more information, source code, an if you want to report issues, sponsor the project etc., visit the [project repository](https://github.com/danielsaidi/RichTextKit).



## License

RichTextKit is available under the MIT license. See the [LICENSE][License] file for more info.



## Topics

### Essentials

- <doc:Getting-Started>
- ``RichTextEditor``
- ``RichTextView``
- ``RichTextContext``

### Foundation

- ``RichTextCoordinator``
- ``RichTextPresenter``
- ``RichTextReader``
- ``RichTextWriter``
- ``RichTextViewComponent``

### Actions

- ``RichTextAction``
- ``RichTextActionButton``
- ``RichTextActionButtonGroup``
- ``RichTextActionButtonStack``

### Alignment

- ``RichTextAlignment``
- ``RichTextAlignmentReader``
- ``RichTextAlignmentWriter``
- ``RichTextAlignmentPicker``

### Attributes

- ``RichTextAttribute``
- ``RichTextAttributes``
- ``RichTextAttributeReader``
- ``RichTextAttributeWriter``

### Colors

- ``ColorRepresentable``
- ``RichTextColorReader``
- ``RichTextColorWriter``
- ``RichTextColorPicker``
- ``RichTextColorPickerStack``

### Commands

- ``RichTextCommandsAlignmentOptionsGroup``
- ``RichTextCommandsIndentOptionsGroup``
- ``RichTextCommandsFontSizeOptionsGroup``
- ``RichTextCommandsStyleOptionsGroup``
- ``RichTextFormatCommandMenu``
- ``RichTextShareCommandMenu``

### Data

- ``RichTextDataError``
- ``RichTextDataFormat``
- ``RichTextDataFormatMenu``
- ``RichTextDataReader``

### Export

- ``RichTextExportError``
- ``RichTextExportMenu``
- ``RichTextExportService``
- ``RichTextExportUrlResolver``
- ``StandardRichTextExportService``
- ``StandardRichTextExportUrlResolver``

### Focus

- ``RichTextContextFocusedValueKey``

### Fonts

- ``FontRepresentable``
- ``FontDescriptorRepresentable``
- ``FontTraitsRepresentable``
- ``RichTextFontReader``
- ``RichTextFontWriter``
- ``StandardFontSizeProvider``
- ``RichTextFontPicker``
- ``RichTextFontPickerFont``
- ``RichTextFontForEachPicker``
- ``RichTextFontListPicker``
- ``RichTextFontSizePicker``
- ``RichTextFontSizePickerStack``

### Format

- ``RichTextFormatSheet``
- ``RichTextFormatSidebar``

### Images

- ``ImageRepresentable``
- ``RichTextImageAttachment``
- ``RichTextImageAttachmentManager``
- ``RichTextImageAttachmentSize``
- ``RichTextImageConfiguration``
- ``RichTextImageInsertConfiguration``

### Images

- ``RichTextKeyboardToolbar``
- ``RichTextKeyboardToolbarMenu``
- ``RichTextKeyboardToolbarStyle``

### Indent

- ``RichTextIndent``
- ``RichTextIndentReader``
- ``RichTextIndentWriter``
- ``RichTextIndentPicker``

### Localization

- ``RTKL10n``

### Pasteboard

- ``PasteboardImageReader``

### Pdf

- ``PdfDataError``
- ``PdfPageConfiguration``
- ``PdfPageMargins``
- ``RichTextPdfDataReader``

### Sharing

- ``RichTextNSSharingMenu``
- ``RichTextShareMenu``
- ``RichTextShareService``
- ``StandardRichTextShareService``

### Styles

- ``RichTextHighlightingStyle``
- ``RichTextStyle``
- ``RichTextStyleReader``
- ``RichTextStyleWriter``
- ``RichTextStyleButton``
- ``RichTextStyleToggle``
- ``RichTextStyleToggleGroup``
- ``RichTextStyleToggleStack``



[License]: https://github.com/danielsaidi/RichTextKit/blob/master/LICENSE
