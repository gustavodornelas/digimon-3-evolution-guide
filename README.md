# Digimon Evolution Data

This repository contains data on Digimon evolution chains, including Champion, Ultimate, and Mega levels. Each Digimon is listed with its evolution requirements and attributes.

## Visualization

The data has been used to create a web page with a pleasant visualization of the evolution chains. The page includes images of the Digimon and their evolutions sourced from [Digimon Wiki](https://digimon.fandom.com/).

## Structure

The data is organized into three main categories:

-   **Champions:** These are the base level Digimon that can evolve into Ultimate level.
-   **Ultimates:** These are the intermediate level Digimon that can evolve into Mega level.
-   **Megas:** These are the highest level Digimon.

## Usage

The data can be used for various purposes related to Digimon, such as creating evolution charts, games, or analysis. It is provided in a JSON format for easy integration into applications.

## Example

Here is an example of the data format for a Champion level Digimon:

jsonCopy code

`{
  "nome": "Angemon",
  "requisitos": {
    "Myotismon": "lv. 20",
    "Wind": 280
  }
}` 

## Contributing

Contributions to this repository are welcome. If you have new data or corrections to existing data, please submit a pull request.
