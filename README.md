# CiteMe License for Open Source Software (CiteMe OSS)

The authors of great scientific publications often write great software to produce their findings. The CiteMe OSS license motivates them to open-source their software by getting acknowledged through citations.

![CiteMe's Magic]()

The CiteMe OSS license is based on the [ISC license](https://opensource.org/licenses/ISC). The ISC license is [approved by the Open Source Initiative](https://opensource.org/approval) and falls into the category of [permissive software licenses](https://en.wikipedia.org/wiki/Permissive_free_software_licence) similar to the [MIT license](https://opensource.org/licenses/MIT) and the [BSD 2-clause license](https://opensource.org/licenses/BSD-2-Clause). The middle section of the CiteMe OSS license which covers the citation requirements was added to the original ISC license text. To date the middle section was NOT reviewed by lawyers nor the Open Source Initiative. Therefore it was tagged as version zero.

---

## FAQ

- You want to **open-source your software** using the CiteMe OSS license?
    - Is CiteMe OSS the right choice for me?
    - How do I apply the license to my software?
    - Which sources should I reference in the license?
- You want to **use software** published under the CiteMe OSS license?
    - What do I need to consider when I am writing an article?
    - What do I need to consider when I am not writing an article?
    - What do I need to consider when I modify the software?

---

### You want to **open-source your software** using the CiteMe OSS license?

#### Is CiteMe OSS the right choice for me?

#### How do I apply the license to my software?

- LICENSE file in the root directory
- Header in each source file not necessary

#### Which sources should I reference in the license?

### You want to **use software** published under the CiteMe OSS license?

#### What do I need to consider when I am writing an article?

#### What do I need to consider when I am not writing an article?

#### What do I need to consider when I modify the software?

## Discussion of the clauses

```
CiteMe License for Open Source Software, Version 0 draft 2016-05-19. (CiteMe OSS v0 draft)
```

If the license is copied into a software repository it is commonly renamed to "LICENSE". In this case users of the software can still easily identify which license was applied.

```
Copyright (c) <4-digit year>, <Company, Institute, or Person’s Name>, <Email address (optional)>

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.
```

This is an unaltered copy of the upper part of the [ISC license](https://opensource.org/licenses/ISC).

```
If this software is used to make a contribution to the findings published in an article, then the author(s) of that article are requested to include a citation using the reference provided below.
```

This is the "cite me" part of the license. It intentionally says "used to make a contribution to the findings" which puts the decision whether a citation is necessary into the hands of the article authors. If e.g. Microsoft Excel was CiteMe OSS licensed and used by the authors it would clearly depend on *how* Excel is used. It may be used to just get a quick understanding of some data (no citation necessary) or to extract statistical information from some data which is added to the article (citation necessary).

In our opinion it is important to give them some leeway in the decision-making so that the article authors are more likely to use CiteMe OSS licensed software in preparation of their article.

However, the article authors' decision-making is decisively confined by the use of the words "contribution to the findings". "contribution" is not weighted - it may be a small or a big contribution. But the contribution has to be aimed towards the published "findings". The findings are the core of the article. This includes everything that was needed to produce the findings of the article - e.g. a machine learning system that was used to crunch data. But it also excludes software that contributed peripheral aspects of the article - e.g. the use of the LaTeX typesetting system if it was CiteMe OSS licensed.

This confinement is not only designed to give the article authors less choice when to cite or not to cite. It also safeguards them against citation requests that make no sense in the context of their article. As a result valid citation requests are usually relevant to the core value - the findings - of the article. Thus the authors are more likely to happily add the citation without any opposition.

```
Scientific articles shall include:

<APA formatted reference - see http://www.bibme.org/apa/journal-citation/new>
```

Publications in scientific journals, proceedings, etc. need an adequate reference. Although many researchers would prefer the BibTex format it should be a format easily readable by everyone. APA seems to be the most widely adopted format across all research fields.

```
Articles of any other type shall include:

<web link, e.g. to GitHub page or arXiv link>
```

This part was added with primarily blog articles in mind. Since references in blog articles are not counted by Google Scholar etc. it is more important to allow a citation more native to the blog readers reading experience. This is of course a web link to directly accessible content for further reading.

```
If this software is used as a component of a CiteMe OSS licensed third-party software that requests a citation which supersedes the reference provided in this license in regard to its relevance to the findings published in the article, then the citation requested in this license shall be optional.
```

Once the CiteMe OSS license gets wider adoption a naturally occurring effect will kick in: CiteMe OSS licensed software will be composed of many components that are themselves CiteMe OSS licensed. With that the chance increases that the authors of an article are requested to cite a long list of software components. To keep the list of citations short and reasonable this clause was added.

However, a citation may only be omitted if the on reference of a component is superseded by the parent third-party software in the context of the published article. The words were carefully chosen to minimise the chance that either the parent software or the component "steals" the citation right.

```
If a large portion of this software is modified, then the author of the modifications may replace the references provided in this license by references that have a higher scientific relevance in regard to contributions the modified software may make to publishable findings.
```

Although open-source software is often celebrated for their big communities the more common life of a regular open-source project is less sensational. If for example a researcher open-sources a great piece of software under the CiteMe OSS license and abandons its development after some time another researcher shall be able to pick up the project and continue its development. If that second researcher brings the software to the next level she should be allowed to receive acknowledgement though getting citations of her own article.

```
THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

This is an unaltered copy of the lower part of the [ISC license](https://opensource.org/licenses/ISC).