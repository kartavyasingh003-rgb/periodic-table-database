# Periodic Table Database

PostgreSQL database of chemical elements with a bash script to look up elements.

## Files

- periodic_table.sql - database dump
- element.sh - look up an element by atomic number, symbol, or name

## Usage

./element.sh 1
./element.sh H
./element.sh Hydrogen

Tested: ./element.sh 1, ./element.sh H, ./element.sh Hydrogen all return the Hydrogen sentence.
