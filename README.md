# SD2BBN Tool for Automatic Mapping of UML Sequence Diagrams to BBN Reliability Model #

## Intro ##

The SD2BBN Tool maps interactions, components (in lifelines), and failure dependencies between them to a reliability network in a Bayesian Belief Network.

The failure dependencies between certain sequences of interactions, especially in combined fragments with operators, are indeterministic due to the limited syntax of UML, and require inspection and possible.

SD2BBN is written in Javascript.

The most important libraries used are [jsbayes.js](https://github.com/vangj/jsbayes) and [jsbayes-viz.js](https://github.com/vangj/jsbayes-viz], made by (Jee Vang)[https://github.com/vangj].

Other libraries include:

[d3.js](https://github.com/d3/d3)

[lodash.js](https://github.com/lodash/lodash)

[graphlib.js](https://github.com/cpettitt/graphlib)

[dagre.js](https://github.com/cpettitt/dagre)

[jquery.min.js](https://github.com/jquery/jquery)


## Input ##

UML Sequence diagram source files in XML. Currently Enterprise Architect source files are supported.

## Output ##

Visual and textual representation of resulting Bayesian Belief Network.

## Requirements ##

Javascript

## License ##

The SD2BBN tool is licensed under the [GNU General Public License Version 2, June 1991](http://www.gnu.org/licenses/gpl-2.0.txt) (license document is in the application subfolder).
License remains the same under adaptations.

The libraries have individual licenses which can be found in their source files. No adaptations were made to the included libraries.

## Installation ##


## Installation procedure ##


## Usage ##


## references ##


