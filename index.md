---
title: false
---
<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/cover.png" alt="advertisement for the conference" class="vid-fluid rounded center">
  </center>
</figure>

# Welcome!

<div id = "LOCAL_TIME"></div>
>SciTinyML: Scientific Use of Machine Learning on Low-Power Devices will be run virtually from October 18-22, 2021. <br> The Zoom link was sent out to all registered attendees. Please check your email and/or [sign up for our workshop](http://indico.ictp.it/event/9622/).

SciTinyML is an ICTP Virtual Meeting supported by the [TinyML4D Academic Network](https://tinyml.seas.harvard.edu/4D/AcademicNetwork) and open to all.

Embedded machine learning (tinyML) enables machine learning technologies to perform on-device analytics of sensor data at extremely low power. This allows for new scientific applications to be developed at an extremely low cost and at large scale.
 
In recent years, hardware advancements have made it possible for microcontrollers to perform calculations much faster. Improved hardware has made it easier for developers to build programs on these devices. Perhaps the most important trend for scientists has been the rise of embedded machine learning, or tinyML.
 
Between hardware advancements and the tinyML community’s recent innovations in machine learning, it is now possible to run increasingly complex deep learning models directly on microcontrollers. tinyML represents a collaborative eﬀort between the embedded power systems and machine learning communities, which traditionally have operated independently.
 
Topics:
+ Introduction to Embedded ML (tinyML)
+ Examples of tinyML applications
+ Scientific Applications of ML

<div class="message">
  We have also held 3 seminars leading up to the workshop. If you missed any of the seminars you can find the recordings on the <a href="https://tinyml.seas.harvard.edu/4D/pastEvents">TinyML4D Past Events</a> page.
</div>

### Workshop Schedule

[View the Detailed Schedule]({{ "/schedule" | relative_url }})

| Day   | Date             | Topics | Speakers |
|-------|------------------|----------------|----------------|
| Day 1 | Monday    | Introduction to Embedded ML (tinyML) | [Vijay Janapa Reddi](https://scholar.harvard.edu/vijay-janapa-reddi/home) of Harvard University and [Laurence Moroney](https://laurencemoroney.com/) of Google |
| Day 2 | Tuesday   | Hands on Embedded ML - Vision and Audio | [Brian Plancher](https://brianplancher.com/) and [Mark Mazumder](https://markmaz.com/) of Harvard University|
| Day 3 | Wednesday | Sensors and Ethical Issues for ML and IoT | [Serge Stinckwich](https://cs.unu.edu/people/experts/15926.html) and [Attlee Gamundani](https://unu.edu/experts/15908.html) of United Nations University Institute in Macau and [Sebastian Büttrich](https://nsrc.org/sites/all/themes/nsrc/bios/SebastianBuettrich.html) of IT University of Copenhagen |
| Day 4 | Thursday  | Hands on Embedded ML - Motion/Anomaly Detection and Scientific Applications | [Marcelo Rovai](https://www.linkedin.com/in/marcelo-jose-rovai-brazil-chile/) of UNIFEI and [Matthew Stewart](http://mpstewart.net/) of Harvard University |
| Day 5 | Friday    | Academic Network Next Steps and Closing Keynotes | [Marco Zennaro](http://users.ictp.it/~mzennaro/) of ICTP, [Hal Speed](https://www.linkedin.com/in/halspeed/) of Robotical, [Susan Kennedy](https://www.susan-kennedy.com/) of Santa Clara University, and [Pete Warden](https://petewarden.com/) of Google |

### Questions?
Contact [edu@tinyml.org](mailto:edu@tinyml.org) with any questions regarding this workshop.

### Supporters
We would like to thank **Harvard SEAS**, **tinyML Foundation**, **ICTP**, **Edge Impulse**, **Google**, and the **TensorFlow Lite Micro Team** for the continued support of all of our TinyML educational content!

<script>
  var start = new Date('10/18/2021 1:00:00 PM UTC');
  var end = new Date('10/18/2021 4:00:00 PM UTC');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from 1:00 PM to 4:00 PM GMT which is "
  var endString = " in your local timezone (according to your computer system time)."
  document.getElementById('LOCAL_TIME').innerHTML = startString + localTime + endString;
</script>