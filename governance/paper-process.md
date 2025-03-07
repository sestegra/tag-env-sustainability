# Process for creating papers

This document is intended to provide a consistent mechanism for cloud native environmental sustainability to produce community papers, ensure they are reviewed, and subsequently published.
Content of this document does not supersede existing processes and is intended to be used in conjunction with [existing proposal to project instructions](process.md).

## Proposal

If a proposal is made that includes a paper as a deliverable, the proposal needs to ensure that there is a clearly identified lead and a well defined paper scope.

The paper scope and topic should be raised in at least one TAG meeting to solicit more volunteers (ideally 4).
A diverse group of contributors from different companies/geos/backgrounds would be valuable.
Interested parties should meet at least once to describe the intent of the paper, & propose a very rough outline to present to TAG leadership for planning and scheduling as a project.

## Project

Once a TAG Leadership sponsor is assigned to the project, the group should meet to and agree on a tentative schedule.

### Tentative schedule milestones

The below list the minimum milestones that should be captured in a tentative schedule along with the estimated time frame for completion.
Milestones are explained further in this document.

| Task | Milestone | Estimated time |
| -- | -- | -- |
| * [ ] | Audience, Goals, & refining scope | 1 week |
| * [ ] | Tasking Assignment | 1 week |
| * [ ] | Content Outline | 2-3 weeks |
| * [ ] | Collaborative Review | 2 weeks |
| * [ ] | Executive Summary and content wrap up | 2 weeks |
| * [ ] | Narrative Voice | 1-2 weeks |
| * [ ] | Final Group Review | 1 week |
| * [ ] | Community Review | 2 weeks |
| * [ ] | Public comment adjudication | 2 weeks (simultaneous with review) |
| * [ ] | CNCF publishing engagement | ~2-3 weeks |
| * [ ] | Addition to the repo | 2 weeks |
| * [ ] | Blog post and publishing coordination | 2-3 weeks |

## Milestones

### Audience, Goals, and refining scope

This milestone is intend to define the following items to assist in generating content:

* Who do we expect to read the paper?
* What positions do they hold?
* Why are we writing this paper?
* What problem are we intending to resolve?
* What assumptions are we making about the audience or the expected content of the paper?
  * Note - these are documented in the "Introduction > Assumptions" section of the paper
* What are our Goals and Non-Goals?
  * Note - these are documented in the "Introduction > Scope > Goals" and "Introduction > Scope > Non-Goals"
* Is the scope in the issue still representative of what we intend to cover?

### Tasking assignment

Contributors should highlight and assign themselves to various areas of the outline.
This allows contributors to focus on a few areas and identify others where more contributors is needed.
If using a google doc for the paper, assignments may be done through the "assign to me" feature after highlight the area or by using the `+foo@bar.com` comment feature for the assignee's email.
Once task assignment is complete, contributors can begin content rough-in.

### Content rough-in

Assignees can provide content rough-in in a variety of ways.
They may provide raw content in the form of phrases, disjointed paragraphs, bullets on the topic, or draft content in the form of completed paragraphs.
If leveraging draft content, placing this content in quotes helps other reviewers know it is 'near-complete' and it should be reviewed as a holistic section.

#### Opinions

There may be situations where multiple differing views on the subject matter or controls implementation are expressed.
Authors should make every effort to discover the industry standard or practice and document it.
If none exists and the suggested content cannot be collaboratively resolved, it is the duty of the authors to capture the different views with references, benefits, and drawbacks or contingencies in order to provide the reader with enough information to reach their own conclusion.

#### References

It is important that any references used to generate paper content be cited appropriately through footnotes and within the references section.
This permits the reader to not only dig deep into a specific reference area but also provides source content and is a matter of good practice.

### Collaborative

Contributors now review all content roughed-in and transition raw content into draft content.
They may begin commenting on sections, expanding ideas, refining arguments, and providing citations.
Contributors are encouraged to discuss content specific items in the doc through comments whereas larger themes and writing decisions should be discussed in the corresponding slack channel.
This keeps the doc clean as well as documents thematic decisions in the primary collaboration & coordination channel.

### Executive summary and content wrap-up

If the paper exceeds five (5) pages, an Executive summary commensurate with the length of the document (but not to exceed 3 pages) should be written.
Content, comments, and other discussions should be closed out and finalized at this time.

### Narrative voice

The narrative voice is a semi-final pass of the paper to ensure it reads as a single, unified voice. It should ensure:

* the language origin is consistent throughout the document
  * lang_en or lang_us,
  * avoid regional slang
  * keep same phrasing
* acronyms are spelled out at their first use and then abbreviated later,
* footnotes and citations are consistent and not direct hyperlinks in the text
* vague terms are defined in a glossary or otherwise cited to the cloud native environmental sustainability lexicon in the repo,

### Final group review

This is the opportunity for the group to collectively review the polished paper prior to opening it for community review.  This should resolve and close out any outstanding items.

### Community Review

At this point the paper needs to be locked from editing with the exception of the Adjudicators (see below).
It should be made public with the permission settings such that suggestions and comments are permitted.
The lead will then provide a brief write up of a call to action with a link to the document and the due by date for comments.
This write up and corresponding links and details will be emailed to the Environmental Sustainability TAG mailing list, at which point we actively solicit public comment.

### Public comment adjudication

Prior to opening the paper for community review, the group should select no more than 3 Adjudicators from different organizations/companies and geolocations. These individuals are tasked with accepting/rejecting suggestions, and resolving comments from the community.
Any comments or suggestions that require larger discussion should be brought up in a group meeting and decisively resolved. These should be clearly documented with justification in the notes.

Decisive resolution is the practice by which the group attempts to immediately resolve the comment either as a won't do, out of initial scope, document options, or accept as is. The intent to expediently discuss (no more than two minutes), identify the remedy, and apply it.
This is done both in the interest of time but also in an effort to minimize gold-plating (perfection is the enemy of complete).

### CNCF publishing engagement

Once the comments on the paper are adjudicated the paper is ready for publishing. The TAG Leadership sponsor will work with the CNCF gather resources to assist in final edits and conversion to PDF and graphics inclusion (if needed).
They can also assist with the conversion to markdown. The paper lead will work with the TAG Leadership sponsor to review publishing drafts prior to final versioned copy and inclusion in the repo.

### Addition to the repo

The CNCF may initiate the PR for the converted markdown of the paper and the graphics.
The paper lead will need to create the paper's README.md that includes the following items to ensure the paper can receive community updates in alignment with the original intent:

* **Title**
* **About**: covers what the paper was about, a brief summary
* **Updates to the paper**: "intended to be a living document created and maintained for the community, by its members."
  * **Markdown**:  "maintained in markdown and all updates will be made in markdown."
  * **Contributing updates**: "All members of the community are welcome to contribute updates. We ask potential contributors to refer to the original design decisions, listed below, as guidance when determining the content of their updates. It is highly recommended that you seek peer review for your updates beyond that of the Technical Leads and Co-Chairs of the TAG."
  * **Versioning and publishing**: "It is expected that many minor updates will occur, corrections to grammar, spelling, clarification in language, translations, etc. When these occur they are considered minor changes to the overall content and will not warrant the regeneration of the PDF.  When significant changes to the intent, content, or numerous minor changes occur, the contributors will assess and determine if a new major version of the PDF needs published. When this decision is made, the markdown content will be converted to text document and sent to the CNCF technical writers to create the PDF. The PDF will then be published back into the repository annotating the new version, updating the links in the README.md accordingly.  Minor updates to the markdown shall receive a minor version bump indicated in the Metadata table of the document and recorded as WIP. When enough significant changes have been recorded, the markdown will be placed "In Review" (via PR) and solicited to the CNCF Environmental Sustainability TAG and TOC mailing list for review, at a minimum. Upon completion of review, the Environmental Sustainability TAG's TOC Liaison shall provide final approval on the PR. At which point the markdown state will be changed to "Approved" and merged."
* **Original design decisions**: this is important as it is intended to enable the original contributors to not be gateways to content updates and allows both reviewers and future contributors to understand a create content around centralized guidance.
* **Links**: include links to the files in the repo

### Blog publishing and coordination

In an effort to increase visibility and awareness of the final product, it is strongly recommended the paper lead coordinate with TAG leadership to engage the CNCF team for posting a blog to summarize and link to the paper.
As community events occur, it is also recommended that the TAG coordinate a submission to community events (presentation) on the paper.

To guide this process follow the steps outlines in the blog post [issue template](https://github.com/cncf/tag-env-sustainability/issues/new?assignees=&labels=blog+post&template=blog.md&title=Blog).

#### Authorship, attribution and acknowledgements

Papers and other resources created from the TAG Environmental Sustainability efforts are under the authorship of the TAG Environmental Sustainability, and all members who have made contributions to the document (through writing, editing, creating illustrations, etc.) are considered "Contributors".
Members of the public or Environmental Sustainability TAG who have commented and given feedback during the Request for Comment (RFC) period of during the creation of the document are considered "Reviewers" of the project.

Individuals/groups who have made huge contributions/impact on the work can be acknowledged in an "Acknowledgements" section.
This is to highlight stellar contributions and commitments by individuals that have went above and beyond to contribute to the project.

Each document should contain a "Contributors", "Reviewers" and "Acknowledgements" section where appropriate.
