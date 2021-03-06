# Astro Machine Learning Resources

Here is a catalog of resources related to Machine Learning applications to Astronomy, Astrophysics and Astroparticles.   
Do not hesitate to suggest contributions.


## Table of contents

  - [Education](#education)

    - [Seminars](#seminars)
    - [Schools](#schools)
    - [Courses](#courses)
    - [Books](#books)


  - [Conferences and workshops](#conferences-and-workshops)

  - [Software](#software)

    - [Libraries](#libraries)
    - [Deep learning frameworks](#deep-learning-frameworks)


  - [Others resources](#others-resources)

  - [Papers](#papers)


## Education

### Seminars

- [CERN Data Science Seminars](https://indico.cern.ch/category/9320/)

- [Inter-Experimental LHC Machine Learning Working Group](https://iml.web.cern.ch/) Guest Seminars:

  - [Open challenges for improving Generative Adversarial Networks (GANs)](https://indico.cern.ch/event/673989/), by [Ian Goodfellow](http://www.iangoodfellow.com/) (October 27, 2017)

### Schools

> These schools are not necessarily entirely dedicated to ML

- [Lisbon Machine Learning School](http://lxmls.it.pt/2018/): at the time of writing the application is closed. From the main page you can find the slides from the previous edition of the school ([2017 edition](http://lxmls.it.pt/2017/?page_id=65) for example): moreover there are also the video recordings of the lectures from past years editions ([2017 Edition on Youtube](https://www.youtube.com/watch?v=oUgkl8Z8wt8&list=PLToLj8M4ao-fuRfnzEJCCnvuW2_FeJ73N), also [2016](https://www.youtube.com/watch?v=jFyg-Ps5B0s&list=PLToLj8M4ao-fymxXBIOU6sF1NGFLb5EiX) is available).

- [PAISS](https://project.inria.fr/paiss/): Artificial Intelligence Summer School, Grenoble, France, 2-6 July 2018

- [4th Machine Learning in High Energy Physics Summer School 2018](https://indico.cern.ch/event/687473/) (August 6-12, 2018)

- ASTERICS-OBELICS Schools
  - [First ASTERICS-OBELICS International School](https://indico.in2p3.fr/event/14227/), Annecy, France, 6-9 June 2017
  - [Second ASTERICS-OBELICS Internation School](https://indico.in2p3.fr/event/16864/), Annecy, France, 4-8 June 2018. A session dedicated to machine learning.


- [ADA IX Summer school](http://ada9.cosmostat.org/), Valencia, Spain, 20-22 May 2018



### Courses

- [Introduction to GANs](https://indico.cern.ch/event/655447/contributions/2742176/), by [Luke de Oliveira](https://ldo.io/) (November 3, 2017)

- [Frontiers with GANs](https://indico.cern.ch/event/655447/contributions/2742180/), by [Michela Paganini](http://mickypaganini.github.io) (November 3, 2017)

- [Nikhef Colloquium: "Teaching machines to discover particles"](https://indico.nikhef.nl/event/878/), by [Gilles Louppe](https://glouppe.github.io/) (September 29, 2017)

- [CERN Academic Training Lecture Regular Programme](https://indico.cern.ch/category/72/), April 2017 (Machine Learning):

  - [Machine Learning (Lecture 1)](https://indico.cern.ch/event/619370/) --- [Michael Kagan](https://www.linkedin.com/in/michael-kagan-06292616/) (SLAC)
  - [Machine Learning (Lecture 2)](https://indico.cern.ch/event/619371/) --- [Michael Kagan](https://www.linkedin.com/in/michael-kagan-06292616/) (SLAC)
  - [Deep Learning and Vision](https://indico.cern.ch/event/619372/) --- [Jonathon Shlens](https://research.google.com/pubs/JonathonShlens.html) (Google Research)

- [Deep Learning in High Energy Physics](https://youtu.be/cSxQPFb0yOw), by [Amir Farbin](http://www.uta.edu/physics/pages/faculty/profiles/farbin/index.html)

### Books

## Conferences and workshops

> These conferences and workshops are not necessarily entirely dedicated to ML

- [2nd ASTERICS-OBELICS workshop](https://indico.astron.nl/conferenceDisplay.py?ovw=True&confId=87), Barcelona, Spain, 16-19 October 2017    

- [ADASS series](http://www.adass.org/): Astronomical Data Analysis Software & Systems Conference Series

  - [ADASS XXVIII](http://adass2018.astro.umd.edu/), USA, 11-15 November 2018
  - [ADASS XXVII](http://www.adass.cl/), Santiago, Chile, 22-26 October 2017
  - [ADASS XXVI](http://www.adass2016.inaf.it/index.php), Trieste, Italy, 21-23 October 2016


- CHEP: International Conference in High Energy and Nuclear Physics

  - [CHEP2018](http://chep2018.org/), Sofia, Bulgaria, 9-13 July 2018
  - [CHEP2016](http://chep2016.org/), San Francisco, USA, 10-14 October 2016

- HAP Workshop: Big Data Science in Astroparticle Physics

  This workshop had a initial parte with a hands-on session on a GPU cluster.

  - [HAP 2017](https://indico.scc.kit.edu/indico/event/277/overview), RWTH Aachen University SuperC
  - [HAP 2018](https://indico.scc.kit.edu/indico/event/344/overview), RWTH Aachen University SuperC


## Software

### Libraries
- [scikit-learn](http://scikit-learn.org/): Python module for machine learning

- [AstroML](http://www.astroml.org/): Python module for machine learning and data mining in Astronomy

### Deep learning frameworks

- [TensorFlow](https://www.tensorflow.org/)
- [Theano](http://deeplearning.net/software/theano/)
- [PyTorch](http://pytorch.org/)
- [Caffe2](https://caffe2.ai/)
- [List of Conversion Tools For Saved Networks](https://github.com/ysh329/deep-learning-model-convertor)

### Data Converters

- [H.E.S.S. to HDF5](https://gitlab.com/ishilon/mcdst-to-h5)
- [CTA to HDF5](https://github.com/cta-observatory/dl_data_dumper/)


## Others resources

- [Resources for machine learning applications in High Energy Physics](https://github.com/iml-wg/HEP-ML-Resources.git) from which this page is largely inspired [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1147001.svg)](https://doi.org/10.5281/zenodo.1147001)

## Papers

[List of astro machine learning papers](astro_ml_bib.pdf)

> a .bib and associated .tex may be found in this repository.   
To add a reference:
- Update the .bib with reference including abstract
- run the .tex with biber (or pdflatexmk engine)
