MODIFIED VERSION OF DPP-QDC-Demo

(N.B. this version works in LIST but not in MIXED) 

Compile in a folder bin/ with

gcc -DLINUX ../src/readout_demo.c ../src/dpp_qdc.c ../src/_CAENDigitizer_DPP-QDC.c -o readout_demo -lCAENDigitizer -lCAENComm -fpermissive -w

Run with

./readout_demo N

Where N is the acquisition duration in sec.
Example of config file is in file Sample_config.txt, which MUST be in bin folder and MUST be renamed config.txt (for now, like that).




-----------------------------------------------------------------------------

                   --- CAEN SpA - Computing Division ---

                                www.caen.it

  -----------------------------------------------------------------------------

  Program: DPP-QDC-Demo


  -----------------------------------------------------------------------------


  Content
  -----------------------------------------------------------------------------

  README.txt        :  This file.

  ReleaseNotes.txt  :  Revision History and notes.

   src          :  Source files
   inc          :  Include files
   build		:  Windows Project files
   bin			:  Executable files, precompiled and custom-developed


  System Requirements
  -----------------------------------------------------------------------------
  - Windows 2000/XP/7/8 
  - GNUplot 4.2 (www.gnuplot.org)


  How to get support
  -----------------------------------------------------------------------------
  Our Software Support Group is available for questions, support and any other
  software related issue concerning CAEN products; for software support
  visit the page www.caen.it/computing/support.php or send an email to
  support.computing@caen.it


  Description:
  -----------------------------------------------------------------------------



  Syntax
  -----------------------------------------------------------------------------
  readout_demo [ConfigFile]
  Default config file is ".\bin\config.txt".


