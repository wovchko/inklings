# Inklin.gs is a blog by Brendan Wovchko.
- Ideas to align Nashville's Suits, Developers, & Designers
- A Github Project Profile powered by Github Pages & Jekyll
- Copyright information can be found in the footer of the web site.

# Customization Settings for Bootstrap
- http://twitter.github.com/bootstrap/customize.html
- The web page above allows for the customization of Twitter Bootstrap.  The output is a single file, bootstrap.css.  This custom bootstrap.css includes the responsive styles that are included in a separate CSS file in the default distribution.
- The information below is a reflection of the configuration options which were available and the options I selected to generate the bootstrap_custom.css file in this repository.
- Heavy customization (e.g. custom fonts) were subsequently made to bootstrap_custom.css.

## 1. Choose components

### Scaffolding
- (Y) Normalize and reset
- (Y) Body type and links
- (Y) Grid system
- (Y) Layouts

### Base CSS
- (Y) Headings, body, etc
- (Y) Code and pre
- (N) Labels and badges
- (Y) Tables
- (N) Forms
- (N) Buttons
- (N) Icons

### Components
- (N) Button groups and dropdowns
- (N) Navs, tabs, and pills
- (N) Navbar
- (N) Breadcrumbs
- (N) Pagination
- (N) Pager
- (N) Thumbnails
- (N) Alerts
- (N) Progress bars
- (N) Hero unit
- (N) Media component

### Miscellaneous
- (N) Media object
- (N) Wells
- (N) Close icon
- (N) Utilities
- (N) Component animations

### Responsive
- (Y) Visible/hidden classes
- (Y) Narrow tablets and below (<767px)
- (Y) Tablets to desktops (767-979px)
- (Y) Large desktops (>1200px)
- (N) Responsive navbar

### JS Components
- (N) Tooltips
- (N) Popovers
- (N) Modals
- (N) Dropdowns
- (N) Collapse
- (N) Carousel

## 2. Select jQuery plugins
- (N) Transitions (required for Affix any animation)
- (N) Modals
- (N) Dropdowns
- (N) Scrollspy
- (N) Togglable tabs
- (N) Tooltips
- (N) Popovers (requires Tooltips)
- (N) Alert messages
- (N) Buttons
- (N) Collapse
- (N) Carousel
- (N) Typeahead

## 3. Customize variables
> No default values were changed

### Scaffolding
- @bodyBackground, @white
- @textColor, @grayDark

### Links
- @linkColor, #08c
- @linkColorHover, darken(@linkColor, 15%)

### Colors
- @blue, #049cdb
- green, #46a546
- @red, #9d261d
- @yellow, #ffc40d
- @orange, #f89406
- @pink, #c3325f
- @purple, #7a43b6

### Sprites
- @iconSpritePath, '../img/glyphicons-halflings.png'
- @iconWhiteSpritePath, '../img/glyphicons-halflings-white.png'

### Grid system
- @gridColumns, 12
- @gridColumnWidth, 60px
- @gridGutterWidth, 20px
- @gridColumnWidth1200, 70px
- @gridGutterWidth1200, 30px
- @gridColumnWidth768, 42px
- @gridGutterWidth768, 20px

### Typography
- @sansFontFamily, 'Helvetica Neue', Helvetica, Arial, sans-serif
- @serifFontFamily, Georgia, 'Times New Roman', Times, serif
- @monoFontFamily, Menlo, Monaco, 'Courier New', monospace
- @baseFontSize, 14px
- @baseFontFamily, @sansFontFamily
- @baseLineHeight, 20px
- @altFontFamily, @serifFontFamily
- @headingsFontFamily, inherit
- @headingsFontWeight, bold
- @headingsColor, inherit
- @fontSizeLarge, @baseFontSize * 1.25
- @fontSizeSmall, @baseFontSize * 0.85
- @fontSizeMini, @baseFontSize * 0.75
- @paddingLarge, 11px 19px
- @paddingSmall, 2px 10px
- @paddingMini, 1px 6px
- @baseBorderRadius, 4px
- @borderRadiusLarge, 6px
- @borderRadiusSmall, 3px
- @heroUnitBackground, @grayLighter
- @heroUnitHeadingColor, inherit
- @heroUnitLeadColor, inherit

### Tables
- @tableBackground, transparent
- @tableBackgroundAccent, #f9f9f9
- @tableBackgroundHover, #f5f5f5
- @tableBorder, #ddd

### Forms
- @placeholderText, @grayLight
- @inputBackground, @white
- @inputBorder, @ccc
- @inputBorderRadius, 3px
- @inputDisabledBackground, @grayLighter
- @formActionsBackground, #f5f5f5
- @btnPrimaryBackground, @linkColor
- @btnPrimaryBackgroundHighlight, darken(@white, 10%)

### Form states & alerts
- @warningText, #c09853
- @warningBackground, #fcf8e3
- @errorText, #b94a48
- @errorBackground, #f2dede
- @successText, #468847
- @successBackground, #dff0d8
- @infoText, #3a87ad
- @infoBackground, #d9edf7

### Navbar
- @navbarHeight, 40px
- @navbarBackground, @grayDarker
- @navbarBackgroundHighlight, @grayDark
- @navbarText, @grayLight
- @navbarBrandColor, @navbarLinkColor
- @navbarLinkColor, @grayLight
- @navbarLinkColorHover, @white
- @navbarLinkColorActive, @navbarLinkColorHover
- @navbarLinkBackgroundHover, transparent
- @navbarLinkBackgroundActive, @navbarBackground
- @navbarSearchBackground, lighten(@navbarBackground, 25%)
- @navbarSearchBackgroundFocus, @white
- @navbarSearchBorder, darken(@navbarSearchBackground, 30%)
- @navbarSearchPlaceholderColor, #ccc
- @navbarCollapseWidth, 979px
- @navbarCollapseDesktopWidth, @navbarCollapseWidth

### Dropdowns
- @dropdownBackground, @white
- @dropdownBorder,  rgba(0,0,0,.2)
- @dropdownLinkColor, @grayDark
- @dropdownLinkColorHover, @white
- @dropdownLinkBackgroundHover, @linkColor