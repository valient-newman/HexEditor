  Simple corrections brought in THexEditor, THexToCanvas by Valient Newman to make the component meet
  the requirements of Delphi 6 and higher, when the design-time and runtime code must be separated.

  Checked in Delphi 7 and Delphi 2007  
  
  This component is used in Activity and Authentication Analyzer
  https://aaanalyzer.blogspot.com/
  
  Valient Newman <valient.newman@proton.me>
  My Github Repository <https://github.com/valient-newman>

  THexEditor v1.16,
  THexToCanvas v1.0 Beta 2

  THexEditor descends from TCustomGrid, and displays and edits hexadecimal/binary files
  THexToCanvas is a descendant of TComponent, assign a THexEditor to it, set some properties
  and you can paint the hex data to a canvas ( e.g. printer canvas )

  credits to :

  John Hamm, john@snapjax.com, http://users.snapjax.com/john/ (s.b. for details)

  Christophe LE CORFEC , CLC@khalif.com for his introduction to the EBCDIC format and
                         the nice idea about half byte insert/delete

  Philippe Chessa , Philippe_Chessa@compuserve.com for his suggestions about AsText, AsHex
                    and better support for the french keyboard layout

  Daniel Jensen , no_comply@usa.net for octal offset display and the INS-key recognition stuff

  written by Markus Stephany, mirbir.st@t-online.de, http://home.t-online.de/home/mirbir.st