![Sunset over the Yoshino River, Tokushima, Japan](/sunset-crop.jpg "Sunset over the Yoshino River, Tokushima, Japan")

# Christopher Bunn

Hi, there! I'm a self-taught programmer and aspiring software engineer. I have experience with a variety of technologies with a focus on web development and automation. The tech stack I'm enjoying at the moment is Django (DRF) with PostgreSQL on the backend and React with Redux Toolkit on the frontend.

I'm based in Tokushima, Japan right now, but I'm originally from Philadelphia, PA, USA. I'm open to both remote work as well as onsite work in Japan or the US. Please have a look at some of my projects below and feel free to contact me.

## Recent Projects

### [ECATS Test](https://github.com/globallabo/ecats-test)

A multiple-choice test app made to evaluate the English level of Japanese EFL/ESL students. The backend is Django (DRF) with a PostgreSQL database. The frontend is React with Redux Toolkit, RTK-Query and Material UI. Deployment is via Docker. Note that this project is still under active development and hasn't yet reached a release stage.

### [Elite curriculum generation](https://github.com/globallabo/elite)

A project to easily generate a full set of PDFs for a business English curriculum with a standard template and content pulled from Google Sheets. The goal is to allow all team members to edit the content of lessons without any knowledge of the code which produces the end result. The content is stored as text in Google Sheets (along with some static images in the project directory). The templates are made with Jinja and custom HTML/CSS. And everything is brought together using a command-line app based in Python, with Typer as a framework and Weasyprint as a means to produce PDF output.

### [All Stars curriculum generation](https://github.com/globallabo/allstars)

A project to easily generate a full set of PDFs for an elementary-level English curriculum with a set of standard templates and content pulled from Google Sheets. It is a similar, but earlier, project to the above Elite project. And so it as a similar goal to allow all team members to edit the content of lessons without any knowledge of the code which produces the end result. The content is also stored as text in Google Sheets (along with some static images in the project directory). In this case, there are multiple templates made with custom HTML/CSS to accommodate different needs for different levels of student as these worksheets emphasize writing practice. There are also templates for flashcards. And everything is brought together using a command-line app based in Python, with Typer as a framework and Weasyprint as a means to produce PDF output.

### [Eikenvocab flashcard generator](https://github.com/globallabo/eikenvocab)

Another automation project. The goal this time was to produce a set of vocabulary flashcards for students studying to take standardized English exams. Previous exams can be downloaded and scanned for English words. Then a word list is created, ranking the words by their frequency across all tests. Public translation and transliteration APIs are used to produce translations in hiragana for students. The word list is stored in Google Sheets to allow other team members to verify and adjust the word list and translations. Then the list is converted into a set of flashcards in PDF form to be printed.

### [checkr](https://github.com/cbunn81/checkr)

A command-line tool written in Python, using Typer as a framework and either CSV or SQLite as a data store. It scans files and records their cryptographic hashes, and later re-scans them and verifies the hashes to ensure data integrity. The intended use case for myself is to monitor a directory of photos for signs of bit rot. But checkr can be useful to anyone wishing to verify that files haven't changed.
