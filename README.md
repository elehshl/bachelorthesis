# How to "Bachelor thesis"

## Thesis (written part)

### Let's get started
1. Download the repository as a zip.
2. Extract the zip.
3. Open the thesis_template.zip file in a latex editor. (How to make Latex ready for use can be found [here](https://www.wwu.edu/faculty/curgus/Courses/LaTeX/Getting_Started_with_LaTeX.html). Our recommendation: use the web-based [Overleaf](https://www.overleaf.com/latex/templates/bachelorthesis-hshl/bydmpbhxfqgq)).
4. Choose main.tex as the main document, which means compile main.tex. Choose TeX Live version <= 2023. The following pdf should open:
![image](https://user-images.githubusercontent.com/43642275/231692705-7359fac9-0975-472b-873a-22be89630f31.png)
5. Document structure
   ```
   chapters/
    ├── 01Introduction.tex
    ├── 02Fundamentals.tex
    ├── 03RelatedWork.tex
    ├── 04Analysis.tex
    ├── 05DesignImplementation.tex
    ├── 06Evaluation.tex
    ├── 07SummaryOutlook.tex
    └── 08Appendix.tex
   images/
    └── HSHL_Logo_horizontal_RGB_blue_green_mit-Schutzraum_ENG.jpg
    cover.tex
    main.tex
    preamble.tex
    References.bib
    ```
   - **Chapters:** This folder includes the chapters of the document. You can write your text in the sub files.
   - **Images:** This folder includes the images.
     
      You can use them in the text like this:
       ```
       \begin{center}
	     \includegraphics[scale=0.12]{images/image_name.jpg}
       \end{center}
       ```
   - **Cover:** This is the cover page.
     - Line 53: Add your matricle number.
     - Line 54: Add your e-mail address. 
   - **Main:** This file connects all the chapters.

     You can also change the cover page here.
     - Line 4: Add the name of the thesis.
     - Line 8: Add your name.
     - Line 9: Change to "Project Work" if necessary.
     - Line 13 - 14: Add the names of the first and second supervisors.
     - Don't forget to write your name in line 75 inside the Affidavit.
    - **Preamble:** This file includes all the needed packages. If you want to add some, do it in this file.
    - **References:** This is the bibliography of your thesis.
      - Often you can already download a citation in bib format.
      - It is recommended to use a literature management program like [Zotero](https://www.zotero.org/).

### Make Changes in the Document
- **List of Abbreviations:** If you need a list of abbreviations, you can use it in main.tex from lines 38-43. If you don't need it, you can delete it or comment it out.
In the list of abbreviations, only those abbreviations are shown which are used in the text. Use in the text looks like this: ```~\ac{abbreviation}```
- **Add or delete chapters:** In the main.tex you will find from lines 47-54 the inclusion of the chapters. There you can add or delete chapters. If you want to add a chapter here, you should also create a new .tex file in the "Chapters" folder and refer to it in main.tex.

### Infos
- **Numbers:** In general, English numbers are only written out in full when they introduce a sentence or when small quantities are involved in a text, i.e. one (1) to nine (9). From ten (10) onwards, numbers are usually written numerically (i.e. as a number).
- **Citation:** to add space automatically but don't write the source in the next line just use ``` ~\cite{citation} ```
- **Number of pages**:
	- Projectwork: min 35
 	- Bachelorthesis: min 50

### Extras
- [Grammarly](https://app.grammarly.com/)

## Presentation
- If you are writing your thesis only at the University, please use the provided template PowerPoint_Template.potx. If you are writing your thesis in cooperation with a company, feel free to use the template of the company.
- Keep in mind that always start the presentation with a motivation!

## Good luck! 🍀
