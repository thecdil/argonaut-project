---
title: Metadata
nav: true
---

# Create New Metadata 

To enhance Argonaut metadata, there is three basic steps that will be completed for each row in your Sheet:

1. Review Metadata
2. Record Headlines
3. Assign Subjects

Each step is described below. 
Please don't hesitate to get in touch if you have any questions or encounter issues!

{% capture review %}
Click the link in `cdm_pdf_link` to open up the issue's PDF for viewing.

On the PDF carefully check the issue information to ensure it actually matches the record's information:

- Check the `date` to ensure the issue is correct. If there is an mismatch, please let us know!
- Check the `title`. For *almost all* records the title will stay as is. However, if the issue has a special title highlighted on the front page, please add it to the end of the automated title after a dash. For example, [arg-1993-04-01](https://digital.lib.uidaho.edu/utils/getfile/collection/argonaut/id/9203/filename/arg-1993-04-01.pdf) is a special April Fools edition, the title field should be "April 1st, 1993 - Cosmonaut: Fools Issue".
- If the quality of the PDF is particularly bad, please let us know.

{% endcapture %}
{% include card.md text=review header="1. Review Metadata" %}

{% capture headlines %}
To create the `headlines` field, scan/skim the issue starting with the front page: 

- Type/copy all headlines from the front page into the spreadsheet, separating each using a semi-colon, `;`. 
- Browse through the rest of the issue and copy any additional major headlines, separating each using a semi-colon, `;`. After each additional headline add the PDF page number in parenthesis, like `(p2)`.

You do not need to copy all headlines in the issue. 
Instead focus on finding headlines that relate to university events and happening on campus. 
Imagine a future user wanting to discover interesting history relevant to the university and campus life.
Leave out headlines that are regular column titles, such as "NOTICE" or "In brief". 

{% capture notes %}
*Keep in mind* the basic format of the issues changes over time. 

Argonauts from early 1900's have a dense front page with many columns and many individual headlines. 
These headline will often include a larger title and a smaller subtitle. 
Please include both if it helps illuminate the topics covered. 
For example, "Home economics group will hear of eastern meet: University instructors to address district association tomorrow;".

Sometime past 1950's the format shifts to one more familiar today, with only a couple top stories appearing on the front page. 
"Headline" fields for these issues will include more items from additional pages. 
Often the front page will include a "contents" box that will be a good clue for finding important stories to include.
{% endcapture %}
{% include alert.md text=notes color="info" %}

{% endcapture %}
{% include card.md text=headlines header="2. Record Headlines" %}

{% capture subjects %}
To create the `subject` field, assign "subject terms" describing the notable topics covered by the issue. 
Separate each subject with a semi-colon, `;`.
Each issue will have a handful or more relevant terms.

After scanning through an issue, you should have a good sense of appropriate subjects.
Think about topics that might not be directly captured in the `headlines` text, but seem important to communicate what a major story is about.

Use the [subjects table]({{ '/content/3-subjects.html' | relative_url }}) to explore the terms used in the existing Argonaut metadata.
This will give you an idea of the types of terms that are applied.
Using the same terms will help users find related content across issues.

These subjects are U of I specific and do not use a controlled vocabulary.
They should help users discover unique content and topics such as news related to U of I specific organizations, people, and events.
The subjects should not try to cover everything in the issue, but represent a curated list of the most important and prevalent topics.

{% endcapture %}
{% include card.md text=subjects header="3. Assign Subjects" %}

## Tips

- Check the [Examples]({{ '/content/4-examples.html' | relative_url }}) page for, well, examples.
- Open the PDF in a new window so you can look at the Sheet and issue at the same time.
- Drag Sheet's text entry box down to make it bigger.
- Create your headlines/subjects in a notepad or Google Doc first, then paste the text into the correct cell with `Ctrl+V`.
