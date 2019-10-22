# Programming with Data: Python and Pandas LiveLessons

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dgerlanc/programming-with-data-livelessons/master?urlpath=lab)

This repository contains the accompanying slides for [Programming
with Data: Python and Pandas: LiveLessons](https://learning.oreilly.com/videos/programming-with-data/9780136623755). 

## Installation

### Binder

If you have a stable Internet connection and the free Binder service isn't under
too much load, the easiest way to interactively run the slides and try the
exercises is to click the Binder badge (make sure you open in a new window).
Keep in mind that Binder aggresively shuts down idle instances so you'll need to
refresh the link if you're idle for too long.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dgerlanc/programming-with-data-livelessons/master?urlpath=lab)

### Local Installation

For offline usage, I recommend downloading and installing the Anaconda Python 3
distribution and `conda` package manager.

```
https://www.anaconda.com/download/
```

Download the latest version of the course materials
[here](https://github.com/dgerlanc/programming-with-data-livelessons/archive/master.zip).

Alternatively, you may clone the course repository using `git`:

```
$ git clone https://github.com/dgerlanc/programming-with-data-livelessons.git
```

The remainder of the installation requires that you use the command line.

To complete the course exercises, you must use `conda` to install the
dependencies specified in the `environment.yml` file in the repository:

```
$ conda env create -f environment.yml
```

This will create an `conda` environment called `pwdlive` which may be
"activated" with the following commands:

* Windows: `activate pwdlive`
* Linux and Mac: `conda activate pwdlive`

Once you've activated the environment your prompt will probably
look something like this:

```
(pwdlive) $
```

The entire course is designed to use `jupyter` notebooks. Start the
notebook server to get started:

```
(pwdlive) $ jupyter lab
```

## Feedback

Your feedback on the course helps to improve it for future students.
Please leave feedback [here](https://danielgerlanc.typeform.com/to/RyB6AJ).



