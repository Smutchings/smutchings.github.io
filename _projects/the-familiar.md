---
name: The Familiar Case Studies
tools: [Sketch, HTML, CSS]
image: /img/thefamiliarhero.png
description: A considered approach to displaying The Familiar's existing work through Case Studies.
---

# thefamiliar.tech Case Studies

When I joined [The Familiar Ltd](https://www.thefamiliar.tech) in July 2019, one of the first tasks I was given was to help bring the stories of our work to life through the addition of a [Case Studies section](https://www.thefamiliar.tech/case-studies) to the website.

Due to a sabbatical, there were only two of us working at The Familiar at the time. And this project played a role in a wider rebrand (from MPJDesign to The Familiar). This gave us freedom to create something new, but also meant that we were constrained in available time because of the nnumber of people and the fact we still had to operate as an agency.

## Laying the Groundwork

Before the designs for the Case Studies sections could be made, we had a lot of decisions to make and questions to answer. Questions and processes such as:

* Business Analysis - What’s best for the business right now? What is the priority?
* Website Analysis - What features of our website can best help us deliver those goals?
* Current State Evaluation - Where are we at now? What steps do we need to take to get to where we need to be?
* Research and Inspiration - What is the state of play for Case Studies? What inspires us?
* Functionality - What functionality do we need on our Case Studies page?
* Sketching, Wireframing and Prototyping - How do these features translate into a structure? 
* Defining Variables - colours, fonts, ratios, measures, etc
* Accessibility - checking everything against WCAG AAA, WCAG AA and WCAG AA Large (based on context)
* Hi-Fidelity Design - What do individual components look like? What do layouts look like?
* Technical Evaluation - What technical skills and tools do we need to execute on this?
* Documentation - Writing Documentation and Specifications to pass onto other designers, developers and for the future
* Development - Write up the HTML, CSS, etc for the site
* QA and Iteration - Test the website. See what needs improving/changing.
* Content Prep - prepare existing content and write new content for the Case Studies
* Deployment - Upload the new site and content to the server.
* Market - Support the launch with marketing to existing and potential clients.
* Evaluate - Evaluate success of the project against metrics - new business delivery.
* Move on - move to the next business objective, start cycle again.

In this piece, I'm going to cover a few of these questions and how we came to the answer we did.

## Accessibility

We decided early on that accessibility (No, I won't be shortening it to "A11Y" - S) would be a crucial component of The Familiar website, and that this would need to extend to the long-form content of our Case Studies as much as it does to the buttons and titles that surround it.

### Typography

Text makes up much of the body of a case study, so carefully chosen and execued typography would be essential in creating an accessible and enjoyable reading experience.

During development of The Familiar brand, Hurme Geometric Sans 4 was carefully chosen as the logo typeface for the company. This friendly-yet-modern-yet-professional typeface was thought to represent the personality of The Familiar. And its letter and symbols remain legibile at various sizes and through different weights.

The characteristics that made it so ideal for our logo also made it a great candidate for the body copy on thefamiliar.tech. This means that we could have a consistent typographic approach - from logo to body - whilst keeping legibility and accessibility.

To give the type presence, and to improve readability, we decided on a larger-than-usual 18px base size for our typography. Mixed with a 1.5 line height, we have a body font that is comfortable to read on all displays.

### Colours

When we started work on The Familiar, just two colours had been defined. These were Familiar Red and Familiar Black, the colours used in the Chough logo. A whole range of colours would need to be created from these to apply to the various uses needed on a website.

#### A Family of Colours

Based on these two colours, I worked with Martin Jewiss of The Familiar to create a family of colours which could be used for all the different cases we have on a modern website (with some created for the future).

From Familiar Red and Familiar Black, we created a family of 15 tones and hues. Colours which could be used for backgrounds, typography, frames, links and more.

<figure>
  <img src="/img/thefamiliar/colours-on-wall.jpeg">
  <figcaption>The Familiar colours can be found on the wall, wherever we work, as a reminder to all our family.</figcaption>
</figure>

These colours live on the walls of our offices as well as in The Familiar's design system Sketch library, so it's always at hand when designing something new for the company.

#### Contrast and Compare

During our colour exercise, we kept our accessibility goal front of mind. Every time a colour was introduced or changed, it was run through an accessibility check to ensure that it would suit us in its purpose. If the colour failed the check, pairings were adjusted to ensure that we had the accessible pairings we would need for our needs.

We tested our colours in Sketch using the [https://github.com/bryanberger/sketch-wcag](Sketch WCAG plugin by Bryan Berger). This plugin quickly takes the colours of selected shapes in Sketch and creates an HTML report showing the pairings that pass WCAG accessibility standards, and at what level.

<figure>
  <img src="/img/thefamiliar/wcag-colour-report.png">
  <figcaption>An excerpt from the report, showing which colours can be used against one of our highlight greys.</figcaption>
</figure>

Whilst the design of the Case Studies section of The Familiar website is minimalist, with few colours overlapping, we still wanted to make sure that we were hitting accessibility guidelines with our colour picks.

We are aware that there are some colours we use which wouldn't pass accessibility if they were used together, but these are colours we consciously do not use together.

For example, Familiar Red is only used as a highlight or where white or back will be used in large type on it. It is never used as a background for small type. 

### Semantic HTML

Working with The Familiar, we have a prescribed order in which we develop a website or web application. This order helps us ensure that we're creating websites and applications that break gracefully, keeping them accessible to the most people.

This process starts with the writing of semantic HTML, written to the living HTML 5 standard, to ensure that we're creating a structure that web browsers, screen readers, and even smart speakers are able to load and render.

Once we are happy with the HTML, we add styles through the use of CSS and SCSS, again working to the latest standards, with testing of across browsers on all platforms and back to IE11.

Once we're happy with the styles, we add additional functionality through the use of templating languages or Javascript. Again, this functionality is then rigourously tested, and only when we're happy with it will it pass Quality Assurance and be allowed onto the production site.

This process ensures that we consistently deliver online experiences we believe in, so it makes sense that we'd follow this on our own site as well as on those of our clients.

## Designing for Consumption

We knew that we were designing this Case Studies for consumption. We also knew who our target market was - key decision makers in businesses and organisations - and how busy they can be.

Because of this, we built features into the design of the site that would help set expectations and improve the reading rate of our Case Studies. 

### Sixty-Second Summary

Each of our Case Studies opens with a Sixty-Second Summary. In this summary, we highlight the core facts about a project as well as the bital statistics. For those in a rush, this helps them decide if the fuller Case Study is worth their time and attention.

<figure>
  <img src="/img/thefamiliar/tf-sss.png">
  <figcaption>Our popular Sixty-Second Summary helps people get the vital statistics and information of a project.</figcaption>
</figure>

For some, they will get all the information they're looking for from our Sixty-Second Summary, allowing them to go straight to contacting The Familar.

### Reading Time

All long-form content on The Familiar website shows the reading time, based on the typical reading speed for adult. This helps people understand how long the article they are about to read will be.

<figure>
  <img src="/img/thefamiliar/readingtime.png">
  <figcaption>Something as simple as a reading time indicator can help set expectations for what lies ahead.</figcaption>
</figure>

It also excludes the Sixty-Second-Summary, only including the words and content from where the reading time is shown, giving an accurate representation of the reading time.

We felt this was important, as we didn't want to over or under-report the length of our case studies. We wanted to get it just right!

### PDF Download

All of our Case Studies are available to download as a PDF, hand-set by one of our designers in specially designed templates for The Familiar case studies.

Whilst we could automate this process, we felt that the current solutions for doing so do not offer the same end result as hand-setting the document. And as we have experienced type-setters on our team, we felt that it was the best use and demonstration of our skills to do the PDF downloads this way.

As far as possible, the PDF Downloads are a truthful facsimile of the online experience. Though, unfortunately, they cannot support some medai types - such as video or audio - which we may use in the future.

## Priority of Features

As mentioned earlier on, the Case Studies project was developed at a point where The Familiar was just two people - myself and Martin Jewiss. Whilst we would later contract in a developer to help us with some aspects of the site, this constraint of applicable human hours meant that we had to prioritise features for the launch.

For example, when the Case Studies first launched, each was a statically-delivered, handwritten HTML and CSS page, served up by our CMS. It was only a month or so after launch that the Case Studies were turned into dynamically generated pages that could be written online and loaded easily into the CMS for delivery.

We also launched without the PDF Download. Time availability, which was dedicated to client work, meant that deliver of each PDF version was slow. As each PDF version became available, they were uploaded to their respective case study.

## Looking Back

If I were to tell the full story of developing the Case Studies for The Familiar, this post would be a lot longer than it already is. Martin, Claudia and I (The Familiar team), put a lot of time and effort into designing what we hope is an accessible and enjoyable reading experiences for new and existing customers.

Since we launched the Case Studies late last year, they have sparked much interest in our work, and have generated some promising leads. The content has also given us snippets and information to use in other areas, making the effort all the more worthwhile.

## Looking Forward

We'd like to add more to our Case Studies section. For one, we'd like to find a way to effectively PDF-ise our content, so that it can be available for download more easily. We feel this would be a great addition for us, and a great product we could offer our clients.

We're now working to add additional content and features to The Familiar website, such as a blog and landing pages. These will allow us to market the business more effectively.