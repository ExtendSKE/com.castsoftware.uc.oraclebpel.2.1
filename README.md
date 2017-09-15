# com.castsoftware.uc.oraclebpel.2.1
BPEL Extension implemented based on Oracle BPEL2.0
Home
Welcome to the BPEL-Extension-Description-Page wiki!
Target audience: This document is to be used in the use of Extension made available by the Community of CAST Users 'BPEL Extension' by IT professionals experienced in operating CAST AIP platform for Application analysis.
________________________________________
Warning: The Extension described in this document is delivered as-is. This Extension is made available by CAST User Community and governed by Open Source License. Please consider all necessary steps to validate and to test the Extension in your environment before using it in production.
1. Description
The Extension should be used in the following situations: AI Admins who need to analyze applications which use BPEL script and WSDL service file. BPEL script is a language to specify BPEL processes. It provides a compact syntax inspired by scripting languages such as JavaScript and Ruby and a full coverage of all features provided by BPEL.

A BPEL process specifies in which order Web services should be invoked. It means A BPEL process receives a request and to full fill this invokes the involved Web services and then respond back to caller. It’s also possible a Web service can depend on the previous invokes also.

Implementation Patterns:-  

1. WSDL Process --> BPEL Process --> BPEL Invoke
2. WSDL Operation ->  WSDL Process ->BPEL Process ->BPEL Invoke -> Java Method

Objects created which are required only for transactions :
1. BPEL Process
2. BPEL Invoke
3. Java Method
4. WSDL Process


Extension Installation procedure:- 
http://doc.castsoftware.com/display/DOC82/Download+your+CAST+AIP+Extensions
For download the Extension :
https://extend.castsoftware.com

