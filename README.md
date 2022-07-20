# EventCalculus-Simulator
This simulator formalizes double auction market dynamics using calculus. We define the different market states mathematically and demonstrate the consequences of placing an order into the market. This simulator is based on the published paper: https://doi.org/10.1109/CEEC.2011.5995835
# Project Description
To understand financial markets and prevent crisis we need to analyse market
microstructure. This simulator applies market-calculus, as a new approach, to
formalise market dynamics. We define calculus to analyse market processes and
feedback loops like cascading margin calls, which exist in both FX and stock markets,
in the context of a simple double auction market model. The objective to get a better
understanding of risk scenarios, not to forecast exogenous order flow. The price
trajectory is determined by the present market state and new orders arriving in
the market. By studying the market microstructure, we can compute the impact
of orders of any size, or how big a sell order has to be to cause the market to
fall by a certain percentage. Using this formalism reduces ambiguity and enables
rigorous reasoning. An algorithm for risk assessment is proposed and implemented
in a double auction demo simulator that is based on the same calculus logic. The
demo simulator demonstrates the potentiality of the market-calculus approach in
understanding market microstructure. Real markets are more complex than the
models presented here, but this chapter is a step towards building a solid foundation
for studying market models.

# Build Distribution
When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "EventCalculusSimulator_Version2.2.jar" 

Or you can simply click the "EventCalculusSimulator_Version2.2.jar"  file
