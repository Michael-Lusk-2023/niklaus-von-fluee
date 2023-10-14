# [Niklaus von Flüe](README.md)

*Niklaus von Flüe* is a website which provides prospective tourists and pilgrims with introductory information and access to resources in connection with the eponymous hermit, hero, and patron saint of Switzerland.

*Niklaus von Flüe* presently comprises:
- outline biographical information about Niklaus von Flüe;
- an English translation of Niklaus von Flüe's well-known prayer;
- a gallery providing impressions of relevant cultural artefacts in the region of Sachseln, Switzerland; and
- a contact form for requesting information and resources about relevant guided tours and pilgim ways.  

In a second development stage it is planned to integrate into the website content promotion of an existing commercial guided tour operator as well as each of the organizations which administer access to relevant heritage places. In a third development stage, it is planned to make the website multilingual. In a fourth development stage, the website may be extended to support readers by further including a literature list and releted resources.

*Niklaus von Flüe* will serve tourists and pilgrims by providing a central hub for accessing essential information and practical resources. It additionally will benefit an established tour operater as well as relevant foundations, churches, and museums, in each case by informing potential customers concerning their respective services.


![Responsive Mockup](media/niklaus-von-fluee-mockup.webp)


## Features

### Existing Features

- __Navigation bar__

  - The fully responsive navigation bar provides links to the Logo, Home page, Gallery and Contact page.
  - To facilitate first-use learning, the navigation bar is implemented in the same form across all pages.
  - For larger screens -- i.e. laptops and larger, implying use of a mouse -- the navigation bar is styled to provide user-feedback in the form of underlining to indicate hover-over in relation to clickable navigation links. 
  - The navigation bar enables the user, across all devices, easily to navigate from page to page without use of the browser ‘back’ button.
  

  ![Navigation Bar](media/niklaus-von-fluee-nav.webp)


- __Landing page__

  - The landing page commences with an eye-catching detail of Niklaus von Flüh as depicted in the monument to him located in the Sachseln village square.
  - A text overlay inspires user-interest with the evocative subtitle "A Swiss Enigma" and practically assists the user by providing a specific geographical reference to "Sachseln, Obwalden".
  

![Landing Page](media/niklaus-von-fluee-landing-page.webp)


- __Biography section__

  - The biography section provides the user with a thematically organized summary of Niklaus von Flüh's life, and his unexpected emergence as fifteenth century secular and religious celebrity.
  - The user will be inspired to read further, and to consider making a touristic visit or pilgrimage to Sachseln and Flüeli-Ranft.


![Biography](media/niklaus-von-fluee-biography.webp)


- __Meditative prayer section__

  - This section speaks especially to users who are interested in pilgrimage or in pre-renaissance art.
  - It presents --
    - an English translation of Niklaus von Flüh's well-known prayer; and
    - a detail of the religious mandala devised by Niklaus von Flüe to explain his understanding of dynamics associated with an undivided godhead.


![Meditative prayer](media/niklaus-von-fluee-prayer.webp)


- __The Footer__

  - The footer section comprises links to the relevant social media sites in connection with *Niklaus von Flüe*. The links open to a new tab to allow easy navigation for the user. In addition, each link specifies the noopener relationship to protect the website from online attack.
  - The footer is valuable to the user as it encourages them to keep connected via social media in order to be updated in relation to new developments concerning *Niklaus von Flüe*.


![Footer](media/niklaus-von-fluee-footer.webp)


- __Gallery__

  - The gallery provides the user with a selection of supporting images showing key places, institutions, buildings, artworks, and monuments.
  - It serves the user by providing visual inspiration to support a decision to use the contact form to request touristic or pilgimage-related resources.


![Gallery](media/niklaus-von-fluee-gallery.webp)


- __Contact page__

  - This page allows the user to request resources from the website operator. The user is requested to specify whether he or she would like to receive resources in relation to guided tours, pilgimage, or both types of activity.
  - The user will be asked to submit his or her full name and email address.
  - The user form uses validation which permits submission of the form only when text is entered in the text inputs, the email address text input contains an "@" symbol, and the radio buttons specify a resource type.


![Contact](media/niklaus-von-fluee-contact.webp)


### Features Left to Implement

- __Promotion of partner organizations__

  - This page will allow the user directly to book guided tours offered by the website's tourism partner, in relation to which the website operator will negotiate a commission.
  - This page additionally will comprise a resources hub providing links to partner foundations, churches and museums.

- __Multilingual support__

  - As interest in pilgrimage currently is increasing in Europe and the European diaspora, it is intended to make the website more broadly accessible by providing multilingual support.
  - The first multilingual implementation will support French, German, and Italian, languages, which are the national languages of Switzerland.
  - A subsequent multilingual implementation might be made to support Portuguese, Russian, and Spanish languages, reflecting nationalities frequently traveling to Switzerland for tourism purposes.
  - A possible further multilingual implementation would be made to support Chinese, Korean, and Japanese languages in an effort to reach out to tourism visitors from East Asia, who increasingly are visiting Switzerland.

- __Literature resources__

  - In a later development stage, the website may be extended to support readers by further including a literature list and copies of scholarly publications which are relatively difficult to access.
  
## Testing

*Niklaus von Flüe* was deployed early in its development to [GitHub](https://michael-lusk-2023.github.io/niklaus-von-fluee/index.html) in order to facilitate third-party testing during and at the conclusion of the development process. Continuous feedback was received from a primary third-party tester. This feedback flowed into and informed testing by the author.

The author conducted testing throughout the development process and at the conclusion of development. In consequence of this testing activity, numerous corrections were made to the code and the content of the website. These corrections are noted up in the project's commit log.

The following website features were tested for proper functionality by accessing the deployed code using two different mobile phones, a tablet, and a large-format laptop:
- landing page;
- logo link;
- navigation bar links;
- footer links; and
- contact form input and submit elements.

All the links function correctly, as do the validation and submit functions of the contact form.

The following issues disclosed by testing remain to be addressed:
- On small mobile phone screens, too little of the hero image on landing page is displayed.
- On small mobile phone screens, the gray-colored div overlaid on the background image extends below the bottom of the background image and the footer.

### Validator testing

- HTML
  - No errors were returned when passing through the official W3C validator for any of:
    -  [Landing page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmichael-lusk-2023.github.io%2Fniklaus-von-fluee%2Findex.html);
    -  [Gallery page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmichael-lusk-2023.github.io%2Fniklaus-von-fluee%2Fgallery.html); or
    - [Contact page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmichael-lusk-2023.github.io%2Fniklaus-von-fluee%2Fcontact.html).
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmichael-lusk-2023.github.io%2Fniklaus-von-fluee%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).

### Unfixed Bugs

The website contains no unfixed bugs that are known to the author.

## Deployment

- The website is deployed to GitHub pages.
- The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab;
  - In the Setting  tab, click on Pages in the Code and Automation menu located in the left-hand panel;
  - The GitHub Pages page will load;
  - On the GitHub Pages page, select the following specifications, then click Save:
    - Source - deploy from branch;
    - Branch - Main;
    - Folder - Root; and
  - Wait a moment for the page to deploy, then click the link to the deployed page. 

The live link for the GitHub Pages deployment is <https://michael-lusk-2023.github.io/niklaus-von-fluee/index.html>.


## Credits

### Code

Each of the HTML page structure and the CSS styling used in *Niklaus von Flüe* borrow from the page structure, styling and methods found in Code Institute's [Love Running](https://code-institute-org.github.io/love-running-2.0/index.html) preview project. While code borrowed from Love Running has been rewritten and extensively adapted, the Love Running preview project and its associated Code Institute teaching materials are the key sources upon which the code used in *Niklaus von Flüe* is based.

### Content

- The text for the biography section is informed by:
  - Förderverein Niklaus von Flüe und Dorothee Wyss, Niklaus von Flüe und Dorothee Wyss - Kurzbiographien, *Bruder Klaus*, available at <https://bruderklaus.com/niklaus-von-fluee-dorothee-wyss/leben-und-wirken/kurzbiografie-2/>;
  - Wikipedia authors, Niklaus von Flüe, *Wikipedia*, available at <https://de.wikipedia.org/wiki/Niklaus_von_Fl%C3%BCe>; and
  - Wikipedia authors, Nicholas of Flüe, *Wikipedia*, available at <https://en.wikipedia.org/wiki/Nicholas_of_Fl%C3%BCe>.
- The abovementioned sources conflict with each other in significant respects. The material presented in *Niklaus von Flüe* may contain consequential errors.

- The meditative prayer section contains the author's own translation of the German original, which may be found from many sources including:
  - Förderverein Niklaus von Flüe und Dorothee Wyss, Gebet in 19 Sprachen, *Bruder Klaus*, available at <https://bruderklaus.com/niklaus-von-fluee-dorothee-wyss/gebete/bruder-klaus-gebet-in-15-sprachen/>.

- The icons in the biography section, the footer, and the contact page are icons available without charge from [Font Awesome](https://fontawesome.com/).

### Media

The media used in *Niklaus von Flüe* comprises copyright material owned by the organizations with whom the website operator proposes to cooperate. It is a feature of the website that users will reencounter the material when they later visit the websites of the respective project partners. It is expected that each proposed project partner will grant on reasonable terms a license to use the copyright material.   

- The main photo used on the landing page is from an online article published by the Swiss Federal Department of Foreign Affairs:
  - [hero-image](https://houseofswitzerland.org/sites/default/files/styles/cover_huge/public/story/cover/Untitled%20design%20%284%29_1.png?h=10d202d3&itok=_Zy0m4ov) - available at <https://houseofswitzerland.org/swissstories/history/st-nicholas-flue-genuine-swiss-legend>.

- Other photos used on the home page are from Förderverein Niklaus von Flüe und Dorothee Wyss:
  - [biography-image](https://bruderklaus.com/wp-content/uploads/2021/03/Medaillon_Spichtig_Bild-bearbeitet.jpg) - available at <https://bruderklaus.com/orte-informationen/sachseln/pfarrkirche/>; and
  - [prayer-image](https://bruderklaus.com/wp-content/uploads/2021/03/DSC_0010_geschn-1600x400.jpg) - available at <https://bruderklaus.com/niklaus-von-fluee-dorothee-wyss/leben-und-wirken/meditationsbild-2/>.

- The photo used on the contact page is from Museum Bruder Klaus:
  - [contact-image](https://static.wixstatic.com/media/6cf4d4_a34e6ccb905344edb3c3e3ec1ff1e54d~mv2.jpeg/v1/fill/w_1903,h_500,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/6cf4d4_a34e6ccb905344edb3c3e3ec1ff1e54d~mv2.jpeg) - available at <https://www.museumbruderklaus.ch/raus-aus-dem-haus>

- The photos appearing in the gallery page are taken from the following sources:

  - Swiss Federal Department of Foreign Affairs:
    - [birth-house](https://houseofswitzerland.org/sites/default/files/inline-images/brother_klaus_residence_saxeln_sachseln-848780.jpg%21d.jpg) - available at <https://houseofswitzerland.org/swissstories/history/st-nicholas-flue-genuine-swiss-legend>;
    - [museum](https://houseofswitzerland.org/sites/default/files/inline-images/2014-Sachseln-Museum-Bruder-Klaus.jpg) - available at <https://houseofswitzerland.org/swissstories/history/st-nicholas-flue-genuine-swiss-legend>; and
    - [niklaus-statue](https://houseofswitzerland.org/sites/default/files/inline-images/2016-Boncourt-Saint-Nicolas-de-Flue.jpg) - available at <https://houseofswitzerland.org/swissstories/history/st-nicholas-flue-genuine-swiss-legend>.

  - Förderverein Niklaus von Flüe und  Dorothee Wyss:
    - [dorothee-statue](https://bruderklaus.com/wp-content/uploads/2021/03/Sachseln-Monument-de-Dorothee-03-680x1024.jpg) - available at <https://bruderklaus.com/orte-informationen/sachseln/flueeli-kapelle/>;
    - [meditation-painting](https://bruderklaus.com/wp-content/uploads/2021/03/Meditationsbild-%C2%A9-Bruder-Klaus-Sachseln-958x1024.jpg) - available at <https://bruderklaus.com/orte-informationen/sachseln/pfarrkirche/>;
    - [flueeli-chapel](https://bruderklaus.com/wp-content/uploads/2021/03/6073_Flueeli_Kapelle-Karl-Borromaeus_geschn-1-1024x822.jpg) - available at <https://bruderklaus.com/orte-informationen/sachseln/pilgergottesdienste/>; and
    - [grave-altar](https://bruderklaus.com/wp-content/uploads/2021/03/Sachseln_Pfarrkirche-Grabaltar000081-%C2%A9-Bruder-Klaus-Sachseln-1024x805.jpg) - available at <https://bruderklaus.com/orte-informationen/sachseln/pfarrkirche/>.
  
  - Erwin Tours of Switzerland:
    - [family-house](https://erwintours.ch/wp-content/uploads/2022/02/Saint-Niklaus-of-Flue-Tour-in-Switzerland-by-Erwin-Tours-of-Switzerland-Porsonally-Guided-Private-Tours-Switzerland-Photo-%C2%A9-Erwin-Faessler-Photography-400x300.jpg) - available at <https://erwintours.ch/tour-categories/culture-and-tradition-tours/saint-niklaus-of-flue-tour/#>;
    - [flueeli-gorge](https://erwintours.ch/wp-content/uploads/2022/02/Saint-Niklaus-of-Flue-Tour-in-Switzerland-by-Erwin-Tours-of-Switzerland-Porsonally-Guided-Private-Tour-Switzerland-Photo-%C2%A9-Erwin-Faessler-Photography-400x300.jpg) - available at <https://erwintours.ch/tour-categories/culture-and-tradition-tours/saint-niklaus-of-flue-tour/#>; and
    - [hermitage-chapel](https://erwintours.ch/wp-content/uploads/2022/02/Saint-Niklaus-of-Flue-Tour-in-Switzerland-by-Erwin-Tours-of-Switzerland-Tailor-made-Private-Tours-Switzerland-Photo-%C2%A9-Erwin-Faessler-Photography-400x300.jpg) - available at <https://erwintours.ch/tour-categories/culture-and-tradition-tours/saint-niklaus-of-flue-tour/#>.
