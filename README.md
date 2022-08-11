~~~~~~~~~~~~~~~~

//***FILE 039 is partially from Citibank in New York, and           *   FILE 039
//*           contains:                                             *   FILE 039
//*                                                                 *   FILE 039
//*           1.  An SMF program to process type 14 and 15 records  *   FILE 039
//*               using IBM DFSORT.                                 *   FILE 039
//*           2.  A modification to the IPOUPDTE program so it      *   FILE 039
//*               will run against any partitioned dataset, and     *   FILE 039
//*               it doesn't require the presence of a member       *   FILE 039
//*               nameed $$$COIBM.                                  *   FILE 039
//*           3.  A modification to the CPPUPDTE program so it      *   FILE 039
//*               will run against any partitioned dataset, and     *   FILE 039
//*               it doesn't require the presence of a member       *   FILE 039
//*               nameed $$$COIBM.                                  *   FILE 039
//*                                                                 *   FILE 039
//*       $$IPODOC member with detailed doc on how to use           *   FILE 039
//*       IPOUPDTE, if you have it.                                 *   FILE 039
//*                                                                 *   FILE 039
//*       The RCNVTCAT REXX which effectively replaces MCNVTCAT,    *   FILE 039
//*       has been copied here from CBT File 542.                   *   FILE 039
//*                                                                 *   FILE 039
//*       Fixed RCNVTCAT to correctly generate DEF ALIAS            *   FILE 039
//*       statements (per Bob Richards).                            *   FILE 039
//*                                                                 *   FILE 039
//*       email:  sbgolob@cbttape.org or sbgolob@attglobal.net      *   FILE 039
//*                                                                 *   FILE 039
~~~~~~~~~~~~~~~~

