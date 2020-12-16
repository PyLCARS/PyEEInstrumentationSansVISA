# PyEEInstrumentationSansVISA

# Please instead use [SocketSCPI](https://socketscpi.readthedocs.io/en/latest/) by Morgan Allison. It’s a much more developed Socket SCPI python interconnection library than this repo


#Disclaimer: The code presented here is for education purpose only and has not been fully tested on the instruments. Therefore you use this code at your own risk!

Collection of notebooks demonstrating EE instrument control and reading using rs-232 and LXI without VISA

The Jupyter Notebooks in this repo show how to use Python with the `serial` and `socket` libraries to control and record readings of some electrical equipment without the use of any VISA based system such as `PyVISA` `LabView` or 'Keysight' like Programs.
Some of the notebooks have full programs with automatic running of the instruments with live plotting via multithreading. While other notebooks show just testing of communicating with the instruments that can be used to develop full programs.

# Instruments so far in this repo:
+ HP (Agilent) 34401A Multimeter [Full Program] (RS-232)
+ IonTech GFC-1000 3 Channel Mass Flow controller [Full Program] (RS-232)
+ Supplementary Program to scrape the correction factors from MKS 
+ Rigol ds1054z Oscilloscope [Testing] (LXI)
+ Sorensen XG DC Power Supply [Testing] (LXI)


