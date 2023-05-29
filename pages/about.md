---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: false
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="eap755_1_1_28_4" %} 



## About this website

This demo collection features items from the British Library's [Endangered Archives Programme](https://eap.bl.uk).

{% include feature/button.html text="Full EAP website" link="https://eap.bl.uk" color="success" %}
 
Photographs from the EAP collections:

- [EAP001: Faces and Places in Iran. Iranian photography at the turn of the 20th century, Iran](https://eap.bl.uk/project/eap001)
- [EAP755: A modern gaze on old cultural practices in Argentina: relocation and preservation of the 'Heinrich Sanguinetti Archive' (1930-1956), Argentina](https://eap.bl.uk/project/eap755)
- [EAP894: Endangered photographic collections about the participation of pre-industrial Bulgaria in three wars in the beginning of the 20th century, Bulgaria](https://eap.bl.uk/project/eap894)

This page has been used for testing some additional display features available with CollectionBuilder. All pages can be customised, and you can also create new pages, for example you could add a 'Blog' or 'Resources' page, which can also be added to the site navigation menu.

Some of the collection metadata has been changed to better demonstrate features such as the timeline below. 

{% include feature/timelinejs.html %}

{% include feature/pdf.html objectid="https://eap.bl.uk/sites/default/files/eap-french-flyer-print.pdf" width="50" caption="PDFs can also be collection items, or embedded from external websites like this PDF hosted on the EAP website" %}

{% include feature/card.html header="This is a Card" text="text description underneath" objectid="eap755_1_1_28_6" width="25" centered=true %}

{% include feature/modal.html button="Modal that displays other text as a popup" title="Message popup:" text="More info given here" color="primary" %}

{% include feature/image.html objectid="eap755_1_1_28_5" width="75" caption="an image" %}


{% include feature/image.html objectid="eap755_1_1_28_2" width="75" alt="EAP image" %}

{% include feature/image.html objectid="eap894_1_9_50;eap755_1_1_28_2;eap755_1_1_1_2" %}

{% include feature/image.html objectid="eap755_1_1_28_2;eap755_1_1_28_7" caption="EAP755;EAP755" link="https://eap.bl.uk/project/eap755" alt="Link back to EAP website;Link back to EAP website" %}
