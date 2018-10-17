
# Group project 1

The project involves the construction of the website according to specifications.

Given are  [examples](utlit/) in `500px`, `800px` and `1500px` with the grid along with `1500px` without the grid and an overview of the website's functionality `utlit/video.mp4`.

## Pages

Data for the pages in the appropriate text file (e.g. forsida.txt) under `efni/`. Images for pages are stored under `img/`. All the data between pages must be copied, this is not a requirement to set up a commonly owned header/footer inthe pages with some kind of system or programming.

Page material should not be wider than `1200px`. Colors in header and footer shall fill up all of the horizontal space.

All pages have the same header and footer. Item groups in the footer should all refer to `pages/products.html`.

Base font size is 16px and all the other fonts come with: `12 14 16 18 21 24 36 48 60` scaling.

Color palette for the website `#000000`, `#ffffff`, `#afb281`, `#cee8ff`, `#fcffd2` og `#cc9694`.

Font type for the main text is Open Sans or helvetica, arial or sans-serif letur.
Font type for headings is Oswald, Verdana or serif type.

Most of everything is set up in 12 columns grid with `20px` gutter.

All the intervals are half, whole, double or triple of the gutter. It is possible to use a ruler (e.g. http://www.arulerforwindows.com/ or http://www.pascal.com/software/freeruler/) to find the exact dimensions, but most importantly that the similar solution exists, but not exactly like on the example.

All animations happening for `300ms` with `ease-in-out` hröðunarfalli.

Nothing needs to be done with buttons and shapes.

## Group work

The project needs to be development in the group with three other students. Be in touch with the teacher, if not possible to work in the group.

Both Git and GitHub need to be used. No zip-files should to be going around in the group work, rather need to „commit“ all code and work through Git.

## Project description

`README.md` file should be in the root of the project and include:

* Information about how to run the project
* Description on project set up, how it is arranged in folders, how CSS is organised etc.
* Information about everyone who worked on the project
* It is allowed to keep this project description, but it should come  _after_ your description

## Devices and tools

Sass and stylelint should be set up for the project. Given `styles.scss` file with basic information.

Given `.stylelintrc` file which says how lint for `scss` file should relate.

In `.gitignore` is `styles.css` ignored which means that it is _not_ checked in. It is done so, because it is made by sass from `styles.scss`

## Given files

The following is set up in the project:

* `.stylelintrc` with the information on how stylelint has to behave. `stylelint-config-primer` package needs to be set up.
* `.gitignore` which ignores common files, [see more](https://help.github.com/ignore-files/)
* `.gitattributes` which prevents inconsistencies that may occur when operating between different operating systems
* `.editorconfig` which coordinates the use of tabs and spaces, indents  [and more](https://editorconfig.org/)
* `index.html` with reference to `styles.css` and `grid.css` along with empty files for `products.html`, `about.html` and `cart.html` under `pages/`, should keep such structure
* `grid.css` to see the grid on which an example is worked on

`package.json` need to be set up and appropriate packages need to be downloaded to enable the devices and tools that the project needs to use in order for it to work.

## Grade assessment break-down

* 10% - `README` eftir forskrift, tæki og tól uppsett
* 20% – Snyrtilegt, gilt (skv. stylelint) CSS/Sass, gilt og aðgengilegt HTML
* 30% – Almennt útlit
* 10% – Forsíða
* 10% – Vörulista síða
* 10% – Um síða
* 10% – Kaupa síða

## Introduced

Verkefni sett fyrir í fyrirlestri mánudaginn 8. október 2018.

## Submission

Einn aðili úr hóp skal skila fyrir hönd allra og skila skal undir „Verkefni og hlutaprófa“ á Uglu í seinasta lagi fyrir lok dags föstudaginn 26. október 2018.

Skil skulu innihalda:

* Nöfn allra í hóp ásamt notendanafni
* Slóð á GitHub repo fyrir verkefni, og dæmatímakennurum skal hafa verið boðið í repo ([sjá leiðbeiningar](https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/)). Notendanöfn þeirra eru `arnar44`, `gorri4`, `mimiqkz`, `hinriksnaer`, `gunkol`, `freyrdanielsson` og `osk`
* Slóð á verkefnið keyrandi á vefnum

## Grading

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 3,5% hvert, samtals 28% af lokaeinkunn.

Sett verða fyrir tvö stærri verkefni þar sem hvort um sig gildir 11%, samtals 22% af lokaeinkunn.

## Images

Images from:

* [Innkaupakörfu íkon eftir Stephen Hutchings á www.flaticon.com](https://www.flaticon.com/authors/stephen-hutchings)
* Unsplash
  - https://unsplash.com/photos/MohB4LCIPyM
  - https://unsplash.com/photos/tpLz5aKdQmM
  - https://unsplash.com/photos/_T4w3JDm6ug
  - https://unsplash.com/photos/cOJgO4Zzs-w
  - https://unsplash.com/photos/PDX_a_82obo
  - https://unsplash.com/photos/ArGvQkA7iOw
  - https://unsplash.com/photos/5ExRBlHu1DA
  - https://unsplash.com/photos/b9dS7hpi67w
  - https://unsplash.com/photos/asBwpysXVB4
  - https://unsplash.com/photos/-s6XYBp1WTc
  - https://unsplash.com/photos/wKOKidNT14w

---

> Útgáfa 0.1
