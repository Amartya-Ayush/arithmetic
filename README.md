# Arithmetic

## Overview

Arithmetic is a Sugar learning activity that presents timed arithmetic questions and tracks scores on a shared scoreboard. The activity provides small puzzle modules (addition, subtraction, multiplication, division and related problems) and is implemented as a GTK/Sugar activity.

## Repository Contents

- `arithmetic.py`: main activity implementation (UI, question scheduling, scoring, synchronization).
- `activity/`: activity metadata (activity.info).
- `puzzles/`: individual puzzle modules; each module provides a `get_problem(self, difficulty)` function.
- `dobject/`: helper modules used by the activity (UI and synchronization helpers).
- `po/`: translation files for multiple languages.
- `setup.py`, `MANIFEST`, `NEWS`, `COPYING`, `COPYING.GPLv2`: packaging and licensing metadata.
- `screenshots/`: example images used in the repository.

## Usage

This project is a Sugar activity and runs inside the Sugar learning environment as an activity bundle.

## License

This project is distributed under the terms of the GNU General Public License (GPL), see COPYING for details. The repository contains a GPL v2 license copy.
