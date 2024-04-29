# RFC
The term "CSS3" has been widely used to encompass various additions and enhancements to Cascading Style Sheets (CSS) since around 2010. However, as CSS continues to evolve with new features and specifications, the blanket term "CSS3" has become insufficient and misleading. This RFC proposes the categorization of CSS properties into distinct groups, namely CSS3, CSS4, and CSS5, to better organize and facilitate understanding of the evolving CSS landscape. This categorization aims to improve adoption and ease of teaching, while not having a direct impact towards the CSS Working Group (CSSWG) operations or the [Baseline initiative](https://github.com/web-platform-dx/web-features/blob/main/docs/baseline.md). 

## Reason

The term "CSS3" has been used to refer to all additions and enhancements to CSS since the early 2010s. However, CSS has continued to evolve beyond the scope of what was traditionally considered CSS3, leading to confusion in recruitment profiles, teaching materials, and documentation. This lack of clear categorization makes it challenging for developers to stay updated with the latest features and for educators to effectively teach CSS advancements and define specializations in the field.

## Proposal

### Categorization
Categorization is based on a variety of factors with the primary factor being the general timeline that an API was initially specified in the CSS Working Group. Additionally, implementer interest and adoption were moderately taken into account in the categorization process.


* **CSS3:** This category was established before this community group began articulating levels and was defined by the CSSWG, and was designed to be open ended. It serves as a historical reference point for CSS advancements up to a certain point.
* **CSS4:** Properties and features introduced in a spec around 2013 - 2018.
* **CSS5:** Properties and features introduced in a spec around 2019 - 2024.
* **Future/Next**: This category is a placeholder for properties and features that are currently in development or proposed for future versions of CSS beyond CSS5.

### Implementation:

* Existing CSS properties and features will be retroactively categorized into CSS3, CSS4, or CSS5 based on their introduction dates in specs.
* The categorization process will be transparent and documented
* Each property has been deliberated extensively to easily fit this categorization.
* The categorization will not affect the numbering or operations of official CSS snapshots maintained by the CSSWG and [Baseline initiative](https://github.com/web-platform-dx/web-features).

## Benefits

### Clarity and Organization
"Modern CSS" does not have any specific meaning or timeframe. Clear categorization of CSS properties into CSS3, CSS4, CSS5, and any future versions will provide developers, recruiters, employers, and educators with a structured framework for understanding and discussing CSS advancements and its evolution.

### Improved Adoption
By simplifying the presentation of CSS advancements, developers may be more inclined to explore and adopt new features, leading to broader utilization of modern CSS capabilities.

### Enhanced Teaching
Educators will have a clearer vocabulary and roadmap for teaching the evolution of CSS and better categorize modern CSS features.

## Conclusion
The categorization of CSS properties into CSS3, CSS4, CSS5, and any future versions offers a solution to the ambiguity surrounding the terms "CSS3" and "modern CSS", while providing a structured framework for understanding and discussing CSS advancements. By implementing this proposal, we can improve adoption, simplify education, and better organize the evolving landscape of CSS.