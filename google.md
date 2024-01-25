## [Google Developer Documentation Style Guide](https://developers.google.com/style)

> Start with [Highlights](https://developers.google.com/style/highlights), 
> [Voice and tone](https://developers.google.com/style/tone), and 
> [Text-formatting summary](https://developers.google.com/style/text-formatting).
> Otherwise, use the guide as a reference document for specific questions. For example, 
> you can look up terms in the [word list](https://developers.google.com/style/word-list).

Source: Google > [About this guide](https://developers.google.com/style)

### [Highlights](https://developers.google.com/style/highlights)

The list below is copied verbatim from the Google documentation.

Tone and content

+   [Be conversational and friendly](https://developers.google.com/style/tone) without being frivolous.
+   [Don't pre-announce anything](https://developers.google.com/style/future) in documentation.
+   [Use descriptive link text](https://developers.google.com/style/link-text).
+   [Write accessibly](https://developers.google.com/style/accessibility).
+   [Write for a global audience](https://developers.google.com/style/translation).

Language and grammar

+   [Use second person](https://developers.google.com/style/person): "you" rather than "we."
+   [Use active voice](https://developers.google.com/style/voice): make clear who's performing 
    the action.
+   [Use standard American spelling](https://developers.google.com/style/spelling) and punctuation.
+   [Put conditions before instructions](https://developers.google.com/style/sentence-structure), 
    not after.
+   For usage and spelling of specific words, see the 
    [word list](https://developers.google.com/style/wordlist).

Formatting, punctuation, and organization

+   [Use sentence case](https://developers.google.com/style/capitalization) for document titles 
    and section headings.
+   [Use numbered lists](https://developers.google.com/style/lists#types-of-lists) for sequences.
+   [Use bulleted lists](https://developers.google.com/style/lists#types-of-lists) for most other 
    lists.
+   [Use description lists](https://developers.google.com/style/lists#types-of-lists) for pairs of 
    related pieces of data.
+   [Use serial commas](https://developers.google.com/style/commas-serial).
+   [Put code-related text in code font](https://developers.google.com/style/code-in-text).
+   [Put UI elements in bold](https://developers.google.com/style/ui-elements).
+   [Use unambiguous date formatting](https://developers.google.com/style/dates-times).

Images

+   [Use SVG files](https://developers.google.com/style/images) or crushed PNG images.
+   [Provide alt text](https://developers.google.com/style/images#text-associated-with-images).
+   [Provide high-resolution
    images](https://developers.google.com/style/images#high-resolution-images) when practical.

### [Voice and tone](https://developers.google.com/style/tone)

In your documents, aim for a voice and tone that's conversational, friendly, and respectful without
being overly colloquial or frivolous; a voice that's casual and natural and approachable, not 
pedantic or pushy. Try to sound like a knowledgeable friend who understands what the developer 
wants to do.

Don't try to write exactly the way you speak; you probably speak more colloquially and verbosely 
than you should write, at least for developer documentation. But aim for a conversational tone 
rather than a formal one.

Don't try to be super-entertaining, but also don't aim for super-dry. Be human, let your 
personality show, and be memorable. But remember that the primary purpose of the document is to 
provide information to someone who's looking for it and may be in a hurry.

Consider that readers come from many different cultures and may have varying levels of ability 
reading English. As much as possible, avoid culturally specific references. Simple and consistent 
writing can also make it easier to translate documents into other languages. For more information, 
see [Writing for a global audience](https://developers.google.com/style/translation).

Some things to avoid where possible

+   Buzzwords or [technical jargon](https://developers.google.com/style/jargon).
+   Being too cutesy.
+   [Ableist 
    language](https://developers.google.com/style/inclusive-documentation#ableist-language)
    or figures of speech.
+   Placeholder phrases like please note and at this time.
+   Choppy or long-winded sentences.
+   Starting all sentences with the same phrase (such as You can or To do).
+   Current pop-culture references.
+   Exclamation marks, except in rare really exciting moments.
+   Wackiness, zaniness, and goofiness.
+   Mixing metaphors or taking a metaphor too far.
+   Phrasing that denigrates or insults any group of people.
+   Phrasing in terms of let's do something.
+   Using phrases like simply, It's that simple, It's easy, or quickly in a procedure.
+   Internet slang, or other 
    [internet abbreviations](https://developers.google.com/style/abbreviations#dont-use) 
    such as [tl;dr](https://developers.google.com/style/word-list#tldr) 
    or [ymmv](https://developers.google.com/style/word-list#ymmv).

Some techniques and approaches to consider

+   If you're having trouble expressing something, step back and ask yourself, 
    "What am I trying to say?" Often, the answer you give yourself reveals what you should be 
    saying in the document.
+   If you're uncertain about your phrasing or tone, ask a colleague to take a look.
+   Try reading parts of your document out loud, or at least mouthing the words. 
    Does it sound natural? Not every sentence has to sound natural when spoken; these are written 
    documents. But if you come across a sentence that's awkward or confusing when spoken, consider 
    whether you can make it more conversational.
+   Use transitions between sentences. Phrases like Though or This way can make paragraphs less 
    stilted. (Then again, sometimes transitions like However or Nonetheless can make paragraphs 
    more stilted.)
+   Even if you're having trouble hitting the right tone, make sure you're communicating useful 
    information in a clear and direct way; that's the most important part.

Politeness and use of please

It's great to be polite, but using _please_ in a set of instructions is overdoing the politeness.

+   ✅ Recommended: To view the document, click View.
+   ❌ Not recommended: To view the document, please click View.
+   ✅ Recommended: For more information, see [link to other document].
+   ❌ Not recommended: For more information, please see [link to other document].

### [Text-formatting summary](https://developers.google.com/style/text-formatting)

#### Bold

+   Use bold formatting, `<b>` or `**`, for 
    [UI elements](https://developers.google.com/style/ui-elements#formatting) and at the beginning 
    of [notices](https://developers.google.com/style/notices).
+   Although a double underscore, `__`, can also indicate bold styling in Markdown, it can be 
    difficult to distinguish in a text editor. It's best to use the double asterisk for bold in 
    Markdown.

#### Italic

+   Use italics formatting, `<i>` or `_`, when drawing attention to a specific word or phrase, 
    such as when [defining terms](https://developers.google.com/style/formatting-key-terms) or 
    [using words as words](https://developers.google.com/style/formatting-words-as-words).
+   Although an asterisk, `*`, can also indicate italics in Markdown, we recommend underscores to 
    make it easier for humans to distinguish italics from bold in the Markdown file.
+   Italicize titles of books, movies, web series, and other full-length works, unless they're 
    part of a link. For more information, see 
    [cross-references](https://developers.google.com/style/cross-references).
+   Italicize parameter names. For example, when you refer to the parameters of a method like 
    `doSomething(Uri data, int count)`, italicize _data_ and _count_.
+   Italicize mathematical variables and version variables. For example, _x_ + _y_ = 3, version 
    1.4._x_.
+   To indicate [semantic emphasis](https://developers.google.com/style/semantic-tagging) in HTML, 
    use the `<em>` element, which renders as italics in most contexts. To indicate emphasis in 
    Markdown, use underscores (`_`), which render as italics; you can't do semantic tagging in 
    Markdown.

#### Underline

+   Do not underline.

#### Code font

+   Use `<code>` in HTML or `` ` `` in Markdown to apply a monospace font and other styling to 
    [code in text](https://developers.google.com/style/code-in-text), inline code, and user input.
+   Use code blocks, `<pre>` or `` ``` ``, for 
    [code samples](https://developers.google.com/style/code-samples) or other blocks of code.
+   Do not override or modify font styles inline.
+   Use [code 
    font](https://developers.google.com/style/code-in-text#some-specific-items-to-put-in-code-font)
    to mark up code, such as filenames, class names, method names, HTTP status codes, console 
    output, and placeholders.

**Items to put in code font**

+   Attribute names and values
+   Class names
+   Command output (for example, `nameserver 169.254.169.254`)
+   [Command-line utility names](https://developers.google.com/style/code-in-text#tool-names), 
    such as `gcloud`, `gsutil`, `kubectl`, and `bq`
+   Data types
+   Defined (constant) values for an element or attribute
    [DNS record types](https://wikipedia.org/wiki/List_of_DNS_record_types)
+   Enum (enumerator) names
+   Environment variable names
+   Element names (XML and HTML).
    
    Place angle brackets (`<>`) around the element name; you might have to escape the angle 
    brackets to make them appear in the document.

+   Filenames, [filename extensions](https://developers.google.com/style/filenames#file-type-names) 
    (if used), and paths
+   Folders and directories
+   HTTP verbs
+   HTTP status codes
+   HTTP content-type values
+   IAM role names (for example, `roles/storage.admin`)
+   Language keywords
+   [Method and function names](https://developers.google.com/style/code-in-text#methods)
+   Namespace aliases
+   [Placeholder variables](https://developers.google.com/style/placeholders)
+   Query parameter names and values
+   Strings (such as URLs or domain names) that are used in commands and code:
    
    ✅ Recommended: In IAM, a condition can specify a page that only Human Resources admins 
    can access—for example, `https://hr.example.com`.

    ✅ Recommended: The `logID` field includes the domain `corpaudits.example.com`.

+   Text input (for example, `my-instance`)
+   [UI elements](https://developers.google.com/style/ui-elements) that are rendered based on 
    previously entered text input

    For example, if a reader was instructed in a procedure to enter an instance name as 
    `my-instance`, when you tell them to click the instance name, use code font and bold: 
    _Click `my-instance`_.

+   Generally, don't put quotation marks around code unless the quotation marks are part of the code.

**Items to put in ordinary (non-code) font**

+   Domain names.
+   URLs that the reader is supposed to follow in a browser.

    However, it's usually best to format a URL as a link and use descriptive link text instead of 
    exposing the URL itself. For more information, see 
    [Link text](https://developers.google.com/style/link-text).
+   Names of products, services, and organizations.

**Items that are sometimes in code font**

+   Often, command-line utility names are spelled the same as the software project or product with 
    which they are associated, with only differences in capitalization. In such cases, use code 
    font for the command and ordinary font for the name of the project or product.

    Recommended:

    +   Invoke the GCC 8.3 compiler using `gcc` for C programs or `g++` for C++ programs.
    +   To send the file over FTP with IPv6, use `ftp -6`.
    +   The options for the `curl` command are explained on the curl project website.
    +   The `apt` program includes commands from the `apt-get` and `apt-cache` programs for 
        working with APT packages.

+   If you want the reader to use the email address as computer input or output, use code font. 
    If you want the reader to treat the email address as a way to contact someone or a reference 
    to someone, use non-code font and hyperlink the email address.

    Recommended:

    +   Enter the username, not the full email address. For example, enter `alex`, not 
        `alex@example.com`.
    +   For help, contact [support@example.com](mailto:support@example.com).

**Method names**

+   When you refer to a method name in text, omit the class name except where including it would 
    prevent ambiguity.

    +   ✅ Recommended: To retrieve the zebra's metadata, call its `get()` method.
    +   ❌ Not recommended: To retrieve the zebra's metadata, call its `animal.get()` method.

    Put an empty pair of parentheses after a method name to indicate that it's a method.

**HTTP status codes**

+   To refer to a single status code, use the following formatting and phrasing:

    > an HTTP `400 Bad Request` status code

+   In particular, call it a _status code_ instead of a _response code_ or _error code_, and put 
    the number and the name in code font. If the _HTTP_ is implicit from context, you can leave it 
    out.

    To refer to a range of codes, use the following form:

    > an HTTP `2xx` or `400` status code

+   In particular, use _Nxx_ (with a specific digit in place of _N_) to indicate anything in the 
    _N00_-_N99_ range, and put the status code number in code font even if you're leaving out 
    the code's name.

    If you prefer to specify an exact range, you can do so:

    > an HTTP status code in the `200`-`299` range

    Here, too, put the numbers in code font.

**Grammatical treatment of code elements**

+   In general, don't use code elements such as keywords and filenames as if they were English 
    verbs or nouns. Don't inflect the name of a code element, such as to make it plural or 
    possessive. Instead, include a noun after the name of the code element, and inflect that noun.

    ✅ Recommended | ❌ Not recommended
    -- | --
    The `ADDRESS` constant's value is defined in the `settings.h` file. | `ADDRESS`'s value is defined in `settings.h`.
    To add the data, send a `POST` request. | `POST` the data.
    To retrieve the data, send a `GET` request. | Retrieve information by `GET`ting the data.
    You can't close the file before opening it. You can't call the `close()` method for a file before you call `open()`. | `Close()`ing the file requires you to have `open()`ed it first.
    Takes an array of extended ASCII code points (an array of `INT64` values) and returns `BYTES` values.For `STRING` arguments, returns the original string with all alphabetic characters in uppercase. | Takes an array of extended ASCII code points (ARRAY of INT64) and returns BYTES.

#### Capitalization

+   Use American English style for 
    [general capitalization](https://developers.google.com/style/capitalization).
+   Use sentence case in all [headings, titles, and 
    navigation](https://developers.google.com/style capitalization#capitalization-in-titles-and-headings).
    Use all-capitals for 
    [placeholders](https://developers.google.com/style/placeholders#placeholder-text).

#### Quotation marks

+   In general, use American English style when 
    [punctuating quotations](https://developers.google.com/style/quotation-marks).
+   For titles of shorter works—such as articles or episodes in a web series—put titles in 
    quotation marks, unless they're part of a link.

#### Font type, size, and color

+   Do not override global styles for [font type, size, or 
    color](https://developers.google.com/style/fonts).
+   Use [semantic HTML](https://developers.google.com/style/semantic-tagging) to control the style 
    of text on a page. For example, use code tags, `<code>` or ``` ` ```, instead of manually 
    styling text with a monospace font.

#### Other punctuation conventions

+   Don't use [ampersands (&)](https://developers.google.com/style/word-list#ampersand) as 
    conjunctions or shorthand for _and_. Use _and_ instead. That includes headings and navigation. 
    
    Exception: It's okay to use _&_ in cases where you need to refer to a UI element or the name of 
    a menu that uses _&_.

+   Put quotation marks and end punctuation
    [outside of link text](https://developers.google.com/style/link-text#punctuation-with-links).
