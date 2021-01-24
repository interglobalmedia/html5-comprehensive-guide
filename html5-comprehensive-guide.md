<h1 class="capitalize">COMD2451</h1>
<h2 class=" capitalize center">HTML5: A Comprehensive Guide</h2>

---

<section class="section">
    <h2 class="sentence">The Purpose of This Slide Deck</h2>

The ***meaning*** and ***scope*** of what is **referred** to as `HTML5` reaches ***far*** and ***wide***.

This `HTML5 guide` is meant to ***bring together*** a `list` of `things` that make up `HTML5` as ***comprehensively*** as possible, thereby **informing** both `aspiring` and `seasoned` **developers/designers** of what is ***available*** under the `HTML5` umbrella.

This is an ***evolving*** `work` in ***progress***.
</section>

---

<section class="section">
    <h2 class="sentence">What is HTML5?</h2>

So **what** IS `HTML5`? 

`HTML5` is the ***latest*** `version` of the `standard` that ***defines*** `HTML` (`Hypertext Markup Language`), the **code** that *`"describes"`* **web pages**. 

***Technically***, it is made up of `3` kinds of **code**: `HTML(5) markup`, which ***provides*** the **page structure**, `Cascading Style Sheets` (`CSS(3)`), which ***provides*** the `presentation` (`styling`), and `JavaScript`, which ***makes*** `"things happen"` on the **page**.

`HTML5` **refers** to ***two*** different `concepts`. ***First***, it **refers** to a ***new version*** of the `HTML` language, containing ***new*** `elements`, `attributes`, and `behaviors`. ***Second***, it **refers** to a **set** of **technologies** that ***permits*** the `building` of more ***diverse*** and ***powerful*** `web sites` and `applications` (***driven*** by `JavaScript`).

</section>

---

<section class="section">
    <h2 class="sentence">Why HTML5?</h2>

`HTML5` was ***designed*** to be **usable** by ***all*** `"Open Web"` **developers**.

`HTML5` was ***also*** `designed` to `deliver` ***almost*** everything one would **need** for ***building*** `web sites` or `applications` online ***without*** the **help** of ***additional*** `software` such as `browser plugins`.

</section>

---

<section class="section">
    <h2 class="sentence">HTML5: Technology Classifications</h2>

+ `Semantics`: **allows** you to ***better describe*** your **content**. `HTML5` ***contains*** `semantic elements`, `elements` ***with*** `meaning`.

+ `Connectivity`: **allows** you to ***communicate*** with the `server` in ***new*** ways.

+ `Offline and Storage`: ***allows*** web pages to ***store*** `data` locally (i.e., `localStorage` or `sessionStorage`) on the `client-side` and to ***operate*** `offline` more ***efficiently***.

+ `Multimedia`: ***makes*** `video` and `audio` "first-class citizens" in the **Open Web**.

+ `2D/3D Graphics and Effects`: ***allows*** for a **much more** `diverse` ***range*** of `"presentation"` **options**.

+ `Performance and Integration`: provides ***greater*** `speed optimization` and ***better*** usage of `computer hardware`.

+ `Device Access`: ***allows*** for the **usage** of ***various*** `input` and `output` **devices**.

+ `Styling`: ***lets*** authors **write** more ***sophisticated*** `"themes"`.

</section>

---

<section class="section">
    <h2 class="sentence">Semantics Overview</h2>

According to [Shaye Howe](https://learn.shayhowe.com/html-css/getting-to-know-html/) in his **book** [Learn To Code HTML & CSS](https://learn.shayhowe.com/html-css/getting-to-know-html/),

> Semantics within HTML is the practice of giving content on the page meaning and structure by using the proper element. Semantic code describes the value of content on a page, regardless of the style or appearance of that content.

</section>

---

<section class="section">
    <h2 class="sentence">The importance of Semantic Elements</h2>

In order to be ***able*** to **build** `web sites` that **make sense** both to the `web browser` and the `web developer`, we ***need*** to **know** which `HTML elements` are ***best suited*** to ***different types*** of `content`. In **order** to ***know*** which `elements` to **use** for ***particular*** `types` of **content**, we **have** to ***know*** what ***different*** `elements` mean `semantically`. ***Additionally***, it is `important` to ***understand*** how ***various*** `elements` **render** to the `web page`.

In his **article** entitled [Semantic code: What? Why? How?](https://boagworld.com/dev/semantic-code-what-why-how/), Paul Boag ***best*** describes the `importance` of the ***meaning*** of `Semantic HTML`:

> Semantic code returns to this original concept and encourages web designers to write code that describes the content rather than how that content should look.
</section>

---

<section class="section">
    <h2 class="sentence">HTML5 Semantic Elements</h2>

A `semantic element` ***clearly*** describes its `meaning` ***both*** to the **web browser** and the **developer**.

***According*** to the [W3C (World Wide Web Consortium) Working Group](https://www.w3.org/TR/html5-diff/), the ***following*** `elements` were [introduced](https://www.w3.org/TR/html5-diff/) in `HTML5` for ***better*** structure:

`<section>`: ***represents*** a ***generic*** `document` or ***application*** `section`. It should be used together with the `h1`, `h2`, `h3`, `h4`, `h5`, and `h6` **elements** to ***indicate*** the `document` ***structure***.

`<article>`: ***represents*** an ***independent*** `piece` of **content** of a `document`, ***such as*** a `blog entry` or `newspaper article`.

`<main>`: ***represents*** the `main content` of the `body` of a `document` or ***application***.

`<aside>`: ***represents*** a `piece` of **content** that is only ***slightly*** related to the **rest** of the `page`.

`<header>`: ***represents*** a **group** of `introductory` or `navigational` ***aids***.

`<footer>`: ***represents*** a `footer` for a `section` and can ***contain*** `information` ***about*** the **author**, **copyright information**, etc.

`<nav>`: ***represents*** a `section` of the `document` ***intended*** for `navigation`.

`<figure>`: ***represents*** a `piece` of **self-contained** `flow content`, ***typically*** referenced as a **single unit** from the `main flow` of the `document`.

`<figcaption>`: can be ***used*** as a `caption` (it is ***optional***).

`<template>`: can be ***used*** to **declare** `fragments` of `HTML` that can be ***cloned*** and ***inserted*** in the `document` by `script`.

`<video>`, `<audio>`: for `multimedia content`. ***Both*** provide an `API` so **application** `Web developers` can `script` their ***own*** `user interface`, but there is ***also*** a **way** to ***trigger*** a `user interface` **provided** by the `user agent`. `source elements` are ***used together*** with these `elements` if there are `multiple streams` **available** of ***different*** `types`.

`<track>`: ***provides*** `text tracks` for the `<video>` **element**.

`<embed>`: is ***used*** for `plugin content`.

`<mark>`: ***represents*** a `run` of `text` in ***one*** `document` ***marked*** or ***highlighted*** for **reference purposes**, due to its **relevance** in ***another*** `context`.

`<progress>`: ***represents*** a **completion** of a `task`, such as `downloading` or when ***performing*** a **series** of ***expensive*** `operations`.

`<meter>`: ***represents*** a `measurement`, such as `disk usage`.

`<time>`: ***represents*** a `date` and/or `time`.

`<ruby>`, `<rt>`, `<rp>`: ***allow*** for ***marking up*** `ruby annotations`.

`<bdi>`: ***represents*** a `span` of `text` that is to be ***isolated*** from its **surroundings** for the ***purposes*** of ***bidirectional*** `text formatting`.

`<wbr>`: ***represents*** a `line break` ***opportunity***.

`<canvas>`: is ***used*** for **rendering** ***dynamic*** `bitmap graphics` on the ***fly***, such as **graphs** or **games**.

`<datalist>`: ***together*** with a ***new*** `list` **attribute** for `<input>` can be ***used*** to ***make*** `comboboxes`.

`<keygen>`: ***represents*** `control` for `key pair` ***generation***.

`<output>`: ***represents*** some `type` of ***output***, such as from a `calculation` ***done*** through `scripting`.

`<unput>` **element's** `type` ***attribute*** now has the following ***new*** `values`:

`tel`: ***defines*** a `field` for ***entering*** a `telephone number`. In ***addition***, it is ***best*** practice to **add** a `<label>` tag ***above*** the `tel` **input** for ***best*** `accessibility` ***practices***.

`search`: ***defines*** a `text field` for ***entering*** a `search` **string/query**. They are ***functionally*** the **same** as `inputs` of `type text`. A `name` **attribute** and ***corresponding*** `value` has to ***also*** be **set** for the `search field`, ***otherwise*** nothing will be `submitted`. In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `search` **input** for ***best*** `accessibility` ***practices***.

`url`: ***defines*** a `field` for ***entering*** a `url`. The `input` ***value*** is ***automatically*** `validated` (or `invalidated`) ***before*** the `form` can be ***submitted***. In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `url` **input** for ***best*** `accessibility` ***practices***.

`email`: ***defines*** an `input field` for an `e-mail` **address**. The `input` ***value*** is ***automatically*** `validated` to ***ensure*** it is a ***properly*** formatted `e-mail` **address**. In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `email` **input** for ***best*** `accessibility` ***practices***.

`date`: ***defines*** a `date picker`. The ***resulting*** `value` ***includes*** the `year`, `month`, and `day`. In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `date` **input** for ***best*** `accessibility` ***practices***.

`time`: ***defines*** a `control` for ***entering*** a `time` (no time zone). In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `search` **input** for ***best*** `accessibility` ***practices***.

`number`: ***defines*** a `field` for ***entering*** a `number`. The ***following*** `attributes` ***specify*** restrictions:

`max`: ***specifies*** the `maximum value` ***allowed***.

`min`: ***specifies*** the `minimum value` ***allowed***.

`step`: ***specifies*** the `number intervals` ***allowed***.

`value`: ***specifies*** the `default value`.

In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `number` **input** for ***best*** `accessibility` ***practices***.

`range`: ***defines*** a `control` for ***entering*** a `number` whose ***exact*** `value` is ***not*** important (like a `slider control`). ***Commonly*** used as `audio element controls` for `volume` or `balance`, or `filter controls`. The ***following*** `attributes` ***specify*** `restrictions`:

`max`: ***specifies*** the `maximum value` ***allowed***.

`min`: ***specifies*** the `minimum value` ***allowed***.

`step`: ***specifies*** the `number intervals` ***allowed***.

`value`: ***specifies*** the `default value`.

In ***addition***, it is ***best*** practice to add a `<label>` tag **above** the `range` **input** for ***best*** `accessibility` ***practices***.

`color`: ***defines*** a `color picker`. In ***addition***, it is ***best*** practice to ***add*** a `<label>` tag **above** the `color` **input** for ***best*** `accessibility` ***practices***.

According to `W3C`,

> The ***idea*** of these ***new*** `types` is that the `user agent` can ***provide*** the `user interface`, such as a ***calendar*** `date picker` or ***integration*** with the ***user's*** `address book`, and **submit** a ***defined*** `format` to the `server`. It ***gives*** the `user` a ***better*** experience as his/her `input` is ***checked*** before **sending** it to the `server`, ***meaning*** there is ***less*** time to **wait** for ***feedback***.

To learn more about the `W3C`, please visit [https://www.w3.org/](https://www.w3.org/).

To learn more about (initial) ***changes*** made to `HTML` with the ***introduction*** of `HTML5`, please visit the `W3C Working Group Note 9 December 2014` ***entitled*** [HTML5 Differences from HTML4](https://www.w3.org/TR/html5-diff/). The `changes` were quite ***extensive***!

</section>

---

<section class="section">
    <h2 class="sentence">Sections and Outlines in HTML5</h2>

***New*** `outlining` and `sectioning` ***elements*** in `HTML5`: [`<section>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section), [`<article>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article), [`<nav>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav), [`<header>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header), [`<footer>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer), [`<aside>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside)
</section>

---

<section xlass="section">
    <h2 class="sentence">Using HTML5 audio and video</h2>

The [`<audio>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio) ([Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API), [HTML5 HTMLMediaElement API](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)) and [`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) ([HTML5 HTMLMediaElement API](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)) `elements` ***embed*** and ***allow*** the **manipulation** of ***new*** `multimedia content`.

</section>

---

<section class="section">
    <h2 class="sentence">Forms improvements</h2>

The [constraint validation API](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation), ***new*** with `HTML5`, several ***new*** `attributes`, ***new*** `values` for the [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) **attribute** `type`, and the ***new*** [`<output>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/output) `element`.

</section>

---

<section class="section">
    <h2 class="sentence">Improvement to the <code>iframe</code> element</h2>

With ***help*** of the [`sandbox`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe#attr-sandbox) and [`srcdoc`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe#attr-srcdoc) `attributes`, **authors** can now be ***precise*** about the **level** of `security` and ***desired*** `rendering` of an `iframe` **element**.

</section>

---

<section class="section">
    <h2 class="sentence">MathML</h2>

[`mathML`](https://developer.mozilla.org/en-US/docs/Web/MathML) ***allows*** for the ***direct*** `embedding` of `mathematical formulas`.

</section>

---

<section class="section">
    <h2 class="sentence">HTML5-compliant parser</h2>

The [parser](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/HTML5_Parser), which ***turns*** the `bytes` of an `HTML document` into a `DOM`, has been ***extended*** in `HTML5`, and now ***precisely*** `defines` the **behavior** to ***use*** in **all cases**, ***including*** `invalid HTML`. This ***results*** in ***greater*** `predictability` and `interoperability` between `HTML5-compliant` **browsers**.

***Other*** helpful `resources`:

- [Downloadable HTML5 Guide](https://websitesetup.org/html5-cheat-sheet/) - A ***quick*** `guide` to `HTML5`, ***including*** the ***common*** `HTML` **tags** as well as the ***new*** `HTML5` **tags**. ***Downloadable*** in `PDF` and `PNG` ***formats***.

- [HTML5 Cheat Sheet](https://www.wpkube.com/html5-cheat-sheet/) - An ***easy-to-use*** `HTML5` **cheat sheet** for ***beginners*** – `2020`

- [Editable HTML5 Cheat Sheet](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) (HTML, CSS AND PHP:
THE ULTIMATE CHEAT SHEET) - A ***beginner-friendly*** and ***editable*** `cheat sheet` with `HTML5` ***examples*** that is ***aimed*** at ***anyone*** wanting to ***learn*** and **use** `HTML5`.

</section>

---

<section class="section">
    <h2 class="sentence">Connectivity</h2>

- [Web Sockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API): ***allows*** the **creation** of a ***permanent*** `connection` between the `page` and the `web server` and to ***exchange*** `non-HTML data` through ***that*** `means`.

- [Server-side events](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events): ***allow*** `servers` to ***push*** `events` to a `client`, ***rather*** than the ***classical*** `paradigm` where the `server` ***sends*** `data` **only** in ***response*** to a ***client's*** `requests`.

- [WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) - `RTC` ***stands*** for `Real-Time Communication`. It ***allows*** for `connecting` to ***other*** `people` and ***controlling*** `video conferencing` ***directly*** in the `browser`, ***without*** the **need** for a `plugin` or an ***external*** `application`.
 
</section>

---

<section class="section">
    <h2 class="sentence">Offline and Storage</h2>

- [Online and offline events](https://developer.mozilla.org/en-US/docs/Web/API/NavigatorOnLine/Online_and_offline_events) - `Firefox 3` ***supports*** `WHATWG` ***online*** and ***offline*** `events`, which ***let*** `applications` and `extensions` ***detect*** whether or not there's an ***active*** `Internet` ***connection***, as well as to ***detect*** when the **connection** goes ***up*** and ***down***.

- [WHATWG client-side session and persistent storage (aka DOM storage)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API) - ***Client-side*** `session` and `persistent` (`local`) `storage` ***allows*** `web applications` to ***store*** `structured data` on the **client side**.

- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - `IndexedDB` is a **web standard** for the ***storage*** of ***significant*** amounts of `structured data` in the `browser` and for ***high performance*** `searches` on this `data` **using** `indexes`.

- [Using files from web applications](https://developer.mozilla.org/en-US/docs/Web/API/File/Using_files_from_web_applications) - ***Support*** for the ***new*** `HTML5 File API` has been ***added*** to `Gecko`, making it ***possible*** for `web applications` to ***access*** `local files` ***selected*** by the `user`. This ***includes*** `support` for ***selecting*** `multiple files` **using** the [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input[) of [type](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Input#attr-type) `file` HTML element's ***new*** [multiple](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Input#attr-multiple) `attribute`. There ***also*** is [FileReader](https://developer.mozilla.org/en-US/docs/Web/API/FileReader).

</section>

---

<section class="section">
    <h2 class="sentence">Multimedia</h2>

- [HTML5 audio and video](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content) - The `<audio>` and `<video>` elements ***embed*** and ***allow*** the ***manipulation*** of `multimedia content`.

- [WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) - ***This*** `technology`, where `RTC` ***stands*** for `Real-Time Communication`, allows ***connecting*** to **other people** and ***controlling*** `video conferencing` ***directly*** in the `browser`, ***without*** the **need** for a `plugin` or an ***external*** `application`.

- `Track and WebVTT` - The [`<track>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/track) **element** ***allows*** `subtitles` and `chapters`. [`WebVTT`](https://developer.mozilla.org/en-US/docs/Web/API/WebVTT_API), which ***stands*** for `Web Video Text Tracks Format`, is a `track` ***text format***.

</section>

---

<section class="section">
    <h2 class="sentence">2D/3D Graphics</h2>

- [HTML5 Canvas Tutorial](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Learn about the [`<canvas>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas) **element** and how to ***draw*** `graphs` and `objects` in the **browser**.

- [HTML5 Text API for `<canvas>` elements](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text) - The `HTML5 text API` is now ***supported*** by `<canvas>` **elements**.

- [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) - `WebGL` ***brings*** `3D graphics` to the **Web** by ***introducing*** an `API` that ***closely*** conforms to `OpenGL ES 2.0` that can be ***used*** in `HTML5` `<canvas>` ***elements***.

- [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG) - An `XML-based` ***format*** of `vectorial images` that can ***directly*** be **embedded** in the `HTML`.

</section>

---

<section class="section">
    <h2 class="sentence">Performance and Integration</h2>

+ [Web Workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers) - ***allows*** the **delegation** of `JavaScript` ***evaluation*** to `background threads`, ***allowing*** these **activities** to ***prevent*** slowing down `interactive events`.
  
+ [XMLHttpRequest level 2](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest) - ***central*** to [AJAX](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX) (`Asynchronous JavaScript and XML`), ***allows*** the `asynchronous fetching` of ***some*** parts of a `web page`, ***allowing*** it to ***display*** `dynamic content`.
  
+ [History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API) - ***allows*** the ***manipulation*** of the `browser history`. This is ***especially*** useful for `pages` ***loading*** interactively ***new*** information. ***Used*** a ***lot*** in the `ReactJS` (`front end`) `library`.

+ [The contentEditable Attribute](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Editable_content) - `HTML5` has ***standardized*** the `contentEditable` ***attribute***.
  
+ [Drag and Drop](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API) - The `HTML5 drag and drop API` ***allows*** `support` for ***dragging*** and ***dropping*** items ***within*** and ***between*** `web sites`.
  
+ [Focus management in HTML](https://developer.mozilla.org/en-US/docs/Web/API/Document/hasFocus) - The (***new***) `HTML5 activeElement` and `hasFocus` ***attributes*** are **supported**.
  
+ [Web-based protocol handlers](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/registerProtocolHandler/Web-based_protocol_handlers) - You can now ***register*** `web applications` as `protocol handlers` ***using*** the `navigator.registerProtocolHandler()` ***method***.
  
+ [requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame) - ***Allows*** `control` of `animations rendering` to ***obtain*** `optimal performance`.
  
+ [Fullscreen API](https://developer.mozilla.org/en-US/docs/Web/API/Fullscreen_API) - ***Controls*** the ***usage*** of the `whole screen` for a `Web page` or `application`, ***without*** the `browser UI` ***displayed***.
  
+ [Pointer Lock API](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_Lock_API) - ***Allows*** `locking` the `pointer` to the ***content***, so `games` and ***similar*** `applications` ***don't lose*** `focus` when the `pointer` ***reaches*** the `window` ***limit***.
  
+ [Online and offline events](https://developer.mozilla.org/en-US/docs/Web/API/NavigatorOnLine/Online_and_offline_events) - In **order** to ***build*** a ***good*** `offline-capable` ***web*** `application`, you ***need*** to ***know*** when your `application` is ***actually*** `offline`. You ***also*** need to ***know*** when your `application` has ***returned*** to an `online status` ***again***.

+ [Detecting device orientation](https://developer.mozilla.org/en-US/docs/Web/API/Detecting_device_orientation) - ***Gets*** the **information** when the `device` on which the `browser` ***runs*** `changes orientation`. This can be ***used*** as an `input device` (e.g., to ***make*** `games` that ***react*** to the `position` of the `device`) or to ***adapt*** the `layout` of a ***page*** or to the `orientation` of the ***screen*** (`portrait` or `landscape`).

+ [Pointer Lock API](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_Lock_API) - ***Allows*** `locking` the `pointer` to the `content`, so `games` and ***similar*** `applications` ***don't*** lose `focus` when the `pointer` ***reaches*** the `window` ***limit***.

</section>

---

<section class="section">
    <h2 class="sentence">Styling</h2>

`CSS` has been ***extended*** to **be able** to ***style*** `elements` in a ***much more*** `complex` ***way***. This is often ***referred*** to as `CSS3`, though `CSS` is ***not*** a ***monolithic*** `specification` any more and the ***different*** `modules` are ***not*** all at `level 3`: ***some*** are at `level 1` and ***others*** at `level 4`, with ***all*** the ***intermediate*** `levels` ***covered***.

+ `New background styling features` - It is now ***possible*** to put `shadows` on `elements` ***using*** [box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow), [multiple backgrounds](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5), and `CSS` [filters](https://developer.mozilla.org/en-US/docs/Web/CSS/filter). You can ***learn more*** about `these` by ***reading*** [Advanced box effects](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Advanced_styling_effects).

+ `More fancy borders` - ***Not only*** it is now **possible** to ***use*** i`mages` to ***style*** `borders`, ***using*** [border-image](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image) and its ***associated*** `longhand properties`, but ***rounded*** `borders` are ***supported*** via the [border-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius) **property**.

+ `Animating your style` - ***Using*** [CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions) to ***animate*** between ***different*** `states` or ***using*** [CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations) to ***animate*** `parts` of the `page` ***without*** a `triggering event`, you can now ***control*** `mobile elements` on your `page`.

+ `Typography improvement` - ***Authors*** have ***better*** `control` to reach ***better*** `typography`. They can ***control*** [text-overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/text-overflow) and `hyphenation`, but ***also*** can ***add*** a [shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow) to it or ***control*** more ***precisely*** its `decorations`. ***Custom*** `typefaces` can be ***downloaded*** and ***applied*** thanks to the ***new*** [@font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) `at-rule`.

+ `New presentational layouts` - In ***order*** to ***improve*** the `flexibility` of ***designs***, `two` ***new*** `layouts` have been ***added***: the `CSS` [multi-column](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Columns/Using_multi-column_layouts) `layouts`, `CSS` [flexible box](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) (Flexbox) `layout`, and [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) `layout`, for ***example***.

</section>

---

<section class="section">
    <h2 class="sentence">Device Access</h2>

+ [Touch events](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events) - `Handlers` to ***react*** to `events` ***created*** by a `user` ***pressing*** `touch screens`.

+ [Geolocation](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) - ***Lets*** `browsers` ***locate*** the `position` of the `user` ***using*** `geolocation`.

</section>

---

<section class="section">
    <h2 class="sentence">Related Resources</h2>

+ [HTML5 (MDN)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)

+ [HTML5: what is it?](https://www.techradar.com/news/internet/web/html5-what-is-it-1047393)

+ [What is the open web and why is it important? Submitted by: Mark Surman, Executive Director of the Mozilla Foundation](https://www.yearofopen.org/november-open-perspective-what-is-open-web/what-is-the-open-web-and-why-is-it-important-submitted-by-mark-surman-executive-director-of-the-mozilla-foundation/)

+ [What is the open web and why is it important? Submitted by: Mark Surman, Executive Director of the Mozilla Foundation](https://www.yearofopen.org/november-open-perspective-what-is-open-web/what-is-the-open-web-and-why-is-it-important-submitted-by-mark-surman-executive-director-of-the-mozilla-foundation/)

+ [HTML5 Content Categories (MDN)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories)

+ [HTML5 Differences from HTML4 (W3C)](https://www.w3.org/TR/html5-diff/)

</section>
