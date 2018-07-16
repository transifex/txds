# 🌀 Transifex Design System [TxDS]

## Introduction
As Transifex continues to grow it became important to create a design system that will reflect not only our style-guide and structure but also our design vision, philosophy and language. 

The TxDS (Transifex Design System) is an evolving set of guidelines, principles, best practices and libraries. It is a living documentation that can afford guidance in design thinking, reasoning, referencing and implementing design solutions across the product.

******

## 📘 Principles
The vision of TxDS is designated by 10 universal design axioms, that offer inspiration and direction to solve people needs and improve the user experience of the product. 

These principles can be used during all phases of design, from design thinking and ideation to sketching, prototyping, and testing.

#### ▣ Simple
Provide no more than is needed. Prefer to be simple and explicit than complex and implicit, even if it feels obvious.

#### △ Authentic
Design genuine experiences. Follow and learn from current conventions and trends but also differentiate and think ahead.

#### ◈ Inventive
Follow a fuzzy logic when needed and try to invent something new and awesome today. Be resourceful and playful.

#### ⚭ Durable
Design for the future. Prefer solutions with a much higher lifespan that will be functional and compatible in the near future.

#### ▦ Modular
Design components that can operate and scale independently as atoms, combine to create new molecules but also inter-communicate effectively inside an organism.

#### ▥ Consistent
Design reusable solutions to solve similar problems and don’t repeat yourself. Use a coherent user interface library.

#### ◳ Efficient
Make it easy for users to find and do what they came to do. Promote one scope per page.

#### ✱ Clear
Design clear and elegant interfaces. Use color, visualizations and graphic elements to denote value, actions or important context. Be functional, not fictional.

#### ◌ Inclusive
Aim to make the product or services accessible to as many users as possible in as many diverse environments as possible.

#### ⌘ Multicultural
Design for a global audience. Consider content and design that goes beyond language localization and incorporate linguistic, physical, business and cultural aspects.

******

## 🏛 Foundation

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

******

### Writing style

**Capitalization**

Titles, headings, labels, actions and menu items should use Sentence style capitalization (capitalizing only the first word of a sentence).

**Example**

"The quick brown fox jumps over the lazy dog"
A mixed-case style in which the first word of the sentence is capitalized, as well as proper nouns and other words as required by a more specific rule. This is generally equivalent to the baseline universal standard of formal English orthography.

**Further reading**
- [Material Design / Writing](https://material.io/guidelines/style/writing.html#writing-capitalization-punctuation)
- [Microsoft / Capitalization](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/capitalization-conventions)
- [Atlassian / Writing Style](https://atlassian.design/server/foundations/writing-style/)

***

### Tone & Voice
Our voice is the core of our personality, and is gender-neutral, not masculine or feminine. Our tone expresses the mood or feeling of the voice, which can change based on the situation.

Following are few examples when communicating and talking to people.

- We’re 'professional' but 'chill'.
- We communicate clearly without sounding too formal or stiff.
- We’re warm and welcoming to our members, partners, and friends.
- We’re human. We’re not robots or scripted.
- We speak with pride about our product, experience, members, team, and - company.
- We take responsibility for our mistakes and resolve issues as quickly as possible
- We respect and support our users every time in the most responsive way.
- We’re transparent. We always speak the truth and never say things to appease.
- We keep it simple and get to the point.
- We don’t over-promise or exaggerate.

******

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

******

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

******

## 📕 Guidelines
Below you can find guidelines and practices about Transifex core elements and components. 

#### 🔩 ELEMENTS 
https://www.transifex.com/styleguide/design-elements/

### Color
https://www.transifex.com/styleguide/design-elements/ui-colors/ https://www.transifex.com/styleguide/design-elements/colors/

### Typography
https://www.transifex.com/styleguide/utilities/typography/
https://www.transifex.com/styleguide/design-elements/typography/

### Iconography
https://www.transifex.com/styleguide/design-elements/icons/

### Layout
- Structure
- Grid https://www.transifex.com/styleguide/utilities/flexbox/
- Spacing https://www.transifex.com/styleguide/utilities/spacing/
- Elevation

### Motion 
_Add more..._

### Interaction
_Add more..._
 
### Communication
- Onboarding
- Messaging

******

#### ⚙️ COMPONENTS
https://www.transifex.com/styleguide/ui-components/

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
_Last updated on July 12, 2018_

  



