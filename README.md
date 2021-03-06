# SumoVizUnity

This repository includes the full source-code of the Unity3D project developed during my master thesis. More information on the thesis can be found on [my blog](http://buechele.cc/blog/2014/8/6/master-thesis-post-visualization-of-pedestrian-simulation-data-using-a-game-engine).

The Unity project was tested and developed for use on Mac OS and Windows. Ready-to-run executables, including some demonstration-data can be downloaded from the releases-section.

## Features
The software takes simulation-data (in this implementation from a text-file) and geometry-data and creates a 3D visualization in real-time. Moreover, it offers tools to analyze trajectories, density, population and speed, create measuring lines and drawing fundamental diagrams.

![Screenshot](https://raw.githubusercontent.com/danielbuechele/SumoVizUnity/master/Screenshot.png)

## License
The software is licensed under the [MIT license](http://opensource.org/licenses/MIT). If this software is used anywhere, I would be more than curios to know and will be happy to help with any problems!

## Thesis

My thesis "Post-visualization of pedestrian simulation data using a game-engine" was written in 2014 at Technische Universität München. The full PDF-file can be downloaded [here](http://buechele.cc/s/thesis.pdf) (German). And includes the following chapters:

1. Einführung
  1. Vorhersage von menschlichem Verhalten
  2. Fußgängerforschung als interdisziplinäres Forschungsfeld
  3. Motivation und Ziele der Arbeit
2. Fußgängersimulation
  1. Modellierungsebenen bei der Fußgängersimulation
  2. Modellierungsmethoden zur Fußgängersimulation
  3. Aufzeichnung realer Daten
  4. ParameterundMessgrößenfürSimulationen
  5. Bestehende Systeme zur Post-Visualiserung
3. Implementierung einer Post-Visualisierung für Fußgängersimulationsdaten
  1. Neuimplementierung von SumoViz3D
  2. Nutzung von Game-Engines für wissenschaftliche Visualisierungen
  3. VerwandteArbeiten
4. Implementierung der Visualisierung auf Basis einer Game-Engine
  1. ImportderSimulationsergebnisse
  2. DarstellungderGeometrie
  3. SteuerungdesVisualisierung
  4. DarstellungderFußgänger
  5. Implementierung der Analysewerkzeuge
5. Ausblick und Fazit
  1. Vergleich zur Bachelorarbeit
  2. Möglichkeiten der Weiterentwicklung
  3. Fazit

## SumoViz3D
This work builds upon my Bachelor's thesis on WebGL-based post-visualization, which can be found [here](https://github.com/danielbuechele/SumoViz3D).
