[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

# Avoimet kvanttisysteemit Qiskitillä
Tämä kokoelma Jupyter-notebookeja sisältää materiaalit kattavalle 54:n tunnin kurssille avoimista kvanttisysteemeistä (OQS). Se esittelee avointen kvanttisysteemien perusteet ja tärkeimmät OQS:n kirjallisuudessa käytetyt käsitteet. Lisäksi esittelemme aivan uuden idean: opetamme simuloiman monia käytännöllisiä esimerkkejä OQS-dynamiikasta Qiskitin ja IBM Q –prosessoreiden avulla. Kurssin idea on peräisin varsin tuoreesta julkaisusta ([García-Pérez, Rossi, Maniscalco, NPJ Quantum Inform. 6, 1 (2020)](https://www.nature.com/articles/s41534-019-0235-y)), jossa näytämme, että IBM Quantum Experience on monipuolinen ja vahva alusta avointen kvanttisysteemien simuloimiseen.  

Tämä kurssi on tarkoitettu maisteriopiskelijoille, joilla on taustaa kvanttimekaniikasta ja kvantti-informaatiosta, ja joille Qiskit on myös tuttu. Kurssi jakautuu luentoihin ja projekteihin. Luentomuistiinpanot tarjoavat useita esimerkkejä OQS:n tärkeistä käsitteistä esitettynä sellaisten piirien avulla, joita oletamme opiskelijan tuntevan. Luentomateriaali sisältää myös monia piirejä, joilla OQS-dynamiikkaa on mahdollista simuloida IBM Q:n todellisilla kvanttilaitteilla. Näiden piirien toimintaperiaatteet selitetään kattavasti materiaaleissa. Lisäksi luentoja täydentävät ohjatut käytännön harjoitukset, joissa opiskelijat saavat toteuttaa piirit ja analysoida niiden tuloksia. 

[Linkki sivustolle](https://qplaylearn.github.io/oqs-jupyterbook)

## Asennus
Jotta pääset käyttämään kurssin notebookeja ja voit toistaa tulokset, kopioi tämä tietovarasto (repository) laitteellesi ja luo Python 3.11.10 -ympäristö valitsemallasi tavalla (virtualenv, conda tai poetry). Esimerkiksi käyttäen poetryä: 

```shell
poetry install
```

Käyttäen pip:iä,

```shell
pip install -r requirements.txt
```

## Käyttö

Notebookit löytyvät kansiosta `content`. 

----

Kirjoittajat: Daria Anttila, Guillermo García-Pérez, Matteo Rossi, Boris Sokolov


Tämä työ on lisensoitu käyttöluvalla  [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
