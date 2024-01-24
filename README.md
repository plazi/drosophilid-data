# drosophilid-data
Repository for cleanup, enhancement, and preparation of Drosophlid data provide by Bächli, [Taxodros](https://www.taxodros.uzh.ch/)

Taxodros is maintained with semiannual updates, the next being in January 2024. It now includes a look up of DOIs for the existing articles, as well as ca 200 new articles per year ([Bächli](https://github.com/plazi/drosophilid-data/issues/20))

the 2024 release con be found in the [Taxodros.github.io](https://taxodros.github.io/) repo

## Goal
* create a repository for all the flies referenced in taxodros, eventually to link to the taxonomic names and to convert them.
* add the zenodo deposition number and eventual created DOI to the provide bibliography
* explore how this upload can be used to add more corpora of publciations to BLR/Zenodo

## Steps
1. Set up infrastructure to proceed based on the data available [here](https://drive.google.com/drive/u/0/folders/0B_yrQwn4yBySfjBfOFZfNGdvTEhobl9YR21UazlmcWxfNnlzYUM1dFVaS0UtS1JsNTJ6WFU?resourcekey=0-Orz3w0AIiL0lMbN8jdHfPg)
      a. Drosophilid data: https://github.com/plazi/drosophilid-data
      b. Drosophilid upload (stalled a couple of years ago): https://github.com/plazi/drosophilid-upload
2. Clean bibliographic references (use open refine?)
3. Check for existing DOI
4. Check for existing uploads in Zenodo
5. Use [Lycophorn](https://github.com/plazi/lycophron) or alternative tool to upload
      a. upload as biosyslit community, create a taxodros community and add as well
6. create an updated file including the Zenodo deposit ID   
