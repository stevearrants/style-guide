# Write for All Users

Always aim to write content that all users can access and understand, regardless of background or level of ability.  

Make content accessible for all audiences, with or without disabilities.

Use these guidelines when creating content.

##  Writing
Use plain language, simple sentence construction, and short paragraphs. Complex sentences and long paragraphs can be
a real struggle for some users. Plain language makes a smoother, better experience. Consider that some readers use
screen readers or other assistive devices.

Avoid using complex words and avoid technical jargon or complicated technological terms. If you must use
technological terms, be consistent. [Use Plain Language](plainlanguage.md) offers guidance.

##  Avoid language that relise on spatial direction
Spatial directional language doesn't help users with screen readers. Instead of using *above*, *below*, *left*, or
*right* to direct users, use *earlier*, *later*, or *following*. Likewise, avoid relying only on visual language,
such as text referring to color, shape, and patterns. Refer to UI elements using their labels whenever possible, and
don't rely on directional or visual language as the only means to guide users to a location.

Lead into new page elements such as tables, lists, images, videos, searches, commands, and code blocks. Introduce a
new page element with a lead-in sentence that explains what information the element contains or what the user needs
to do. These lead-in sentences can prepare users for what to expect.

##  Spell it out
Avoid unnecessary abbreviations, acronyms, and initialisms Spell out words like *and*, *plus*, *minus*, and
*approximately* instead of using symbols. See [Abbreviations](abbrev.md) and [Acronyms and Initialisms](acronym.md).
Consult the [Usage Dictionary](usagedict.md).

##  Be precise and exact
Make sure that the noun that a pronoun refers to us clear. It may be unclear, too broad or placed a distance from
the pronoun. This can make the sentence vague and confusing for users with reading disabilities.

The following table contains examples of vague sentences and more precise alternatives:

###  Vague
- This leads to an invalid activity.
- This is similar to JavaScript, with with important differences.

### Precise
- Undefined variables lead to an invalid activity.
- Jitterbit Script is similar to JavaScript, with important differences.


## Titles and Document and Section Headings
Headings help break up long text passages and help all readers navigate through a page. Descriptive titles and
headings are not only useful for search engine optimization, but also help all users find information.

Many sighted and screen reader users scan through headings first to figure out where they need to go. Sections
organized by headings are easier to parse than long sections with fewer headings. Make your headings descripted and
well-organized. It makes it much easier for our users to understand the documentation.

Organize your topic using headers down to the H3 level. If you need to use a heading level beyond an H3, your topic
might be too complex. Never skip heading hierarchy levels. For more guidance on headings, see Manual names, topic
titles, and section headings.

## Images and Figures
Images can help readers understand complex topics, locate an icon, or zero in on a portion of the UI. However, don't
include images without alt-text or surrounding test with limited vision. Ask yourself, *Does this image help
understand the text? Have I included alt-text for screen readers?*.

Alt-text is crucial for helping visually impaired users understand and use our sofware and services. Some users
aren't native English speakers and use translation tools to translate alt-text for images with accompanying English
labels.

Here are some tips for using image:

- Don't include new information in an image. Introduce new information in the surrounding text of the image.
- Don't rely on color to convey the message of the image. Use a combination of colors, shapes, patterns, explanatory text,
and labels instead.
- Ensure your image meets the contrast ratio for users with visual disabilities. See
  https://webaim.org/resources/contrastchecker/ on the WebAIM website.
- Always include alt text. For guidance on writing alt text, see Include alt text.
- Lead into an image with a description of the content and the purpose of the image that makes the image meaningful.
  For more information, see [Best Practices: Images](imagebest.md) .

##  Videos
If you include videos, include captions and transcripts. Synchronize captions with the video and include all
dialogue and important sound effects. If your video covers important visual details, describe them in the audio.

##  Tables
Tables are effective at organizing and presenting information, so keep tables as simple as possible.Tables with
bulleted or numbered lists or with merged cells present problems for screen readers. Use a non-breaking space
instead of a blank in an empty cell. Screen readers won't skip over the cell, causing confusion. See
[Best Practices: Tables](tablesbp.md).

##  Lists
Use simple lists. Use parallel construction for list items. Use one item or idea for a single list item. COnsistent
patterns and simples lists won't cause problems for screen readers or confusion for readers with disabilities. See
[Best Practices: Lists](listbp.md) for more information.

## Linking
Links should be clear, descriptive, and meaningful. Don't add links just because they're available. Make each link
count! Lead into each link with a description so that users can decide if that link is useful to them.
