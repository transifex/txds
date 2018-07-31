
# 🌀 Transifex Design System [TxDS]

As [Transifex](https://www.transifex.com) continues to grow it becomes extremely important to create a **design system** that will reflect not only our frontend framework and styleguide but also our design vision, philosophy and language. 

The **TxDS (Transifex Design System)** is an evolving set of guidelines, principles, best practices and libraries that will help  designers, engineers and stakeholders learn more about the logic, rationale and practice of elements and components that we have in Transifex organization.

It is a living documentation that can afford guidance in design thinking, reasoning, referencing and implementing design solutions across the product. And as a living document expect to be updated in intervals and never stop growing. 
This is a promise!


# 📘 Principles

The vision of **TxDS** is designated by 10 universal design axioms, that offer inspiration and direction to solve people needs and provide a great user experience. 

These high level principles can be used and cited during all phases of design, from design thinking and ideation to sketching, prototyping, and testing.

### We believe that good design is:

#### 🕹 Simple
Provide no more than is needed. Prefer to be simple and explicit than complex and implicit, even if it feels obvious.

#### 🏺 Authentic
Design genuine experiences. Follow and learn from current conventions and trends but also differentiate and think ahead.

#### 💡 Inventive
Follow a fuzzy logic when needed and try to invent something new and awesome today. Be resourceful and playful.

#### 🔋 Durable
Design for the future. Prefer solutions with a much higher lifespan that will be functional and compatible in the near future.

#### 🔗 Modular
Design components that can operate and scale independently as atoms, combine to create new molecules but also inter-communicate effectively inside an organism.

#### ⚖️ Consistent
Design reusable solutions to solve similar problems and don’t repeat yourself. Use a coherent user interface library.

#### 🔑 Efficient
Make it easy for users to find and do what they came to do. Promote one scope per page.

#### 💎 Clear
Design clear and elegant interfaces. Use color, visualizations and graphic elements to denote value, actions or important context. Be functional, not fictional.

#### 💙 Inclusive
Aim to make the product or services accessible to as many users as possible in as many diverse environments as possible.

#### 🌍 Multicultural
Design for a global audience. Consider content and design that goes beyond language localization and incorporate linguistic, physical, business and cultural aspects.


# 🏛 Foundation

### Visual 
TxDS favors concepts such as simplicity, consistency, hierarchy and concise structure with the goal to represent a unique and innovative interface and also immerse the user in the experience. Following are some key visual characteristics.

**Authentic**

We think and design in a creative way. Our design process and thinking is unique and our visual personality look and feel modern and fresh.

**Adaptive**

Our design is fun, relaxed but also professional and formal depending on the context, condition, environment or use case.

**Resourceful** 

We are capable in finding new, innovative and creative solutions that cover our users needs and solve their problems fast and efficiently.

**Balanced**

We design harmonious and aesthetically pleasing experiences that people love to have repeatedly, are unobtrusive and reduce distraction.

**Visionary**

We strive for faster, simpler, better solutions as we look ahead in the future and we don’t stop searching for new answers and paradigms.


### Writing style

**Capitalization**

Titles, headings, labels, actions and menu items should use Sentence style capitalization (capitalizing only the first word of a sentence).

**Example**

_The quick brown fox jumps over the lazy dog_
A mixed-case style in which the first word of the sentence is capitalized, as well as proper nouns and other words as required by a more specific rule. This is generally equivalent to the baseline universal standard of formal English orthography.

**Further reading**
- [Material Design / Writing](https://material.io/guidelines/style/writing.html#writing-capitalization-punctuation)
- [Microsoft / Capitalization](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/capitalization-conventions)
- [Atlassian / Writing Style](https://atlassian.design/server/foundations/writing-style/)


### Tone & Voice
Our voice is the core of our personality, and is gender-neutral, not masculine or feminine. Our tone expresses the mood or feeling of the voice, which can change based on the situation.

Following are few examples when communicating and talking to people.

- We’re **_professional_** but **_chill_**.
- We communicate **clearly** without sounding too formal or stiff.
- We’re warm and **welcoming** to our members, partners, and friends.
- We’re **human**. We’re not robots or scripted.
- We speak with **pride** about our product, experience, members, team, and company.
- We take **responsibility** for our mistakes and resolve issues as quickly as possible
- We **respect** and **support** our users every time in the most responsive way.
- We’re **transparent**. We always speak the truth and never say things to appease.
- We keep it **simple** and get to the point.
- We don’t over-promise or exaggerate.


### Accessibility

**WCAG**

As a digital team we strive to make all efforts necessary to meet Level AA (including Level A) success criteria of the Web Content Accessibility Guidelines (WCAG). 

**Color**

Some people find it hard or impossible to see specific colors, either as a standalone color, or when combined with a particular secondary color. Level AA criteria (of WCAG) requires that the foreground and background colors have a 4.5:1 contrast ratio. 

**Links**

Color shouldn’t be used as the sole method of conveying meaning or distinguishing visual elements (this is a Level A criteria). Underlining links is common place online. If this isn’t appropriate to the design then the link must be sufficiently different in contrast from the surrounding text (e.g. the link could be accompanied by an arrow or icon).

**Forms**

Form fields (e.g. text input, textarea, select, radio, checkbox, fieldset) should include a label. A label clearly identifies what the user needs to do with the accompanying form field. A label is a good visual indication, but it’s also important for accessibility, for people who can’t or struggle to see the screen. 

Screen readers will read the label (and input) and instruct the user what they need to do. Without a label, the user may only hear: “Edit text.” You can see how useless this is to them. With a label, they will hear: “Username, edit text.”

**Focus states**

A focus state is the styling of an element being targeted by the keyboard, or activated by the mouse. Some people navigate websites with just a keyboard. A focus state (a visual indication) is very helpful to know which element you are on. The most commonly used visual indicator is a subtle border ‘glow’.

**Further reading**
[Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)


### Localization
Some languages are more verbose than others, meaning your design must account for text expansion and contraction in translated languages. 

The general rule is to plan for an average of 35% text expansion. The example below illustrates how the character length of a text string will vary from language to language.

|Language       |String        |
|:--------------|:-------------|
|English|Transifex makes localization easy.|
|Dutch|Transifex maakt lokalisatie gemakkelijk.|
|Chinese Simplified|Transifex 使得本地化容易。|
|Hindi|Transifex स्थानीयकरण आसान बनाता है।|

Development frameworks provide features that can help you to program dynamic UI expansion and contraction. Although the intricacies may vary based on the framework, the design considerations detailed below are mostly common.

**Further reading**
[Transifex / Designing a Localization-Friendly User Interface](https://www.transifex.com/blog/2015/localization-friendly-ui-design-part-1/)
[IBM / Guideline A3: UI expansion](https://www-01.ibm.com/software/globalization/guidelines/a3.html)


# 📕 Guidelines

Below you can find guidelines and best practices regarding Transifex core elements and components. 

##  🔩 Elements

### Color Palette

>🖥 **Code Resources** 
>https://www.transifex.com/styleguide/design-elements/colors/


Color brings a design to life. Color should be used in meaningful and intentional ways in order to create patterns and visual cues. 

We favor semantic coloring and tend to follow generic conventions and usually don't introduce new colors if it's not necessary but instead play with opacity and shades.

Our color palette has 27 unique hues which produce numerous combinations in the UI. 

![Color Palette](/images/colors.png?raw=true "Color Palette")

### UI Colors

>🖥 **Code Resources** 
>https://www.transifex.com/styleguide/design-elements/ui-colors/

This page displays the usage and semantic of Colors in Transifex. 

UI colors are split in categories that reflect their usage. Category descriptions are giving more details on color usage when needed.

#### Brand Colors
This is the Transifex brand color, used to identify relation with Transifex.

![Brand colors](/images/brand-colors.png?raw=true "Brand colors")

#### Background Colors

Use colors displayed below as backgrounds. Follows a brief usage meaning for each color:

-   `@background-color`, is the default color used as background in Transifex applications.
-   `@background-data-color`, is used on areas of the interface that includes the main information displayed on the page.
-   `@background-muted-color`, is used on areas that contain secondary information and complementary actions of the page.
-   `@background-active-color`, is used on elements that have some action on but don't want to draw to much attention. Examples are table sorting headers and graph filters.

![Background colors](/images/background-colors.png?raw=true "Brackground colors")

#### Secondary Navigation Colors

This color set applies to navigation sidebar. This navigation element is only used in vertical space. Colors included here are for various elements displayed inside that navigation area:

-   `@secondaryNavigation-background-color`, is the base color of the secondary navigation area.
-   `@secondaryNavigation-background-highlight-color`, is used to highlight the background of activated elements.
-   `@secondaryNavigation-symbol-color`, is used to color symbols.
-   `@secondaryNavigation-symbol-highlight-color`, is used on symbols of activated elements.
-   `@secondaryNavigation-text-active`, active text on area.
-   `@secondaryNavigation-text-highlight-active-color`, highlighted active text on area.

![Secondary navigation colors](/images/secondary-nav-colors.png?raw=true "Secondary navigation colors")

#### Graph Colors

-   `@background-graph-back`, background color of a graph.
-   `@background-graph-base`, this color should be used on the primary graph data.
-   `@background-graph-extend`, this color should be used on the secondary graph data.

![Graph colors](/images/graph-colors.png?raw=true "Graph colors")

####  Interactive Colors

This set contains colors for interactive elements of the interface. Buttons, links and other active elements use these colors to display various interaction states.

*Note:  the  _onMuted_  variations refer to interactive elements used on top of  `@background-muted-color`, the secondary information areas of the interface.*

![Interactive colors](/images/interactive-colors.png?raw=true "Interactive colors")

#### Feedback Colors

These color set is used to display elements status and state on the interface.

![Feedback colors](/images/feedback-colors.png?raw=true "Feedback colors")

**Element states**

Notification color is used when an element needs to notify the user of an interesting info that is not pressing or urgent.

Issue color is used to showcase an element containing info that require some attention by the user, in a sense that the displayed info contains some urgency.

**System status**

Colors below are used to display system statuses.

![System status](/images/system.png?raw=true "System status")

> **Suggestion** 
> Status error color, is used to display something negative
> or fatal, don't use this color in cases that only a part of the action
> fails and other succeeds. Use status-warning-color instead.

#### Text Colors

 ![Text colors](/images/text-colors.png?raw=true "Text colors")
 
#### Social Colors

![Social colors](/images/social-colors.png?raw=true "Social colors")

#### Further reading
[Color Contrast Checker](https://marijohannessen.github.io/color-contrast-checker/)


### Typography

>🖥 **Code Resources** 
>https://www.transifex.com/styleguide/utilities/typography/
>https://www.transifex.com/styleguide/design-elements/typography/

#### Headings
These are the standard heading styles:

# Header style for H1 ( 30px )

## Header style for H2 ( 28px )

### Header style for H3 ( 23px )

#### Header style for H4 ( 17px )

##### Header style for H5 ( 16px )

###### Header style for H6 ( 15px )


> **👍Suggestion** 
> **h1:** Hero titles. Very important text.
> **h2:** Usually page titles.
> **h3:** Separating page sections with eachother.

#### Alignment

This is a list of classes that we use to define the text alignment of an element:

`.u-textAlign-center`
`.u-textAlign-left`
`.u-textAlign-right`

![Alignment](/images/alignment.png?raw=true "Alignment")

> 💡**NOTE**   
> In case you are wondering, these examples also use utility classes, like the  `.u-padding-x2`,  `.u-backgroundColor-notification` and  `.u-color-white`class.

#### Weight
|Class|Weight|
|:--------------|-------------:|
 `.u-fontWeight-thin`|100
`.u-fontWeight-regular`|300
 `.u-fontWeight-semibold`|600

![Font weight](/images/font-size.png?raw=true "Font weight")

#### Styles

These utility classes are used to simulate most of the different style properties a text might have:
|Class|Example|
|:--------------|:-------------|
`.u-textDecoration-linethrough`|~~Hello~~
`.u-textDecoration-underline`|__Hello__
`.u-fontStyle-italic`|_Hello_
`.u-textTransform-uppercase`|HELLO
`.u-textTransform-none`|Hello

#### Sizes

Here are some font size variations relative to the root (in rem) font size (currently 14px):
|Class|Font size (rem)|Font size (px)|
|:--------------|-------------:|-------------:|
|`.u-fontSize-tiny`|0.714rem|10px
|`.u-fontSize-small`|0.857rem|12px
|`.u-fontSize-normal`|1rem|14px
|`.u-fontSize-default-plus`|1.2rem|16px
|`.u-fontSize-large`|1.286rem|18px
|`.u-fontSize-big`|1.786rem|25px
|`.u-fontSize-bigger`|2.143rem|30px
|`.u-fontSize-enormous`|2.5rem|40px
|`.u-fontSize-enormous-plus`|3.49rem|48px
|`.u-fontSize-huge`|3.5rem|49px
|`.u-fontSize-gargantuan`|4.286rem|60px

![Font size](/images/font-size.png?raw=true "Font size")

> **💡NOTE**  
> There is no use case of the last four classes in the Transifex app. If you think you need to use a something larger than the  `.u-fontSize-bigger`, you should consult someone from the design team.


#### Line Height

-   `.u-lineHeight-{2-9}x`, a line height multiple of the  `@baseline-grid`  (6px).
-   `.u-lineHeight-form`
-   `.u-lineHeight-button`
-   `.u-lineHeight-1em`

#### Vertical align

-   `.u-verticalAlign-middle`
-   `.u-verticalAlign-textTop`
-   `.u-verticalAlign-bottom`

#### Wrapping

 `.u-wordBreak-breakAll`, breaks text to the current element's width.

Let's use a large variable name to demonstrate this utility: @secondaryNavigation-background-highlight-color.

> **💡NOTE**  
> Other classes we used for this example are  `.u-width-20`, `.u-padding-2x`,  `.u-marginHorizontal-auto`, `.u-backgroundColor-notification`  and  `.u-color-white`.



### Iconography

>🖥 **Code Resources** 
>https://www.transifex.com/styleguide/design-elements/icons/

In order to have lightweight and scalable pixel perfect graphics in our platform, independent of screen we are using SVG icons. The only thing you need to do to use an icon, is to add the desired icon's id to the href attribute of the svg code you see below.

This is the default state of an icon which results to the "urgent priority" icon ().

```
<svg class="o-icon">
    <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-priority-urgent"></use>
</svg>
```

Like most of the elements in Transifex, to apply any other property to the icon you need to use the available [utilities](https://www.transifex.com/styleguide/design-elements/icons/#). For example, the classes `.u-box-6`, `u-marginBottom-2x`, and `.u-fill-brand` give the different look you see in the icon list provided in this page:

```
<svg class="o-icon u-box-6x u-marginBottom-2x u-fill-brand">
<use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-priority-urgent"></use>
</svg>
```

Below you can see all available svg icons along with their ids:

![Icons](/images/icons.png?raw=true "Icons")


### Layout

>🖥 **Code Resources** 
>https://www.transifex.com/styleguide/utilities/flexbox/
>https://www.transifex.com/styleguide/utilities/spacing/

#### Grid & Spacing
Inside the Transifex app we don't use the traditional 'grid way' to create layouts, but Flexbox utility classes.

Additionally block elements and spacing is defined by the `@baseline-grid` variable.
**The baseline grid is set to 6px.**

For all our utility classes which are associated with the  [box model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)  we use the 
`u-{ property }{ '' | Top | Right | Bottom | Left | Horizontal | Vertical }-{ multiplier }x`  naming convention. 

For example, if we want to have a bottom margin of 24px we will use the  `.u-marginBottom-4x`  class, if we want to define padding to the whole box model we are going to use  `.u-padding-4x`.

When you see the description  **position**  in a classname we are refering to the  
`{ '' | Top | Right | Bottom | Left | Horizontal | Vertical }`  part of a class.

#### Elevation
Z index is used to define elevation of block and components. Modals use the top elevation.
|Z-index|Elevation|Box-shadow
|:--|--:|--:|
|Base|0|`none`
|`@zindex1`|1|`..`
|`@zindex2`|2|`..`
|`@zindex3`|3|`..`
|`@zindex4`|4|`..`
|`@zindexTop`|10|`0 0 4px rgba(0,0,0,0.16)`
|`@zindex11`|11|`0 2px 20px rgba(0,0,0,0.2);`
|Modal|1000|`0 0 20px rgba(0,0,0,0.4)`

🎬Todo

![Elevation](/images/elevation.png?raw=true "Elevation")


#### Patterns
🎬Todo


### Motion 
🎬Todo


### Interaction
🎬Todo


### Communication

#### Onboarding
🎬Todo

#### Empty states
🎬Todo

#### Imagery
🎬Todo

#### Messaging
🎬Todo



##  ⚙️ Components

>🖥 **Code Resources** 
>https://www.transifex.com/styleguide/ui-components/

### Dropdown menus

**Usage**

Dropdown menus display options for list items, and they immediately commit choices upon selection. Dropdown options can be single and multi-level with the difference that for the later a visual cue is needed such as an right arrow. For selected options a checked mark should be added.

**Example**

_Add more..._

**Content**

Dropdown menu content typically consists of text and/or UI control elements. It is focused on a specific task, such as choosing a setting or option.

**Mechanics**

Dropdowns should not include more than two actions. A third action, such as “Learn more,” navigates away from the dialog, potentially leaving the task unfinished.

Choosing an option immediately commits the option and closes the menu. Clicking outside of the dialog, or pressing ESC, cancels the action and closes the dialog

**Good & Bads**

Avoid using a “Learn more” action to access help documentation; in-line expansion within the dialog should be used instead. If more extensive information is needed, provide it prior to entering the dropdown.
 
 
### Help text

**Usage**

To assist user and provide context and clarity about a field’s input you can use help text.

**Example**

_Add more..._

**Content**

As with all form content, help text should be succinct and easy to read. For brief explanations (shorter than a sentence), place the text underneath the field. If the explanation is lengthy, don't use a help text! Help text should be short!

Help text should not be correlated with placeholder, label or tip patterns/components and should be used differently and per use case.

You can also use placeholder text to provide an example of the type of input required. For example, in a Name field, show a name in the correct format.

**Good & Bads**
- Help text should be placed below the text field
- Left aligned
- On a single line if possible, or with text wrapping (if multiple lines)
- Don't write more than 2-3 lines of text.
- Keep it short!

******

## 🗃 Changelog

### Version 0.3
**📆 July 2018** / More core elements

**💎 Changes**

Updated document with basic elements from Tx Styleguide, formatting cleanup and added todo placeholders for next iteration.


### Version 0.2
**📆 June 2018** / TxDS Design Language … finalized

**💎 Changes**

Merge design language chapters into one universal document
Cleanup, update txds repo

### Version 0.1
**📆 January 2018** / First drafts of foundation blocks. 

**💎 Changes**

- Present and collaborate on initial version
- Created GH repo
- Added first issues/PR’s

------
_Last updated on July 31, 2018_
