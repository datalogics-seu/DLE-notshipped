# DLE-notshipped

APDFL DLE (mostly C#) samples -- Derived from demos, blogs or other sources

** AddTextToDocument-WithTimer.cs - Tests performance/speed of the OCRParams Performance options (Default vs. Faster vs. MoreAccuracy vs. BestAccuracy).  Unscientific test showed that the Faster option took 25%-50% of the elapsed time of BestAccuracy. v15.0.4 and higher. Place in \Sample_Source\OpticalCharacterRecognition\AddTextToDocumentWithTimer

** CheckForMissingAppearanceStreams.cs - Examine any Widget annotations (not all annots) for fields that have a missing appearance and also have a value.  v15.0.4 and higher. Place in \Sample_Source\Annotations\

** ConvertTextToOutlines.cs - "Tricks" APDFL into converting all text to outlines by adding a small translucent element to each page and then calling the flattener with the "UseTextOutlines" option (equivalent to the Acrobat -> Flattener Preview "Convert All Text To Outlines" ).  v15.0.4 and higher. Place in \Sample_Source\ModifyContent\

** FormWalker.cs - Walks through AcroForm field of a PDF, describing the widget annotation properties (should work for statix XFA too). PGallot sample, updated with a bit more info on signature fields.  v15.0.4 and higher. Place in \Sample_Source\InformationExtraction\FormWalker

** ModifyLinkAnnotDests.cs - Walk through the link annots and change the JS or URI Actions that contain the destination URL.   v15.0.4 and higher. Place in \Sample_Source\ContentModification\ModifyLinkAnnotDests

** PDFOptimizerSampleByteArray.java - Optimization sample that reads/writes to a byte array and uses ByteArrayInputStream and ByteArrayOutputStream.  To construct the ImageInputStream/ImageOutputStream requires v15.0.4 and higher. Place in \samples\PDFOptimizerSample folder.
 
 ** RepeatingFormXObject.cs - Sample creates a Form object to hold boilerplate content that needs to be repeated on each page; and adds unique content on top for each page. For use with account statements, credit card statements, etc. Creates from 1 to N unique pages. Place in \Sample_Source\ContentCreation\RepeatingFormXObject folder.  Uses DuckyAccountStatement.pdf as the source template
