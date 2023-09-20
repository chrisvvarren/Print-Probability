<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config
       title="Print & Probability"
       banner="https://github.com/chrisvvarren/Print-Probability/blob/main/images/banner2.png?raw=true" layout="vertical">

<!-- banner="https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/AtelierTypographie-AVonWerdt.jpg/1280px-AtelierTypographie-AVonWerdt.jpg"
       layout="vertical"> -->

<!-- banner="https://hrc.contentdm.oclc.org/digital/iiif/p15878coll17/10666/185,160,1048,454/full/0/default.jpg"
              layout="vertical"> -->

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q642635"> <!-- Areopagitica -->
<param ve-entity eid="Q72759598"> <!-- David Shribman -->
<param ve-entity eid="Q64026160"> <!-- St. Paul's Churchyard -->
<param ve-entity eid="Q190080"> <!-- Carnegie Mellon University -->
<param ve-entity eid="Q622664"> <!-- University of California, San Diego -->
<param ve-entity eid="Q22682088"> <!-- IIIF -->

Print & Probability
is an interdisciplinary, NEH- and NSF-funded project at the intersection of book history, computer vision, and machine learning that seeks to discover letterpress printers whose identities have eluded scholars for several hundred years.
<param ve-image region="1171,890,727,311" fit="cover" title="P&P Researchers at Pittsburgh Theological Seminary" url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/191115D_Pittsburgh_Theological_Research_RD-19.jpg?raw=true" attribution="Carnegie Mellon University" >
<!-- <param ve-graphic img="https://github.com/chrisvvarren/Print-Probability/blob/main/images/191115D_Pittsburgh_Theological_Research_RD-19.jpg?raw=true" attribution="Carnegie Mellon University" > -->
<!-- region="1171,890,727,311" -->

## What We Do

Our team of book historians, statisticians, computer scientists, and librarians tackles bibliographical mysteries by modeling the material conditions of early modern print shops.
<param ve-compare compare fit="cover" url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/Nhole_lordmayor_1692_title.png?raw=true">
<param ve-compare
      url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/lordmayor_nhole.png?raw=true">
<param ve-compare
             url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/leviathan-0347_chunk_014.jpg?raw=true">

Among the aspects we model are <span data-mouseover-image-zoomto="372,330,373,337">fonts and type pieces</span>, <span data-mouseover-image-zoomto="630,452,373,337">paper</span>, <span data-mouseover-image-zoomto="704,417,259,234">inking</span>, and <span data-mouseover-image-zoomto="572,370,224,202">imposition</span>.
<param ve-image label="A late 17th-century printshop as depicted by engraver Abraham Von Werdt" region="372,330,373,337"
url="https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/AtelierTypographie-AVonWerdt.jpg/1280px-AtelierTypographie-AVonWerdt.jpg" license="CC-BY-SA 3.0" attribution="Wikimedia">

## Our Team

Print & Probability is a collaboration among researchers from Carnegie Mellon University and the University of California, San Diego.  The team's led by [Taylor Berg-Kirkpatrick](https://cseweb.ucsd.edu/~tberg/) (UCSD Computer Science), [Max G'Sell](http://www.stat.cmu.edu/people/faculty/mgsell) (CMU Statistics and Machine Learning), and [Christopher Warren](https://www.cmu.edu/dietrich/history/people/courtesy/warren.html) (CMU English and History) and also includes [Matthew Lincoln](https://matthewlincoln.net/) (JSTOR Labs), [Kartik Goyal](https://www.ttic.edu/faculty/goyal/) (TTIC), [Nikolai Vogler](https://nvog.github.io/) (UCSD CS PhD Student), [Sam Lemley](https://www.library.cmu.edu/about/people/samuel-lemley) (CMU Libraries), Elizaveta Pertseva (UCSD undergrad), [Kari Thomas](https://www.cmu.edu/dietrich/history/people/graduate-students/thomas.html) (CMU History PhD Student), [D.J. Schuldt](https://www.linkedin.com/in/dj-schuldt-05045171) (Simmmons MLIS student), [Elizabeth Dietrich](https://www.cmu.edu/dietrich/english/about-us/phds/bios/elizabeth-dieterich.html) (CMU English PhD Student), [Laura DeLuca](https://www.cmu.edu/dietrich/english/about-us/phds/bios/laura-deluca.html) (CMU English PhD Student) and [Jonathan Armoza](https://jonathanarmoza.com/).
<param ve-image region="-187,-484,6345,4949" url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/DC-220329A-NEH-Grant169.jpg?raw=true">  

<!-- label="Team members Shruti Rijhwani, Pierce Williams, Max G'Sell and Christopher Warren on a research expedition to the Pittsburgh Theological Seminary" -->

## Tools

Our beta [Coloring Book Paper Analysis Tool](https://coloringbook.nfshost.com/) analyzes remote IIIF images from repositories such as the British Library, Internet Archive, the Harry Ransom Center, and the Folger Shakespeare Library.  Users can generate and study LUV or RBG color profiles for each page in a digitized book, thereby permitting fine-grained investigations of changes and continuities in paper-stocks, and sequencing of printing.
<param ve-graphic img="https://coloringbook.nfshost.com/demo_rect_select_small.gif">

The [Print & Probability Workbench](https://github.com/cmu-lib/printprob-db) we use internally is a Django-powered REST [API for powering P&P's data transformation and tagging pipeline](https://printprobdb.psc.edu/api/docs/).  To classify characters, we use [Ocular](https://github.com/tberg12/ocular), a state-of-the-art historical OCR system developed in part by team co-lead Taylor Berg-Kirkpatrick.
<param ve-graphic img="./images/workbench.gif">

## Publications

Warren, Christopher N, Samuel V Lemley, D J Schuldt, Elizabeth Dieterich, Laura S DeLuca, Max G’Sell, Taylor Berg-Kirkpatrick, Kari Thomas, Kartik Goyal, and Nikolai Vogler. “Who Rpinted Shakespeare’s Fourth Folio?” Shakespeare Quarterly 74, no. 2 (June 9, 2023): 139–46. [https://doi.org/10.1093/sq/quad021](https://hcommons.org/deposits/view/hc:57952/CONTENT/quad021-1.pdf).
<param ve-iframe src="https://hcommons.org/deposits/view/hc:57952/CONTENT/quad021-1.pdf/">

Vogler, Nikolai, Kartik Goyal, Kishore PV Reddy, Elizaveta Pertzeva, Samuel V. Lemley, Christopher N. Warren, Max G’Sell, and Taylor Berg-Kirkpatrick. “Contrastive Attention Networks for Attribution of Early Modern Print.” In Association for the Advancement of Artificial Intelligence (AAAI), 2023. [https://arxiv.org/abs/2306.07998](https://arxiv.org/abs/2306.07998)

Warren, Christopher, Pierce Williams, Shruti Rijhwani, and Max G’Sell. “Damaged Type and Areopagitica’s Clandestine Printers.” Milton Studies 62, no. 1 (Spring 2020). [https://www.jstor.org/stable/10.5325/miltonstudies.62.1.0001](https://www.jstor.org/stable/10.5325/miltonstudies.62.1.0001).
<param ve-iframe src="https://doi.org/10.1353/mlt.2020.0005">

Goyal, Kartik, Chris Dyer, Christopher Warren, Max G’Sell, and Taylor Berg-Kirkpatrick. “A Probabilistic Generative Model for Typographical Analysis of Early Modern Printing.” ArXiv:2005.01646 [Cs], May 4, 2020. [http://arxiv.org/abs/2005.01646](http://arxiv.org/abs/2005.01646).
<param ve-iframe src="https://arxiv.org/pdf/2005.01646.pdf">

Warren, Christopher N., Avery Wiscomb, Pierce Williams, Samuel V. Lemley, and Max G’Sell. “Canst Thou Draw Out Leviathan with Computational Bibliography? New Angles on Printing Thomas Hobbes’ ‘Ornaments’ Edition.” Eighteenth-Century Studies 54, no. 4 (2021): 827–59. [https://doi.org/10.1353/ecs.2021.0094](https://doi.org/10.1353/ecs.2021.0094).
<param ve-iframe src="https://doi.org/10.1353/ecs.2021.0094">

## Recent and Upcoming Presentations

* “Whig Data: Milton’s Printers in the Restoration,” International Milton Society (2023)
* “Mincing Words: Computational Bibliography as Cookery,” Renaissance Society of
America (2023)
* "The Early Modern Book of Numbers," Shakespeare Association of America (2023)
* "Contrastive Attention Networks for Attribution of Early Modern Print,” Association for the Advancement of Artificial Intelligence (AAAI) (2023)

* "Freedom and the Press before Freedom of the Press," The Grolier Club Bibliography Week Lecture (2023)
<param ve-video id="7iBuxz69rvA" title="Grolier Club Bibliography Week Lecture">

* "Shakespeare, Print Networks, and the History of Clandestine Printing,” Networks 2021
* “Computational Bibliography: Techniques and Analyses,” Association for Computers and Humanities (2021)

## In the News

David M. Shribman: _The Lessons of_ Areopagitica
<param ve-iframe src="https://www.post-gazette.com/opinion/david-shribman/2019/11/24/Carnegie-Mellon-University-John-Milton-Areopagitica-document-analysis-Christopher-Warren/stories/201911240029">

[Freedom, They Printed: AI on XSEDE-allocated system solves mystery of who printed seminal works on liberty](https://www.xsede.org/-/freedom-they-printed)
<param ve-graphic url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/xsede_freedom.png?raw=true">


[PODCAST: NLP Highlights] _Automated Analysis Of Historical Printed Documents, with **Taylor Berg-Kirkpatrick**_
<param ve-iframe src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/719460085&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true">

[CMU Projects Sleuth Secret Printers, Teach Shakespeare in VR](https://www.cmu.edu/ambassadors/july-2022/humanities-projects.html)

CMU Receives NEH Grant To Develop Bibliographic Tools
<param ve-iframe src="https://www.libraryjournal.com/story/cmu-receives-mellon-grant-to-develop-bibliographic-tools">

## Awards

RBS’s Andrew W. Mellon Society of Fellows in Critical Bibliography Awards Second Annual Essay Prize (Honorable Mention)
<param ve-iframe src="https://rarebookschool.org/rbss-andrew-w-mellon-society-of-fellows-in-critical-bibliography-awards-second-annual-essay-prize/">

## Project Alumni

[Shruti Rijhwani](https://shrutirij.github.io/), [Dan Evans](http://danieljevans.net/), [Avery Wiscomb](https://averywiscomb.net/), [Pierce Williams](http://piercew.net/), [Craig Stamm](https://www.glenville.edu/directory/craig-stamm), [Sriram Viswanathan](https://github.com/FrailWords)
<param ve-image region="523,187,1653,1381" url="https://github.com/chrisvvarren/Print-Probability/blob/main/images/191115D_Pittsburgh_Theological_Research_RD-6.jpg?raw=true">

## Project Support

Print and Probability gratefully acknowledges grants from CMU Mellon Seed Grants, the  National Science Foundation, and the National Endowment for the Humanities.
<!-- <param ve-image manifest="https://iiif.archivelab.org/iiif/ldpd_15486283_000$91/manifest.json"> -->
