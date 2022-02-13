# Railway Operation Simulator Project Status

This repository is here to provide a project board for displaying the status of various ongoing and proposed simulations for Railway Oepration Simulator which can be found [here](https://github.com/orgs/Railway-Op-Sim/projects/6).

## Adding a Project
When adding a project to the board please ensure you:
* Firstly add a card to the relevant column, then make sure to convert the card to an issue under the `ProjectStatus` repository.
* Project name in the usual form of `<country-abbreviation> <name>` (e.g. `GB Crewe`).
* In the description provide a link to the GitHub repository for the project itself (e.g. [FR Paris Metro](https://github.com/Railway-Op-Sim/FR-ParisMetro))
* Tag the issue with the relevant labels (see [below](#labelling))

## Project Status
The project status columns are:
* `Proposed`: projects which are under proposal with no work yet carried out.
* `Awaiting Requirement`: "stale" projects which are missing a feature.
* `Map Under Edit`: you/a user is actively editting the map, make sure to assign yourself to the issue as well!
* `Timetable Under Edit`: you/a user is creating a timetable for the simulation, make sure to assign yourself to the issue as well!
* `Under Review`: project is in beta/open to testing (this can be before release, or after as long as a new release is planned)
* `Released`: project is complete and available for download.

## Labelling
Labels provide a way of quickly determining the state of a project from the issue side. Make sure you assign the label relevant to the column the project is in, and if the project is "Awaiting Requirement" you specify what the requirement is with the `requires x` labels.
