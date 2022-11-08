# Tautobase

This repository contains relevant project files of the public tautomer
database "Tautobase", an optional plugin for
[DataWarrior](http://openmolecules.org/datawarrior/index.html).  It was
presented in the publication "Tautobase: An Open Tautomer Database",
Wahl, O. and Sander T. _J. Chem. Inf. Model._ 2020, 60, 1085-1089;
[doi 10.1021/acs.jcim.0c00035](https://doi.org/10.1021/acs.jcim.0c00035).
Since release February 2020, the installation of DataWarrior (release 2.5.1)
includes this data base as one of its reference files.

The principle source of information digitized in Tautobase is the
tautomer codex authored by P.W. Kenny and P.J. Taylor, “The Prediction of
Tautomer Preference in Aqueous Solution”
(<https://doi.org/10.6084/m9.figshare.8966276.v1>).

Each tautomer pair in the database has matching atom positions. The first
version of the database contains 1680 unique tautomer pairs and available
both as a DataWarrior file (`.dwar`) and a text file containing SMIRKS
transformations along with the non-structural information.

The list of references, mentioned in the column "Reference" in the `.dwar`
file equally is provided by this repository.

Tautobase (`.dwar` file and SMIRKS transformations) can be downloaded
separately from DataWarrior at
<https://github.com/WahlOya/Tautobase.git>

Please add the reference mentioned above if you use Tautobase in your
study.

For questions/comments, please contact the corresponding author of the
article.
