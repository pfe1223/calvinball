# Calvinball

This project calculates the records for each MLB team when playing by Calvinball rules: any extra inning game or seven-inning game. This project is based on the [pybaseball](https://pypi.org/project/pybaseball/) library.

## Setup

I had some initial problems installing the `pybaseball` library. I tried both installation methods shown on the link above. In the end, performing the following steps got `pybaseball` up and running.

* Upgrade `pip`
* Install `cython`
* Install `cmake`
* Install `pyarrow`
* Install `pybaseball`