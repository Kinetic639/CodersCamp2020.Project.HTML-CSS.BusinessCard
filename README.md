


# CodersCamp Projekt HTML & CSS — Wizytówka / Portfolio
link do projektu:
https://kinetic639.github.io/CodersCamp2020.Project.HTML-CSS.BusinessCard/
Za główny cel postawiłem sobie odwzorowanie wzoru podanego jako przykład. 
  

### W projekcie każdy z uczestników powinien zaprezentować praktyczną znajomość poniższych zagadnień związanych z HTML & CSS:   

#### [x] Box-model

Strona zawiera moduł scss o nazwie *_settings.scss* wewnątrz któego znajduje się *"reset"* styli nadający właściwości `box-sizing` wartość `border-box`

  

#### [x] Kaskadowość CSS

  

#### [x] Selektory CSS

Najciekawsze selektory są chyba w nawigacji

  

#### [x] Popularne tagi HTML

Starając się o pisanie jak najbardziej poprawnego semantycznie HTML'a w projekcie użyto popularne tagi takie jak:

  

*  `<header>` - W headerze znajduje się hero image oraz tytuł strony.

  

*  `<section>` - Elementy z tym tagiem tworzą poszczególne sekcje na stronie. Są to kolejno *"about me"*, *"skills"*,*"portfolio"*, *"contact"*

  

*  `<footer>` - Znajduje się na dole strony, zawiera :copyright:

*  `<figure>`  `<img>`  `<figcaption>` - sekcja portfolio

*  `<form>` - sekcja kontaktowa
 i inne...

  

#### [x] Jak podpinać CSSa do HTMLa

Wewnątrz tagu `<head>` znajduje się `<link rel="stylesheet" href="main.css">` łączący plik *main.css* ze stroną.

Same style napisane są przy wykorzystaniu scss, któego kompilacją do pliku *main.css* zajmuje się wtyczka *Live Sass Compiler*

  

#### [x] Zapisywanie kolorów

zmienne są tworzone przy użyciu scss

  

#### [x] Stylowanie tekstu

  

#### [x] Zewnętrzne ikony/fonty (fontawesome, google fonts)

Importowanie google fonts wewnątrz scss (moduł *_typography.scss*)

Importowanie ikon z fontawsome przy użyciu cdn

  

#### [x] Flexbox i/lub CSS Grid

Flexbox:

- sekcja skills

  

Grid:

- sekcja portfolio

  

#### [x] Position (absolute, relative)

  

#### [-] Animacje keyframes

Niestety zapomniałem dodać ten rodzaj animacji

  

#### [x] Formularz (wysłanie formularza może powodować przeładowanie strony, gdyż w kursie nie było jeszcze jego obsługi)

  

#### [ ] Responsive Web Design

- podejście mobile first

- odpowiednio napisane media queries

- nawigacja mobila vs desktopowa