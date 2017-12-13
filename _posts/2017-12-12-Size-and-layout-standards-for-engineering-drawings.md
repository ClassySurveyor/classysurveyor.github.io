---
layout: post
title: Size and layout standards for engineering drawings
tags: naval-architecture drawings standards autocad drafting
thumb: loading-plan.jpg
---
Throughout my career and education, I have come across countless common practices and approaches to producing engineering drawings.  There are both national and international standards for engineering drawings.  However, they are not enforced.  As long as the message is clear, most of us accept drawings the way they are.  This is the first post in a series which will explore the standards for engineering drawings and today's post will focus on the basics - the page and the layout.

For all those who are *really* interested, you can of course read the ISO standards one by one, in detail, but to most this is time consuming and the standards themselves are expensive to have access to.  So this will be a concise summary of what is detailed in the below listed standards.  I cannot, unfortunately, post the standards themselves as they are protected by copyright.  I will, however, include some relevant snippets from:
- *ISO 5457:1999 Technical product documentation — Sizes and layout of drawing sheets*
- *ISO 7200:2004 Technical product documentation — Data fields in title blocks and document headers*

## Paper size
The internationally recognized paper sizes are those defined in ISO 216 - A0, A1, A2, A3, A4, etc.  For technical drawings, though, ISO 5457 is the reference and the smallest considered size should usually be A2, maybe A3 (rare), but no smaller than A4 (under very special circumstances).  All dimensions given below are in millimeters (mm).

<table>
	<tr>
		<th rowspan="2">Designation</th>
		<th colspan="2">Trimmed sheet</th>
		<th colspan="2">Drawing space</th>
		<th colspan="2">Untrimmed sheet</th>
	</tr>
	<tr>
		<td markdown="span">a<sub>1</sub></td>
		<td markdown="span">b<sub>1</sub></td>
		<td markdown="span">a<sub>2</sub> ± 0.5</td>
		<td markdown="span">b<sub>2</sub> ± 0.5</td>
		<td markdown="span">a<sub>3</sub> ± 2</td>
		<td markdown="span">b<sub>3</sub> ± 2</td>
	</tr>
	<tr>
		<td>A0</td>
		<td>841</td>
		<td>1189</td>
		<td>821</td>
		<td>1159</td>
		<td>880</td>
		<td>1230</td>
	</tr>
	<tr>
		<td>A1</td>
		<td>594</td>
		<td>841</td>
		<td>574</td>
		<td>811</td>
		<td>625</td>
		<td>880</td>
	</tr>
	<tr>
		<td>A2</td>
		<td>420</td>
		<td>594</td>
		<td>400</td>
		<td>564</td>
		<td>450</td>
		<td>625</td>
	</tr>
	<tr>
		<td>A3</td>
		<td>297</td>
		<td>420</td>
		<td>277</td>
		<td>390</td>
		<td>330</td>
		<td>450</td>
	</tr>
	<tr>
		<td>A4</td>
		<td>210</td>
		<td>297</td>
		<td>180</td>
		<td>277</td>
		<td>240</td>
		<td>330</td>
	</tr>
</table>

![ISO 5457 paper sizes]({{ site.baseurl }}/images/iso5457-paper-sizes.png)

Paper that comes in boxes/reems, they are considered to be "trimmed".  Paper that comes out of a plotter that prints from a roll, is printed on an "untrimmed" dimension by the printers, then trimmed to the required size manually or automatically.

## Margins and centering marks
According to ISO 5457, a margin of 20 mm shall be maintained on the left side of the sheet, and a margin of 10 mm shall be maintained on all the other sides of the sheet, measured from the trimmed edge.  However, this margin shall include the 5 mm grid frame (more on this below).

![ISO 5457 paper borders]({{ site.baseurl }}/images/iso5457-borders.png)

The centering marks are located at the horizontal and vertical centers of the "drawing space" and shall have a length of 10 mm, measured from the outer edge of the grid reference frame (i.e. the centering marks extend 5 mm into the "drawing space").

![ISO 5457 centering marks]({{ site.baseurl }}/images/iso5457-centering-marks.png)

## Border and frame
Two overlapping 10 mm x 5 mm rectangles in the shape of an "L" shall be placed on all four corners to assist with trimming (if necessary) - this is called a "Trimming mark".  A 5 mm wide grid reference frame shall be plotted around the "drawing space".  The number of fields (or cells) depends on the paper size but it shall be aligned from the "centering marks".  Each field shall have a length of 50 mm.

| **Designation** | **A0** | **A1** | **A2** | **A3** | **A4** |
|-----------------|--------|--------|--------|--------|--------| 
| **Long side**   | 24     | 16     | 12     | 8      | 6      | 
| **Short side**  | 16     | 12     | 8      | 6      | 4      | 

This arrangement will lead to some imperfect division of the drawing space but this okay - the grid system is just used (very rarely) for reference.  This difference should be included in the "corner cells".  The cells shall be marked with capital letters on the sides going from top to bottom (I and O shall not be used) and with numbers on the top and bottom going from left to right.  The size of the letters and characters shall be 3.5 mm.

For A4 papers, only the top and the right side have the grid reference frames.

The bottom-right corner field/cell can have the paper size printed in it also (if not part of the title block).

## Title block
The title block of engineering drawings are essential to reading the drawing itself - it should be the first thing an engineer should look at before looking at the rest of the drawing.  Its contents and design are of equal importance.

## Design
For A3 and larger sizes, the title block shall be placed at the bottom-right corner.  All sheets of this size and with this title block arrangement shall be positioned horizontally.  A4 sized paper shall have the title block on the shorter (lower) part of the drawing space and the sheet shall be positioned vertically.  The title block's direction dictates the reading of the drawing.

Although some engineering firms like to use a full-width or a full-length title block since this may be a more efficient use of drawing space, the ISO standard does not cover these designs.  Personally, I also do not like these designs because they do not serve well in the real world.  Drawings are usually over-sized and are stored by folding.  When folded, all of the data fields of the title block shall be legible.  When you have a full-length or a full-width title block, this is impossible.  As such, the best design is one that is at the bottom right corner and compact enough to save space and to include all the necessary information.

Although ISO 7200 does not specify required dimensions for title blocks, it suggests a width of 180 mm.  As you can see from the above table, the drawing space for an A4 sheet has a width of 180 mm so a title block of this dimension fits perfectly.  Any paper size greater than A4 should also have the same dimension for uniformity but also due to the fact that, as mentioned above, over-sized drawings are stored in a folded state (usually no larger than A4) and it is crucial to keep the width equal to or below 180 mm to avoid losing information behind the folds.

![ISO 7200 sample title blocks]({{ site.baseurl }}/images/iso7200-title-blocks.png)

## Data fields

ISO 7200 governs which data fields shall be incorporated in title blocks.  Obviously everyone can add more to the list but these are the minimally required and recommended data fields (M - Mandatory, O - Optional):

| **Field name**            | **Language-dependent** | **Recommended number of characters** | **Obligation** | 
|---------------------------|------------------------|--------------------------------------|----------------| 
| Legal owner               | -                      | Unspecified                          | M              | 
| Identification number     | No                     | 16                                   | M              | 
| Revision index            | No                     | 2                                    | O              | 
| Date of issue             | No                     | 10                                   | M              | 
| Segment/sheet number      | No                     | 4                                    | M              | 
| Number of segments/sheets | No                     | 4                                    | O              | 
| Language code             | No                     | 4 per language                       | O              | 
| Title                     | Yes                    | 25                                   | M              | 
| Supplementary title       | Yes                    | 2x25                                 | O              | 
| Responsible department    | No/Yes                 | 10                                   | O              | 
| Technical reference       | No/Yes                 | 20                                   | O              | 
| Approval person           | No/Yes                 | 20                                   | M              | 
| Creator                   | No/Yes                 | 20                                   | M              | 
| Document type             | Yes                    | 30                                   | M              | 
| Classification/key words  | No/Yes                 | Unspecified                          | O              | 
| Document status           | Yes                    | 20                                   | O              | 
| Page number               | No                     | 4                                    | O              | 
| Number of pages           | No                     | 4                                    | O              | 
| Paper size                | No                     | 4                                    | O              | 


**Legal owner** refers to the owner of the drawing - usually the engineering firm.

**Identification number** refers to the unique number assigned to each drawing, based on the company's numbering system.

**Language code** refers to the language code as assigned in ISO 639 - practically irrelevant for engineering

**Title** refers to the title of the drawing but it should, in general, be based on international, national or company standards and should not refer to a particular use or application - this can be done with the "Supplementary title".  Consistency in titling will allow for efficient search, retrieval and reference in future project.

**Document status** refers to review/approval statuses such as "Released for approval", "Approved", "Rejected", etc...

## Summary
Based on the above information, we can now create some standard drawing layouts for different paper sizes that are according to ISO 5457 and ISO 7000.  I created some below, available for free viewing and download.
