# XLSTestCaseUploadUtilityForTestLink
This utility helps uploading test cases written in excel sheet to test link. A XML file will be generated as an output which can be uploaded in Testlink 

# Steps 

Download from: https://github.com/srinivasanarulsivam/XLSTestCaseUploadUtilityForTestLink/tree/master/artifact

or follow steps

1. Clone Repository: https://github.com/srinivasanarulsivam/XLSTestCaseUploadUtilityForTestLink.git
2. Run mvn clean install
3. Executable jar [xlsTestCaseUploadUtility.jar] should be available in root/artifact directory 

# Guidelines

1. Supported Format: .xls only [.xlsx is not supported]
2. Sample input file: https://github.com/srinivasanarulsivam/XLSTestCaseUploadUtilityForTestLink/blob/master/src/main/resources/SampleTestCaseFormat.xls
3. Sample output file: https://github.com/srinivasanarulsivam/XLSTestCaseUploadUtilityForTestLink/blob/master/src/main/resources/sample-output.xml
4.Ensure the fields are populated correctly before you attempt to convert to XML. Field values have a vital role in output genration
