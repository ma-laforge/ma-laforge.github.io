---
layout: default
title: "Modelling Tools"
#__altstars: "&#x2B50;&#x1F31F;&#x2728;" #Alternarnative unicode "stars"
#__altthumbsup: "&#x1F44D;" #Alternarnative unicode "thumbs up"
#__altthinking: "&#x1F914;&#x1F9D0;" #Alternarnative unicode "thinking"
permalink: /extresouces/modelling
---

{% include favicon.html %}

<!-- Reference-style links to make tables & lists more readable -->


# Math, Modelling, Simulation, Plotting

This page provides a list to promissing extrnal resources that address various problems in math, modelling, simulation, and plotting.

## Basic info
 - &#x2728;: Recommended by MA
 - &#x1F914;: Looks promising to MA
 - [Mathematical Software (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/Mathematical_software): Explains different types.

## Modelling languages
 - [Modelica (modelling language) &#x21AA;](https://www.modelica.org/): &#x1F914; Has multiple implementations.
   - Implementations (see below): OpenModelica, AMESim, CATIA Systems, Dymola, JModelica.org, MapleSim, Wolfram SystemModeler, Scicos, SimulationX, Vertex, Xcos.
 - Verilog A/AMS (Implemented in circuit simulators)

## Computer Algebra Systems (CAS)
 - [Computer algebra system (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/Computer_algebra_system)
 - [Scilab &#x21AA;](https://www.scilab.org/): Similar to Matlab.
 - [SymPy (Python) &#x21AA;](https://www.sympy.org/): Symbolic
   - [SymPy.jl (Julia) &#x21AA;](https://github.com/JuliaPy/SymPy.jl): Symbolic. Wrapper for Python library.
 - [Maxima &#x21AA;](http://maxima.sourceforge.net/): Symbolic.
   - [Maxima.jl (Julia) &#x21AA;](https://github.com/nsmith5/Maxima.jl): Symbolic. Wrapper using Maxima software.
   - See also: wxMaxima, xmaxima
 - [Axiom &#x21AA;](http://www.axiom-developer.org/): Symbolic.
   - See also: OpenAxiom, FriCAS
 - [Octave &#x21AA;](http://www.gnu.org/software/octave/): Similar to Matlab. MA: Not recommended; use Julia if possible.
   - See also: xoctave, QtOctave
 - [GeoGebra (Web+app) &#x21AA;](https://www.geogebra.org/): Interactive geometry/algebra/statistics/calculus.
   - Teach/learn math/science elementary &rArr; university.

## Other math systems
 - [Enthought Tool Suite, ETS (Python) &#x21AA;](https://docs.enthought.com/ets/): Components to construct scientific applications.
   - Mayavi (3D viz), Chaco (Interactive 2D plots), SciMath (Scientific utilities including units), ...
 - [SageMath &#x21AA;](https://www.sagemath.org/): Builds on top of many existing open-source packages: NumPy, SciPy, matplotlib, Sympy, Maxima, GAP, FLINT, R and many more.
 - [SciPy (Python) &#x21AA;](https://www.scipy.org/): Similar to Matlab.
   - Add-on package listing: <http://scikits.appspot.com/scikits>
   - Add-on examples: scikit-learn, scikit-rf, scikit-image.
 - [Qwt (C++/Qt) &#x21AA;](https://qwt.sourceforge.io/): Qt Widgets for Technical Applications.
 - [ROOT (CERN) &#x21AA;](https://root.cern/): Data analysis framework
   - Source: CERN (European Organization for Nuclear Research, orig: Conseil Européen pour la Recherche Nucléaire).

## Numerical-analysis software
 - [List of numerical-analysis software (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/List_of_numerical-analysis_software)
 - [Comparison of numerical-analysis software (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/Comparison_of_numerical-analysis_software)
 - [Julia (Programming Language) &#x21AA;](https://julialang.org/): &#x2728;&#x2728; Designed with numerical-analysis in mind.
 - [Scilab &#x21AA;](https://www.scilab.org/): Similar to Matlab.

<a name="DynamicSim"></a>
## Dynamic simulation systems (modelling/numerical solvers)
 - [Dynamic simulation (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/Dynamic_simulation)
 - [Modia (Julia) &#x21AA;](https://github.com/ModiaSim/Modia.jl): &#x1F914;&#x1F914; Implementation trying to *improve/extend* Modelica language.
 - [Open Modelica &#x21AA;](https://openmodelica.org/): Open Source Modelica Consortium (OSMC).
 - [Xcos (Scilab) &#x21AA;](https://www.scilab.org/software/xcos): Based on Modelica language.
 - [Simulink (Mathworks) &#x21AA;](https://www.mathworks.com/products/simulink.html)
 - [MapleSim (Maplesoft) &#x21AA;](https://www.maplesoft.com/products/maplesim/index.aspx): Based on Modelica language.
 - [SystemModeler (Wolfram) &#x21AA;](https://www.wolfram.com/system-modeler/): Based on Modelica language.
 - [DAETools &#x21AA;](http://daetools.sourceforge.net/html/index.html): Open source.

## Calculators/plotting libraries
 - [matplotlib (Python) &#x21AA;](http://matplotlib.sourceforge.net/)
 - [Grace/xmgrace &#x21AA;](http://matplotlib.sourceforge.net/): Outdated interface, but good .eps output.
 - [Desmos (web+app) &#x21AA;](https://www.desmos.com/)
 - [GeoGebra (web+app) &#x21AA;](https://www.geogebra.org/graphing)
 - [KmPlot (KDE) &#x21AA;](http://edu.kde.org/kmplot/): Mathematical function plotter.
 - [QtiPlot (Qt) &#x21AA;](https://www.qtiplot.com/)
 - [SciDAVis (Qt) &#x21AA;](http://scidavis.sourceforge.net/): Fork of QtiPlot.
 - [LabPlot (KDE) &#x21AA;](https://labplot.kde.org/)
 - [MagicPlot &#x21AA;](https://magicplot.com/)

## IDEs/front ends
 - [Cantor (KDE) &#x21AA;](http://www.kde.org/applications/education/cantor/): Matlab-like IDE.
   - Supports: Julia, KAlgebra, Lua, Maxima, Octave, Python 2 and 3, Qalculate, R, Sage, and Scilab.
   - Part of [KDE Education Project &#x21AA;](https://edu.kde.org/)

## Instrument control
 - [NIDAQ.jl (Julia) &#x21AA;](https://github.com/JaneliaSciComp/NIDAQ.jl): National Instruments Data Acquisition Interface
   - Source: Howard Hughes Medical Institute
 - [Instruments.jl (Julia) &#x21AA;](https://github.com/BBN-Q/Instruments.jl): (VISA) Instrument control in Julia
   - Source: Raytheon BBN Technologies - Quantum Group
 - [PyVISA (Python) &#x21AA;](https://pyvisa.readthedocs.io/en/latest/): Control your instruments with Python

## Numerical libraries
 - [List of numerical libraries (Wikipedia) &#x21AA;](https://en.wikipedia.org/wiki/List_of_numerical_libraries)
 - [GNU Scientific Library (GSL) &#x21AA;](http://www.gnu.org/software/gsl/): Numeric Library for C/C++.
 - Boost, BLAS, LAPAK, Intel MKL, ...

## Information sites
 - [Wolfram|Alpha &#x21AA;](https://www.wolframalpha.com/)
 - [Math Open Reference &#x21AA;](https://www.mathopenref.com/)
 - [NIST Digital Library of Mathematical Functions &#x21AA;](https://dlmf.nist.gov/)
 - [NIST Reference on Constants, Units, and Uncertainty &#x21AA;](https://physics.nist.gov/cuu/Constants/index.html)

