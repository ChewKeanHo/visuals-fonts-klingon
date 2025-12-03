# Klingon Font | (Holloway) Chew, Kean Ho's Creative Visuals

[![banner](/Pictures/banner_1200x630.svg)](#)

Klingon is a Klingon (ID: `*Piqd`) Display font designed by
[The Klingon Project Team](https://www.evertype.com/fonts/tlh). Its design is
based on fictional alphabetic used in [Star Trek](https://en.wikipedia.org/wiki/Star_Trek)
movie franchise, as of year 2025, owned by Paramount; presenting its space-theme
new space alien-like typeface. This font has multiple families:

* `Klingon pIqaD HaSta`  - standard Klingon typeface.
* `Klingon pIqaD Mandel` - the Klinzhai/Mandel script from The U.S.S. Enterprise
                           Officer's Manual (1980) typeface.
* `Klingon pIqaD vaHbo`  - whimsical variety based on free forms of hot wax in a
                           lava lamp.

The example above is using `Klingon pIqaD vaHbo`.

Since Star Trek is a registered copyright product, this font is **ONLY IDEAL for
testing Klingon unicode characters (`U+F8D0`-`U+F8FF`)**. Any other use are
**STRICTLY PROHIBITED** without written approval from the franchise owner.

This font was re-distributed mainly because Unicode.org registered Klingon as
[an official ISO-15924 script](https://en.wikipedia.org/wiki/Klingon_scripts)
but *provided no way to test them at all*. Thanks to this project team, we can
now have a proper font to test them. For character assignments, please refer to
https://www.evertype.com/standards/csur/klingon.html in which the following
are currently tracked:

```
U+F8D0	KLINGON LETTER A
U+F8D1	KLINGON LETTER B
U+F8D2	KLINGON LETTER CH
U+F8D3	KLINGON LETTER D
U+F8D4	KLINGON LETTER E
U+F8D5	KLINGON LETTER GH
U+F8D6	KLINGON LETTER H
U+F8D7	KLINGON LETTER I
U+F8D8	KLINGON LETTER J
U+F8D9	KLINGON LETTER L
U+F8DA	KLINGON LETTER M
U+F8DB	KLINGON LETTER N
U+F8DC	KLINGON LETTER NG
U+F8DD	KLINGON LETTER O
U+F8DE	KLINGON LETTER P
U+F8DF	KLINGON LETTER Q
U+F8E0	KLINGON LETTER QH
U+F8E1	KLINGON LETTER R
U+F8E2	KLINGON LETTER S
U+F8E3	KLINGON LETTER T
U+F8E4	KLINGON LETTER TLH
U+F8E5	KLINGON LETTER U
U+F8E6	KLINGON LETTER V
U+F8E7	KLINGON LETTER W
U+F8E8	KLINGON LETTER Y
U+F8E9	KLINGON LETTER GLOTTAL STOP
U+F8EA	(This position shall not be used)
U+F8EB	(This position shall not be used)
U+F8EB	(This position shall not be used)
U+F8ED	(This position shall not be used)
U+F8EE	(This position shall not be used)
U+F8EF	(This position shall not be used)
U+F8F0	KLINGON DIGIT ZERO
U+F8F1	KLINGON DIGIT ONE
U+F8F2	KLINGON DIGIT TWO
U+F8F3	KLINGON DIGIT THREE
U+F8F4	KLINGON DIGIT FOUR
U+F8F5	KLINGON DIGIT FIVE
U+F8F6	KLINGON DIGIT SIX
U+F8F7	KLINGON DIGIT SEVEN
U+F8F8	KLINGON DIGIT EIGHT
U+F8F9	KLINGON DIGIT NINE
U+F8FA	(This position shall not be used)
U+F8FB	(This position shall not be used)
U+F8FC	(This position shall not be used)
U+F8FD	KLINGON COMMA
U+F8FE	KLINGON FULL STOP
U+F8FF	KLINGON MUMMIFICATION GLYPH
```




## Verifying Content Integrity

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

To secure the content from unauthorized modification by anyone down to bit-level
(`0|1`), they are cryptographically signed using one or more cryptography tools
such as but not limited to:

* [GnuPG](https://gnupg.org); AND/OR
* [OpenSSL](https://www.openssl.org/).

The public key and the associated certificate are attached. Only the main owner
keeps and maintains the private keys. To verify the content's integrity:



### GnuPG

1. Install [GnuPG](https://gnupg.org) software if not present.
2. Download the target file and its detached signature file (the `.asc` file
   with the same filename).
3. Download the public key file (`.gpg`).
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ gpg --no-default-keyring --keyring /path/to/public.gpg --verify /path/to/file.asc
```



### OpenSSL

1. Install [OpenSSL](https://www.openssl.org) software if not present.
2. Download the target file and its detached signature file (the `.sig`/`.sign`
   file with the same filename).
3. Download the public certificate file (`.pem`) containing the public key
   within.
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ openssl dgst -verify /path/to/pubkey.pem -signature /path/to/file.sig /path/to/file
```




## Artificial Intelligence (A.I.) Decrees

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

This decree defines the project’s policy on the use of Artificial Intelligence.
The following sections list data lifecycle activities and indicate whether A.I.
is deployed. Unless explicitly stated otherwise (e.g. deployment with
specifics), A.I. is not used for these tasks.



### Data Sourcing & Acquisition

> [!Note]
>
> Example activities:
>
> * Performing enhanced web searches due to search engine pollution by A.I.
>   slop contents.
> * Performing completely auto-generated media such as but not limited to
>   images, videos, and audios.

* Multiple Large Language Model (LLM) A.I.s as the search engine for searching
  research materials across the Internet due to massive unwanted A.I publication
  slops.
* One or more LLM A.I.s as the grammar and language corrector and enhancer for
  superpervised improvement against human written content.



### Data Processing & Transformation

> [!Note]
>
> Example activities:
>
> * Performing multi-steps process development.
> * Performing data sanitization like data cleaning and data deduplication.
> * Performing data format compatibility conversion.
> * Constructing and optimizing data processing libraries.
> * Upscaling an image with neural network not achievable with conventional
    image manipulation technologies.

* No deployment.



### Data Storage & Security

> [!Note]
>
> Example activities:
>
> * Performing security and threat detection.
> * Performing `Data at Rest` encryption and health monitoring.
> * Performing encryption data storage management.
> * Performing automated data storage house-keeping.
> * Performing data storage devices health monitoring and mitigation.

* No deployment.



### Data Analysis & Insight Generation

> [!Note]
>
> Example activities:
>
> * Performing multi-steps data analytics.
> * Performing pattern detection and recognition.
> * Developing predictive modelling.
> * Developing natural language queries models.
> * Creating artificial intelligence's neural network models based on data
>   feeds.
> * Optimizing artificial intelligence's transfer learning, hyperparameter
>   tuning, etc.

* No deployment.



### Data Quality Validation & Assurances

> [!Note]
>
> Example activities:
>
> * Performing end-user use case simulated testings.
> * Performing automated sanity testings.
> * Performing penetration & security testings.
> * Performing anomaly detection testings.
> * Performing schema validations.
> * Performing automated testing of data pipelines.

* No deployment.



### Data Visualization & Reporting

> [!Note]
>
> Example activities:
>
> * Performing data graphical visualization creation based on data feeds.
> * Performing summarized dashboarding with graphical design and data feeds.
> * Performing report writing.
> * Performing prediction projections.

* No deployment.



### Data Governance & Compliance

> [!Note]
>
> Example activities:
>
> * Performing personal identifiable information (PII) filtration and removal.
> * Performing regulatory compliance checks (e.g., data filtration, censorship,
>   removal as required by law).
> * Performing compliance monitoring and validation.
> * Performing data lineage tracking and analysis.
> * Performing data audit trail analysis.

* No deployment.



### Data Sharing & Publication

> [!Note]
>
> Example activities:
>
> * Performing document's metadata creation.
> * Performing document translation.
> * Processing data publication licensing and management.

* No deployment.




## Maintainers' Notes

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

1. This is a **STRICTLY DECENTRALIZED SELF-SUFFICIENT git repository** so all
   critical and maintenance data and info **MUST** inside this repository.
   Anyone has this repository can operate without any restrictions or
   limitations.
2. **Only keep the `git` repository for font metadata and display purposes**.
   * Font files are binary objects which are **unsuitable for `git` commits**.
   * Use `git tag` and `releases` version control strategy instead.
3. **DO NOT use `git-lfs`** due to ambiguous and inconsistent storage allocation
   policies from various git service providers.
   * It will disrupt the work pipeline causing unwanted data losses downstream.
   * Some actually monetarily charge you for storage space.
4. All fonts **MUST be strictly licensed under
   [Open Font License](http://scripts.sil.org/OFL) without ANY private arbitrary
   terms (e.g. people from country X are prohibited to use; not allowed to
   re-distribute without payment; trademarked font, etc)**.
   * The goal is for downstream to use the font without fear of anything.
   * Some designers modify the license terms without considering its legal
     concequences into account. Also watch out for hidden modifications (The
     same license name with different license body).
   * When you have even a slightest doubt: **DROP** & **DO NOT** commit. There
     are a lot of fonts in the market to deal with.
5. To naturally monitor conflicting font families' names and IDs:
   * **Font Filename** - **STRICTLY THE SAME as the font family name**. If it is
     funny looking; leave it. It is *the creators' responsibilities* to sort out
     proper naming conventions. For any following type descriptor
     (e.g. `Regular` or `Bold`), it is first separated by a dash (`-`).
     Descriptor can be anything.
   * **Product SKU** - **STRICTLY THE SAME as the font family name only in
     lowercase basic Latin, number, and dash (`[a-z][0-9]-`)**. You **MUST**
     replace all spaces to dash (`-`) and non-compatible characters to their
     basic Latin counterparts (e.g. `&` -> `and`; `天宇` -> `tian-yu`). The SKU
     is used across various applications including repository URL construction.
   * If any of the above is conflicting with existing registered font(s):
     * Comply to Copyright laws: *the oldest (check its license ownership birth
       time) stays; the new ones get updated*. In any case, the default action
       is **dropping the new ones**.
     * If you have the resources to drive the upstream changes:
       * Make sure you are *prepared to possibly face any legal reprecussion*
         from any socially undesirable creators.
       * Drop the project with a public notice if things go sour.
6. When a font is qualified for re-dstribution, please **DO HELP** the upstream
   creators to clean up their license file and marketing pitches. This repo uses
   the unified copyright accreditations licensing pattern. Hence, you should do
   the following:
   * The upstream owns their repository/workspace; we own the re-distributed
     repository.
   * For `CREATORS.txt` or `CONTRIBUTORS.txt`:
     1. `CREATORS.txt` are for the legal entities that are responsible and own
        the project copyright like authors, principal designers, principal
        engineers, etc.
     2. `CONTRIBUTORS.txt` are for any legal entities that contributes to
        the project but are not owning the project copyright like pull-request
        contributors, curators, etc.
     3. Each files have their internal guides. Please comply accordingly.
   * `LICENSE.txt`
     1. Update the collective aliases (e.g. `The XYZ Project Authors`) matching
        the project correctly. The format is the same as the ones in
        `CREATORS.txt` and `CONTRIBUTORS.txt`.
     2. **ENSURE the creators entry is linked correctly with upstream websites**.
     3. When re-distributing a font, **ENSURE** the wording **CLEARLY STATES**
        that we **ARE NOT** the creators but a re-distributor.
     4. There should be **2 EMPTY lines** context separator between the
        copyright entities list and the first line of the first clause.
7. Please **ONLY USE AND SUPPORT** the following open source image editing
   software for securing software supply chain from unwanted threats (e.g.
   vendor-locked by any expensive or proprietary software):
   * **GIMP (http://gimp.org)** - for rasterized graphics maintenances and
     exporting non-vector graphic files.
   * **Inkscape (https://inkscape.org)** - for vector graphics maintenances and
     exporting SVG plain vector files.
   * **FontForge (https://fontforge.org)** - for assembling and developing font
     files.
8. For the thumbnail:
   * All known languages are already tabulated accordingly with their
     ISO3166-Alpha2 (e.g. `ZH`) and/or ISO15924 language scripts (e.g.
     `Hans`/`Hant` for `ZH` or entirely `ZH-Hans`/`ZH-Hant`).
   * If the language is unsupported with blank or tofu, leave it. That's the
     whole point of demonstrating the font's capabilities.
   * The languages'/scripts' elements are labelled and ID-ed with full english
     identifier using basic latin characters only for programming purposes.
   * The principal canvas **MUST BE SAVED** in `inkscape SVG format` and retain
     all legal attributes (license, copyright, etc). The files **MUST HAVE**
     `inkscape-` prefixes to avoid confusion. They are saved inside
     `Pictures/principal-canvas` directory.
   * The exported svg **MUST BE IN** `Plain SVG format` and retain all legal
     attributes (license, copright, etc). The files **MUST NOT HAVE**
     `inkscape-` prefixes. They are saved inside `/Pictures` directory.
   * The exported svg's texts **MUST BE** converted into `object path` data type
     and then `union` into a single `foreground` path object layer. This is to
     ensure the text remain consistent in the absent of font files (e.g.
     end-user shopping the font on storefront without owning the font).
9. For the artificial intelligence (A.I.):
   1. Use of A.I. **IS ALLOWED INTERNALLY** as long as:
      * You as a legal entity (e.g. person|organization) **BEARS FULLY LEGAL
        REPONSIBILITIES for ALL** your signed-off commitment.
      * Non-legal entities (e.g. bot|AI account|shadow account|alternate account)
        **ARE STRICTLY PROHIBITED FROM ANY SIGNED-OFF COMMITMENT**.
      * Update the A.I Decree section accordingly on any use of any kind of A.I.
   2. For any non-supervised or unatteneded automation; or "vibe" commitments,
      to comply with the previous, please **REJECT ALL WITH PREJUDICE AND BLOCK
      THE ENTITY WHEN NECESSARY**.




## License

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

* [Agreed GIMP License](.internals/terms-of-services/GimpORG-License.pdf)
* [Agreed GIMP Privacy Policy](.internals/privacy-policy/GimpORG-Privacy-Policy.pdf)
* [Agreed Inkscape License](.internals/terms-of-services/Inkscape-License.pdf)
* [Agreed Inkscape Privacy Policy](.internals/privacy-policy/Inkscape-Privacy-Policy.pdf)
* [Agreed (Holloway) Chew, Kean Ho's Upscaler License](.internals/terms-of-services/Upscaler-LICENSE.txt)

This entire repository is licensed under [SIL Open Font License](LICENSE.txt).
To ensure better understanding of this license, the following sub-sections will
briefly describe how to deploy the content.

For registered non-profit organizations (NGO), you are considered a
`Commercial Entity` the same as any for-profit organization by default. However,
you will be eligible for the NGO disbursement grant and receive exception
privileges from the creator(s).



### Attribution

Attribution is **OPTIONAL**. Whenever required, you **MUST** attribute back to
the creator(s) as follows:

```
Title: Klingon Font
Creators: The Klingon Project Team
Packaged-By: (Holloway) Chew, Kean Ho
Contact: hello@chewkeanho.com
SKU: chewkeanho-visuals-fonts-klingon
UUID: 91C74F69-E719-407E-ABD8-D6E12FB50132
License: SIL Open Font License (http://scripts.sil.org/OFL)
Repository Made On: 2026-04-21
Repository Made From: Malaysia, South East Asia
Procure: https://github.com/ChewKeanHo/visuals-fonts-klingon
```



### Ownership - Personal

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITHOUT**
> any monetary intention such as but not limited to:
>
> * Saving a local copy and then viewing via his/her own mobile device(s); OR
> * Saving a local copy and then viewing via his/her own personal computer; OR
> * Saving a local copy for artificial intelligence data training purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Ownership - Commercial

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITH** any
> monetary intention such as but not limited to:
>
> * Saving a local copy for enhancing his/her company's procurement list; OR
> * Saving a local copy for commercial artificial intelligence data training
>   purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**.



### Reference - Personal & Commercial

> [!NOTE]
>
> This targets any customer wanting to refer or to provide a guide for sourcing
> the original content for any 3rd-party entity **without directly displaying
> any portion of the original content**; **WITHOUT** any monetary intention such
> as but not limited to:
>
> * Academic research and paper writing; OR
> * New content creation linking to the original content **WITHOUT displaying
>   any of the original content** for his/her own streaming platform; OR
> * Content production and collection linking to original content **WITHOUT
>   displaying any of the original content**; OR
> * Web portfolio project linking to the original content **WITHOUT displaying
>   any of the original content**; OR
> * Event materials linking the original content **WITHOUT displaying any of the
>   original content**; OR
> * Meeting materials linking the original content **WITHOUT displaying any of
>   the original content**; OR
> * Advertisement contents linking the original content **WITHOUT displaying any
>   of the original content**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**.



### Integration - Personal

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITHOUT** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform **without any monetary gain**; OR
> * Content production and collection with displaying portion(s) of the original
>   content **without any monetary gain**; OR
> * Web portfolio project with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Event materials with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Meeting materials with displaying portion(s) of the original content
>   **without any monetary gain**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Integration - Commercial

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITH** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform; OR
> * Content production and collection with displaying portion(s) of the original
>   content; OR
> * Web portfolio project with displaying portion(s) of the original content; OR
> * Event materials with displaying portion(s) of the original content; OR
> * Meeting materials with displaying portion(s) of the original content; OR
> * Advertisement materials with displaying portion(s) of the original content.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**; AND
3. Using the font files for commercial integration (e.g. design works) and
   selling the output (not the font files) for commerical gains.



### Composition Remix - Personal

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITHOUT** any
> monetary intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform **WITHOUT** any profits
>   including advertisement commission; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform
>   **WITHOUT** any profits including advertisement commission; OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Composition Remix - Commercial

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITH** any monetary
> intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform;
>   OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**; AND
3. Using the font files for commercial integration (e.g. design works) and
   selling the output (not the font files) for commerical gains.



### Broadcast or Resell Redistribution - Personal

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITHOUT** any monetary intention such as but not limited to:
>
> * Sharing with family members; OR
> * Streaming the content via any streaming platform with private viewer
>   access; OR
> * Displaying the content in his/her gallery with privately invited guests; OR
> * Displaying the content in private, free entry open spaces like living room;
>   OR
> * Owning a copy of the original content and serving it as downloadable content
>   on a website in a private network (e.g. self-hosted home network); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**.



### Broadcast or Resell Redistribution - Commercial

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITH** any monetary intention such as but not limited to:
>
> * Streaming the content via any streaming platform with public or private
>   viewer access; OR
> * Displaying the content in any company's public events with free or payable
>   guest invites; OR
> * Displaying the content in any company's internal/private events with free or
>   payable guest invites; OR
> * Owning a copy of the original content and serving it as free OR payable
>   downloadable content on his/her website in any network (Internet, Intranet,
>   or private networks); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger; OR
> * Distributing the original content via multiple profit-earning streaming
>   platforms.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**.
