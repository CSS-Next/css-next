*Note that this is a draft / template and just a suggestion by one person for the moment, this is by no means a final RFc*

# Rfc
The term "CSS3" has been widely used to encompass various additions and enhancements to Cascading Style Sheets (CSS) since around 2010. However, as CSS continues to evolve with new features and specifications, the blanket term "CSS3" has become insufficient and misleading. This RFC proposes the categorization of CSS properties into distinct groups, namely CSS3, CSS4, CSS5, and Future/Next, to better organize and facilitate understanding of the evolving CSS landscape. This categorization aims to improve adoption and ease of teaching, while not having a direct impact towards the CSS Working Group (CSSWG) operations and specifications.

## Reason

The term "CSS3" has been used to refer to all additions and enhancements to CSS since the early 2010s. However, CSS has continued to evolve beyond the scope of what was traditionally considered CSS3, leading to confusion in recruitment profiles, teaching materials, and documentation. This lack of clear categorization makes it challenging for developers to stay updated with the latest features and for educators to effectively teach CSS advancements and define specializations in the field.

## Proposal

### Categorization
Categorization is based on when new properties were introduced in a spec. This is to be browser(vendor) independent.


* **CSS3:** This category includes CSS properties and features introduced prior to the proposal to further categorize. It serves as a historical reference point for CSS advancements up to a certain point.
* **CSS4:** Properties and features introduced in a spec between 2014 - 2018.
* **CSS5:** Properties and features introduced in a spec between 2019 - 2022.
* **Future/Next**: This category encompasses properties and features that are currently in development or proposed for future versions of CSS beyond CSS5. It serves as a preview of upcoming CSS that are currently known.

### Implementation:

* Existing CSS properties and features will be retroactively categorized into CSS3, CSS4, or CSS5 based on their introduction dates in specs.
* New CSS properties and features will be categorized into Future/Next (name pending)
* The categorization process will be transparent and documented
* Each property has been deliberated extensively to easily fit this categorization.
* The categorization will not affect the numbering or operations of official CSS snapshots maintained by the CSSWG.

## Benefits

### Clarity and Organization
Clear categorization of CSS properties into CSS3, CSS4, CSS5, and Future/Next will provide developers, recruiters, and educators with a structured framework for understanding and discussing CSS advancements and skill level.

### Improved Adoption
By simplifying the presentation of CSS advancements, developers may be more inclined to explore and adopt new features, leading to broader utilization of modern CSS capabilities.

### Enhanced Teaching
Educators will have a clearer roadmap for teaching CSS advancements and could even be divided in different classes, making it easier to introduce concepts to students.

## Conclusion
The categorization of CSS properties into CSS3, CSS4, CSS5, and Future/Next offers a solution to the ambiguity surrounding the term "CSS3" and provides a structured framework for understanding and discussing CSS advancements. By implementing this proposal, we can improve adoption, teaching, and better organize the evolving landscape of CSS.