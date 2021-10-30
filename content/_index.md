---
###################### hero slider ###########################
slider:
  enable : true
  slider_item:
  # slider item loop
  - bg_image : images/banner/banner-buch.jpg
    animation_from : left
    subtitle : Architekturdokumentation
    title : Das Standardwerk
    content : Erfahrt, wie die Dokumentation der Architektur von der lästigen Pflicht <br> zu einem integralen Kommunikations- und Arbeitsmittel wird. Lernt architekturrelevante <br> Einflussfaktoren und zentrale Entscheidungen festzuhalten.
    pagination_icon : ti-book # themify icon pack : https://themify.me/themify-icons
    pagination_name : Das Buch
    button:
      enable : true
      label: Mehr dazu
      link : "buch"
      
  # slider item loop
  - bg_image : images/banner/banner-autor.jpg
    animation_from : up
    subtitle : Stefan Zörner
    title : Der Autor
    content : Stefan arbeitet als Softwarearchitekt und Berater bei embarc in Hamburg. <br>Er wirkt bei Entwurfs- und Umsetzungsfragen mit, unterstützt beim Festhalten <br> von Architektur und beleuchtet Lösungsansätze in Bewertungen.
    pagination_icon : ti-user # themify icon pack : https://themify.me/themify-icons
    pagination_name : Der Autor
    button:
      enable : true
      label: Mehr
      link : "autor"
      
  # slider item loop
  - bg_image : images/banner/banner-download.jpg
    animation_from : down
    subtitle : Materialien zum
    title : Download
    content : Hier findet Ihr Leseproben sowie Vorlagen und Werkzeuge <br>zu den im Buch vorgestellten Zutaten und Gliederungen<br> für Architekturdokumentation.
    pagination_icon : ti-download # themify icon pack : https://themify.me/themify-icons
    pagination_name : Materialien
    button:
      enable : true
      label: Mehr dazu
      link : "buch"
      
  # slider item loop
  - bg_image : images/banner/banner-beispiele.jpg
    animation_from : right
    subtitle : Ideen illustriert anhand vieler
    title : Beispiele
    content : Wie sieht das Ganze in Aktion aus? Die Zutaten angefertigt <br>und zusammengefügt für verschiedene Software-Systeme. <br>Angefertigt fürs Buch, für Workshops und Vorträge, Blogbeiträge, ... 
    pagination_icon : ti-eye # themify icon pack : https://themify.me/themify-icons
    pagination_name : Beispiele
    button:
      enable : true
      label: Mehr dazu
      link : "beispiel"

########################################## Service ####################################
feature:
  enable : true
  title: "Was es ausmacht"
  subtitle: "Features"
  section: "feature" # showing items from feature section
  # service item comes from "content/feature" folder

######################################## About #########################################
about:
  enable : false
  bg_image : "images/background/about-bg.jpg"
  title : "Who We Are?"
  content : "Excepteur sint occaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum."
  # bullet point
  bullet_point:
  - "Business Services"
  - "Audit & Assurance"
  - "IT Control Solutions"
  - "Business Services"
  - "Audit & Assurance"
  - "IT Control Solutions"
  button:
    enable : true
    label : "Explore More"
    link : "about"

##################################### Skill ##############################################
skill:
  enable : false
  subtitle : Our Skills
  title : Why Choose Us
  content: Erfahren Sie, wie die Dokumentation der Architektur von der lästigen Pflicht zu einem integralen Kommunikations- und Arbeitsmittel wird. <br><br> Lernen Sie architekturrelevante Einflussfaktoren und zentrale Entscheidungen festzuhalten. <br> Erleben Sie am Beispiel einer Schach-Engine, wie eine nachvollziehbare Architektur entsteht.
  # funfacts
  funfacts :
  - icon : ti-book # themify icon pack : https://themify.me/themify-icons
    title : Auflagen
    count : 3
    
  - icon : ti-book # themify icon pack : https://themify.me/themify-icons
    title : Kapitel
    count : 12
    
  - icon : ti-files # themify icon pack : https://themify.me/themify-icons
    title : Seiten
    count : 272

  # progressbar
  progressbar : 
  - title : Motivation
    progress : 10%
    
  - title : Solides Fundament
    progress : 35%
    
  - title : Gelebte Praxis
    progress : 45%
    
  - title : Stolpersteine
    progress : 10%
      
########################################## project ####################################
project:
  enable : true
  title: "Beispieldokumentationen"
  subtitle: "Die Buchkonzepte in Aktion "
  section: "beispiel" # showing items from project section
  # project item comes from "content/beispiel" folder

########################################### Mission ###################################
mission:
  enable : false
  subtitle : Our Goal
  title : Company Mission
  content : Lorem ipsum dolor sit amet consectetur adipisicing elit sed eiusmod tempor didunt laboris nisi ut aliquip ex ea commodo consequat.
  image : images/chart.png
  accordion:
  - title : Our Company Mission
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.
    
  - title : Our Company Vision
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.
    
  - title : Our Company Goal
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.

##################################### Promo video ####################################
promo_video:
  enable : true
  title : "Auf der Bühne"
  bg_image : "images/background/JUG_Saxony_2.jpeg"
  video_URL : "https://www.youtube.com/watch?v=4QAFlEPdcJI"
  video_title : "Video: Keynote von Stefan Zörner auf dem JUG Saxony Day"

##################################### call to action #################################
testimonial:
  enable : true
  subtitle : Stimmen
  title : Was Leute über das Buch sagen
  image : images/cover_493x691.png
  testimonial_item :
  - name : Martin Dungs
    content : Mit dem Buch 'Softwarearchitekturen dokumentieren und kommunizieren' von Stefan Zörner gibt es endlich eine praxistaugliche Anleitung zur effizienten Dokumentation von Softwarearchitekturen.
    designation : Amazon-Rezension
    
  - name : Gernot Starke
    content : Als Reviewer durfte ich ja schon vor längerer Zeit frühe Versionen testlesen. Mehr als einmal haben mir Stefans Ratschläge in konkreten Projektsituationen seitdem geholfen.
    designation : aus dem Geleitwort zur 1. Auflage
    
  - name : Thomas Allweyer
    content : Wie eine gelungene Architekturdokumentation aussehen kann, thematisiert Stefan Zörner in seinem neu erschienen Buch Softwarearchitekturen dokumentieren und kommunizieren. Dabei beschreibt er einen praktikablen Weg, der sich gerade auch für agile Projekte eignet.
    designation : Besprechung im Blog "Kurze Prozesse"

##################################### call to action #################################
call_to_action:
  enable : false
  bg_image : "images/background/cta.jpg"
  title : "Das Buch kaufen"
  button:
    enable : true
    label : "Kaufen"
    link : "contact"
      
########################################## blog ####################################
blog:
  enable : false
  title: "Company News"
  subtitle: "Latest News"
  section: "blog"
  # blog item comes from "content/blog" folder
  
################################ clints logo slider ################################
clients_logo_slider:
  enable : false
  client_logos:
  - logo: "images/client-logo/client-logo-1.png"
    link: "#"

  - logo: "images/client-logo/client-logo-2.png"
    link: "https://examplesite.com"

  - logo: "images/client-logo/client-logo-3.png"
    link: "#"

  - logo: "images/client-logo/client-logo-4.png"
    link: "https://examplesite.com"

  - logo: "images/client-logo/client-logo-5.png"
    link: "#"

  - logo: "images/client-logo/client-logo-3.png"
    link: "https://examplesite.com"

    
---