# Society for the Advancement of small Research Software Projects

# Verein zur Förderung kleiner Forschungs-Softwareprojekte


Things for the foundation and management of the Society.

**UPDATE**: considering the RSE: see Issue https://git.physik.uni-wuerzburg.de/ALF/society/-/issues/2

---

### Statute / Satzung

File: Satzung-VFkS.md, converted to pdf via:

~~~
pandoc --variable margin-left=2cm --variable margin-right=2cm --variable margin-top=2.5cm --variable margin-bottom=2.5cm --variable fontsize=11pt Satzung-VFkS.md --pdf-engine=pdflatex -o Satzung-VFkS.pdf
~~~


### Foundation

For legal clarity the society should be incorporated/eingetragene; for tax advantages it should be a charity/gemeinnützig ("the recognition of 'gemeinnützigkeit' by the Finanzamt will take 6-12 months").

* Members of the society / Vereinsmitglieder (min. 7): ALF Collaboration+
* Board / Vorstand : to be chosen at the foundation assembly; rules defined in the statute/Satzung
* Name: Society for the Advancement of small Software Projects - Verein zur Förderung kleiner Softwareprojekte (_sollte der Vereinsname geschützt werden, etwa als eine Wortmarke._)
* Donations received by the Society can be of two types:
  1. Earmarked to a specific existing project or projects, in which case the funds will be used at the discretion of the Society members linked to the project(s);
  2. Open donations to the Society itself, to be used at the discretion of the Society Board.
* For the distribution of money wi should declare them as 'Stipends'. This sounds better on CVs if people use the money for bridging funding gaps and should also be more favorable in terms of taxation.
* Also taxation-wise it is more sensible to try to obtain all funds as research funds as opposed to obtaining money for the implementation of a specific feature.

#### Goals

* To support the development of non-profit, open-source, research software.
* In particular:
   * to support the construction of scientific networks (den Aufbau von wissenschaftlichen Netzwerken zu unterstützen);
   * to allow projects to receive and use donations avoiding the bureaucratic hurdles typical of universities and other institutions (es Projekten zu ermöglichen, Spenden unter Umgehung der für Universitäten und andere Institutionen typischen bürokratischen Hürden entgegenzunehmen und zu verwenden);

### Resources

Some from Flo's issue https://git.physik.uni-wuerzburg.de/ALF/ALF/-/issues/183:

* some guide: https://www.wonder.legal/de/guide/leitfaden-zur-grundung-eines-vereins (don't use their templates, since they're not free)
* Eine aktuelle Satzung die die Gemeinnützigkeit bestanden hat: https://raw.githubusercontent.com/DE-RSE/satzung/master/de-RSE-e.V._Satzung_2019-01-07.pdf
* Another society with similar goals: https://freie-software.org/verein/

* Vereinsregister; Einsicht:  https://www.freistaat.bayern/dokumente/leistung/64774641676

* Consider a gGmbH (gemeinnützige Gesellschaft mit beschränkter Haftung - "non-profit company with limited liability")?   
  Some info: https://www.gruenderkueche.de/fachartikel/checkliste-gemeinnuetzige-gmbh-ggmbh-und-verein-im-vergleich/   
             https://www.firma.de/en/company-formation/the-ggmbh-what-is-the-german-non-profit-limited-liability-company/


#### Newer (2021) Resources

some links for a similar initiative in Dresden:   
https://fsfw-dresden.de/index.html

in 2018 they published something on it, but it seems to have come to an end...   
https://fsfw-dresden.de/2018/11/funding-foss-en.html

https://fsfw-dresden.de/2018/06/interview-sander-finanzierung-freie-software.html

https://pad.fsfw-dresden.de/p/funding-foss-35c3

https://wiki.fsfw-dresden.de/lib/exe/fetch.php/events/35c3/fund-raising_for_free_software--thinking_big.pdf

https://wiki.fsfw-dresden.de/doku.php/doku/funding-foss

Wau Holland Stiftung - https://www.wauland.de/de/  - Foundation, accepts donations, supports certain open-source projects

techCultivation [see Fiscal Sponsorship below]

> ##### Ideen
> - Marktplatz für Entwickler. -> Forschungsgruppen bräuchten für sowas 
> ein budget.(Mail von Joachim Wuttke)
> - Marktplatz speziell für RSE Entwickler, mit nähe zum Forschungsumfeld
> - Marktplatz am NFDI e.V ansiedeln, oder beim EOSC AISBL
> - https://researchsoftware.org/2020/11/03/single-entry-point-and-marketplace-for-the-RSE-community-RSE-profile-map.html
> - klassisches Bug-Bounty: https://www.bountysource.com/
> - kickstarter?
> - wissenschaftliche Dienstleistungen? (Siehe Mail von Daniela Rings)
> - Kooperationen zwischen öffentlichen Einrichtungen und Universitäten.

Prototype Fund: https://prototypefund.de/en/about-2/

https://numfocus.org/ (USA based)


#### Newer (04.2022) Resources

- Also see https://git.physik.uni-wuerzburg.de/group-assaad-proposals/alf-vs-dfg/-/blob/master/Proposal_2020/NOTES.md

##### Fiscal Sponsorship

Also called fiscal hosting, fund-holding, auspicing, etc.

Some info: 
- https://buildingblocks.simplysecure.org/fiscal-sponsorship/
- https://opencollective.com/fiscal-hosting
- https://docs.opencollective.com/help/fiscal-hosts/fiscal-hosts

[Open Collective Europe](https://opencollective.com/europe) (6% fee) is able to receive deductible funds in Belgium only.
The USA chapter of RSE is in Open Collective ([link](https://opencollective.com/usrse)) fiscally hosted by the [Open Collective Foundation](https://opencollective.com/foundation). One can also use the Open Collectives for free being their own fiscal host, as a so-called [Independent Collective](https://docs.opencollective.com/help/independent-collectives/about-independent-collectives).

[GitHub Sponsors](https://docs.github.com/en/sponsors) seems to be another way to get funds to open-source projects.

There seems to be a German fiscal sponsor in the works: The [Center for the Cultivation of Technology](https://techcultivation.org/). They have nice [docs](https://techcultivation.org/docs/index.html), but there has not been much activity over the last year.


##### Misc

Interview: [„Open Source braucht öffentliche Finanzierung“](https://netzpolitik.org/2021/interview-open-source-braucht-oeffentliche-finanzierung/)

Example of Max-Planck-G-supported code: https://epics.mpg.de/

RSE Working Group (2020) [Marketplace for the RSE Community](https://researchsoftware.org/2020/11/03/single-entry-point-and-marketplace-for-the-RSE-community-RSE-profile-map.html)

https://bountysource.com/   
https://en.wikipedia.org/wiki/Open-source_bounty   
www.kickstarter.com   
https://www.spi-inc.org/ , https://sfconservancy.org/ - USA fiscal sponsors, only for 501(c)3-compatible non-profits 

https://www.linuxfoundation.org/   
https://incubator.apache.org/

