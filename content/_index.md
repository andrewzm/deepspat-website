---
####################### Banner #########################
banner:
  title : "Deep Learning for Spatial and <br> Spatio-Temporal Statistics"
#  image : "images/statsgpu.png"
  content : "Webpage on work done at the University of Wollongong, Australia, since 2018, on the application of deep learning models to spatial and spatio-temporal statistical models. This work was in large part funded by the Australian Research Council (ARC) Discovery Early Career Research Award (DECRA) DE180100203 awarded to Andrew Zammit-Mangion."
#  button:
#    enable : true
#    label : "Contact Us"
#    link : "contact"


##################### under banner text #####################
under_banner_text:
  enable : true
  title : "About Me"
  image : "images/Andrew.png"
  content : "My name is Andrew Zammit-Mangion and I am an Associate Professor in Statistics with the National Institute for Applied Statistics Research Australia (NIASRA) at the University of Wollongong. I completed my PhD in 2012 at the University of Sheffield, UK in the Department of Automatic Control and Systems Engineering before carrying out brief post-docs at the University of Edinburgh with the School of Informatics and the University of Bristol with the Department of Maths and the School of Geographical Sciences. I joined NIASRA in 2014 and have been here ever since!

\

This page highlights some of the key projects I have participated in with some great students and collaborators as part of the Discovery Early Career Research Award (DECRA) that I was awarded in 2017, titled ``Deep space-time models for modelling complex environmental phenomena'' (see Collaborators and Students). The DECRA was invaluable in giving me the time to explore some ideas that I had for several years since my time in the UK, and to connect with several international researchers. Please take a browse of the below projects; the synopsis for each project is left to be deliberately short, and clicking on `Read more' will direct you to a published work with more details.

\

If you’d like to follow me on Twitter, my handle is @andrewzm."


  button:
    enable : false
    label : "Contact me"
    link : "contact"

##################### under banner text2 #####################
under_banner_text2:
  enable : true
  title : "Key Projects"


##################### Feature ##########################
#feature:
#  enable : true
#  title : "Something You Need To Know"
#  feature_item:
#    # feature item loop
#    - name : "Clean Code"
#      icon : "fas fa-code"
#      content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"

#    # feature item loop
#    - name : "Object Oriented"
#      icon : "fas fa-object-group"
#      content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
#
#    # feature item loop
#    - name : "24h Service"
#      icon : "fas fa-user-clock"
#      content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
#
#    # feature item loop
#    - name : "Value For Money"
#      icon : "fas fa-heart"
#      content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
#
#    # feature item loop
#    - name : "Faster Response"
#      icon : "fas fa-tachometer-alt"
#      content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
#
#    # feature item loop
#    - name : "Cloud Support"
#      icon : "fas fa-cloud"
#      content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil" -->



######################### Service #####################
service:
  enable : true
  service_item:
    # service item loop
    - title : "Deep Compositional Spatial Models"
      images:
      - "images/AWURBF2D.png"
      content : "Nonstationarity in spatial processes can be constructed by warping space and subsequently defining a stationary process on the warped domain. In this project, together with [James Ng](https://scholar.google.com/citations?user=a2ahoJIAAAAJ&hl=en), [Quan Vu](https://quanvu17.wordpress.com/), and [Maurizio Filippone](https://www.eurecom.fr/~filippon/),  we describe a warping approach that allows for straightforward fitting and prediction with univariate spatial data. The model, uses low-dimensional injective warping functions which can either be estimated using maximum likelihood or inferred using stochastic variational Bayes. "
      button:
        enable : true
        label : "Read more"
        link : "https://www.tandfonline.com/doi/abs/10.1080/01621459.2021.1887741?journalCode=uasa20"


    - title : "Multivariate Deep Compositional Spatial Models"
      images:
      - "images/multivariatewarping2.png"
      content : "In this project, led by [Quan Vu](https://quanvu17.wordpress.com/) and together with [Noel Cressie](https://www.uow.edu.au/niasra/our-research/centre-for-environmental-informatics/people/people/#d.en.138780), we extended the deep compositional spatial models outlined in the previous project to the multivariate case. Here, we model the joint processes using stationary, symmetric, covariance functions on the warped domain. There are many interesting properties that arise when modelling nonstationarity and asymmetry in this way; see main text for more details."
      button:
        enable : true
        label : "Read more"
        link : "http://doi.org/10.5705/ss.202020.0156"

    - title : "Convolution Neural Network Spatio-Temporal Models "
      images:
      - "images/BallResults2.png"
      content : "Dynamic spatio-temporal models are often used to model highly dynamic geophysical or ecological processes, such as daily sea-surface temperature or the spread of an invading species. Often, the dynamics themselves (e.g., the direction of flow) changes rapidly in both space and time. In this project, together with [Chris Wikle](), we integrate a convolution neural network with a statistical spatio-temporal model to jointly predict the spatio-temporal varying dynamical parameters and the process of interest."
      button:
        enable : true
        label : "Read more"
        link : "https://www.sciencedirect.com/science/article/abs/pii/S2211675320300026?via%3Dihub"


    - title : "Intensity Function Estimation on the Plane using Neural Autoregressive Flows"
      images:
      - "images/PP_Transport.png"
      content : "Neural autoregressive flows are injective maps constructed using deep neural networks, often used for density estimation or for variational inference in machine learning. In this project led by [James Ng](https://scholar.google.com/citations?user=a2ahoJIAAAAJ&hl=en), we use normalising flows to estimate the intensity function of a non-homogeneous Poisson process on the plane. We also show that the modelling architecture we use exhibits an attractive universal approximation property."
      button:
        enable : true
        label : "Read more"
        link : "https://arxiv.org/abs/2007.00248"


    - title : "Intensity Function Estimation on the Sphere using Radial Flows"
      images:
      - "images/spherePP.png"
      content : "Geophysical event data (e.g., earthquake occurrence) are often presented to the analyst as a set of spherical coordinates. Here, in this project led by [James Ng](https://scholar.google.com/citations?user=a2ahoJIAAAAJ&hl=en), we use radial flows within a measure transport framework to constuct a flexible model for the intensity function of a non-homogeneous point process on the sphere."
      button:
        enable : true
        label : "Read more"
        link : "https://arxiv.org/abs/2007.00248"



    - title : "Spatio-Temporal Emulation using Convolution Variational Autoencoders"
      images:
      - "images/CVAE.png"
      content : "Some computationally-intensive numerical models, such as Lagrangian Particle Dispersion Models (LPDMs), take a spatio-temporal location as an input (e.g., a source location) and generate a spatio-temporal output (e.g., the spatio-temporal evolution of a gas). In this project, led by [Laura Cartwright](https://scholar.google.com/citations?user=CMee9DIAAAAJ&hl=en), we take advantage of spatial and temporal correlations of the numerical-model output to emulate outputs at other, new, input locations. Emulation is done on a small-dimensional space constructed via a convolutional variational autoencoder. "
      button:
        enable : true
        label : "Read more"
        link : ""


    - title : "Multi-Resolution Spatial Modelling"
      images:
      - "images/Ypred01err_Global.png"
      content : "Fitting spatial models to big, remote, sensing data is often challenging even if the model one is fitting is relatively simple. However, in order to take advantage of the information in big data sets, one also needs to use more complex models. Here, together with [Jonathan Rougier](https://www.rougierconsulting.com/), we construct a model using multiple spatial scales, where the degree of spatial nonstationarity is allowed to increase with decreasing process scale."
      button:
        enable : true
        label : "Read more"
        link : "https://link.springer.com/article/10.1007/s11222-020-09962-6"

#    - title : "Deep Learning for Spatial Parameter Estimation"
#      images:
#      - "images/4_3_Sydney_training_data_mixed.png"
#      - "images/4_3_Sydney_SA1_predictions_mixed.png"
#      - "images/4_3_Sydney_SA3_predictions_probability_mixed.png"
#      content : "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Consequat tristique eget amet, tempus eu at consecttur. Leo facilisi nunc viverra tellus#. Ac laoreet sit vel consquat. consectetur adipiscing elit. Consequat tristique eget amet, tempus eu at consecttur. Leo facilisi nunc viverra tellus. Ac laoreet s#it vel consquat."
#      button:
#        enable : true
#        label : "Read more"
#        link : "projects/project4"



################### Screenshot ########################
# screenshot:
#  enable : true
#  title : "Experience the best <br> workflow with us"
#  image : "images/screenshot.svg"



##################### Call to action #####################
# call_to_action:
#  enable : true
#  title : "Want to know more?"
# #  image : "images/cta.svg"
#   content : "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Consequat tristique eget amet, tempus eu at consecttur."
#  button:
#    enable : true
#    label : "The Project"
#    link : "project"
---

## Project 1
My name is Andrew
