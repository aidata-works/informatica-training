INFORMATICA NUMBER CONVERSION SOAP LAB

Files:
- numberconversion.wsdl: Reconstructed from a publicly posted copy of the DataAccess NumberConversion WSDL (not directly retrieved from the live provider).
- NumberToWords_request.xml: SOAP 1.1 example with ubiNum=123.
- NumberToDollars_request.xml: SOAP 1.1 example with dNum=123.45.

WSDL service endpoint: https://www.dataaccess.com/webservicesserver/numberconversion.wso
Source WSDL reference: https://git.etud.insa-toulouse.fr/nbillard/SOA/src/commit/e4607e3968dc67586b6bc2214bc00f7bab08c707/NumberConversion/src/main/resources/wsdl/numberconversion.wsdl

In Informatica: choose WSDL from File and upload numberconversion.wsdl if supported. Make sure the Secure Agent can reach the SOAP service endpoint for execution. Hosting the WSDL does not host the service.

For SOAP 1.1 requests use Content-Type: text/xml; charset=utf-8 and SOAPAction: "" (empty as declared in this WSDL).
