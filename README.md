# DLE-notshipped

APDFL DLE (mostly C#) samples -- Derived from demos, blogs or other sources

** FormWalker.cs - Walks through AcroForm field of a PDF, describing the widget annotation properties (should work for statix XFA too). PGallot sample, updated with a bit more info on signature fields.  v15.04 and higher. Place in \Sample_Source\InformationExtraction\FormWalker

** PDFOptimizerSampleByteArray.java - sample reads/writes to a byte array and uses ByteArrayInputStream and ByteArrayOutputStream 
 * to construct the ImageInputStream/ImageOutputStream that DLE needs  v15.04 and higher. Place in \samples\PDFOptimizerSample folder.
 
 ** RepeatingFormXObject.cs - sample creates a Form object to hold boilerplate content that needs to be repeated on each page with nique content added on top for each page. For use with account statements, credit card, statement, etc. Creates from 1 to N unique pages. Place in \Sample_Source\ContentCreation\RepeatingFormXObject folder.  Uses DuckyAccountStatement.pdf as the source template
