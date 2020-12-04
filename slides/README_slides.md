---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: myst
      format_version: '1.1'
      jupytext_version: 1.1.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---
**Details** <br />
Learn how to extract speaker diarized notes and meaningful insights reports using IBM® Watson™ Speech To Text, Watson Natural Language Processing, and Watson Tone Analysis when given any video.

🎓 What will you learn? <br />
- Use the Watson Speech to Text service to convert the human voice into the written word.
- Use advanced natural language processing to analyze text and extract metadata from content such as concepts, entities, keywords, categories, sentiment, and emotion.
- Leverage Watson Tone Analyzer cognitive linguistic analysis to identify a variety of tones at both the sentence and document level.

👩‍💻 Who should attend? <br />
Developers who are interested in AI and IBM Watson APIs.

+++ {"slideshow": {"slide_type": "subslide"}}

🎙️ Speakers
- Mridul Bhandari, IBM Developer Advocate, U.A.E - (https://www.linkedin.com/in/mridul-bhandari)
- Mostafa Abdelaleem, IBM Developer Advocate, Egypt -
(https://www.linkedin.com/in/mostafa-abdelaleem/)
- Fawaz Siddiqi, IBM Developer Advocate, UAE - (https://www.linkedin.com/in/fawazsiddiqi/)

🎈 Prerequisites <br />
1) Sign up to IBM Cloud using this link: https://ibm.biz/VideoInsights <br />
2) Register for the live event or watch the recording: https://www.crowdcast.io/e/extract-insights-from

👩‍💻Resources <br />
- GitHub Repository - https://github.com/fawazsiddiqi/VideoInsights
- Workshop Slides - https://fawazsiddiqi.github.io/VideoInsights/#/
- Survey - https://www.surveymonkey.com/r/HVQGC2M
- Meetup page - https://www.meetup.com/IBM-Cloud-MEA/events/ 

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide1.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide2.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide3.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide4.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide5.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide6.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide7.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide8.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide9.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide10.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide11.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide12.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide13.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide14.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide15.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide16.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide17.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide18.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide19.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide20.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide21.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide22.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide23.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide24.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide25.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide26.png?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![](https://github.com/fawazsiddiqi/VideoInsights/blob/master/doc/source/images/slide_images/Slide27.png?raw=true)


