This example demonstrates a potential error when using the REDEFINES clause in COBOL. The program defines two areas, WS-AREA-1 and WS-AREA-2, where WS-AREA-2 redefines WS-AREA-1.  If the programmer isn't careful about data alignment and lengths, incorrect data manipulation may occur.  The solution shows how to avoid these pitfalls and illustrates correct use of REDEFINES.