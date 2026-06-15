This document lists the issues that the CBOR WG chairs have seen on the mailing list
in response to a request for comments on draft-ietf-cbor-edn-literals-26 draft.

The chairs will fill in this list from what they see on the drafts.
The document in this repo will not accept issues or pull requests.
If you want something added, please send a message to the mailing list.

1.  Introduction  

1.1.  Structure of This Document  

1.2.  Terminology and Conventions 

1.3.  (Non-)Objectives of this Document 

1.3.1.  For Humans  

1.3.2.  Determinism?  

1.3.3.  Basic Output Format 

1.3.4.  Evolution 

1.3.5.  Character Repertoire of Source 

2.  Concise Diagnostic Notation (CDN)

2.1.  Application-Oriented Extension Literals

2.2.  Comments 

2.2.1.  Discussion 

2.3.  Encoding Indicators

2.3.1.  Syntax, Semantics, Examples

2.4.  Numbers

2.5.  Strings

2.5.1.  No Special String Concatenation Syntax 

2.5.2.  Double-Quoted String Literals

2.5.3.  Single-Quoted String Literals

2.5.4.  Raw String Literals

2.5.5.  Deprecated: Indefinite-length Encoding Indicators for Strings

2.5.6.  Base-Encoded Byte String Literals

2.5.7.  CBOR Sequence Literals 

2.5.8.  Validity of Text Strings 

2.6.  Arrays and Maps

2.6.1.  Mandatory Separators, Optional Terminators 

2.6.2.  Encoding Indicators of Arrays and Maps 

2.6.3.  Validity of Maps 

2.7.  Tags 

2.8.  Simple values

3.  Application-Oriented Extension Literals

3.1.  Date and Time: The "dt" Extension

3.2.  IP Addresses and Related Structures: The "ip" Extension

3.3.  Cryptographic Hash Values: The "hash" Extension

3.4.  String Concatenation: The "b1" and "t1" Extensions 

3.5.  Creating Indefinite-length Encoded Strings: The "ilbs" and "ilts" Extensions

3.6.  Concise Resource Identifiers: The "cri" Extension

3.7.  The "float" Extension

4.  Tag-based Representations of CDN Input in Binary CBOR

4.1.  Handling unknown application-extension identifiers 

4.2.  Handling information deliberately elided from a CDN document 

5.  ABNF Definitions 

5.1.  Overall ABNF Definition for Concise Diagnostic Notation 

5.2.  ABNF Definitions for Application Extension Content 

5.2.1.  h: ABNF Definition of Hexadecimal representation of a byte string

5.2.2.  b64: ABNF Definition of Base64 representation of a byte string 

5.2.3.  dt: ABNF Definition of RFC 3339 Representation of a Date/Time

5.2.4.  ip: ABNF Definition of Textual Representation of an IP Address

5.2.5.  cri: ABNF Definition of URI Representation of a CRI

5.3.  ABNF Definitions for Integrated Extension Parsers

5.3.1.  h'': ABNF Definition of Integrated Parser

5.3.2.  b64'': ABNF Definition of Integrated Parser

5.3.3.  h``: ABNF Definition of Integrated Parser

5.3.4.  b64``: ABNF Definition of Integrated Parser

6.  IANA Considerations

6.1.  Concise Diagnostic Notation Application-extension Identifiers Registry 

6.2.  Encoding Indicators

6.3.  Media Type 

6.4.  Content-Format 

6.5.  Tags 

7.  Security considerations

8.  References 

8.1.  Normative References 

8.2.  Informative References 

Appendix A.  CDN and CDDL

