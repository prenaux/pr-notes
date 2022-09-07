# Module niCURL
Generated on 2022-09-07T10:09:41+08:00

- name: niCURL
- desc: CURL module
- version: 1,0,0
- author: niLang Authors
- copyright: (c) 2022 The niLang Authors

## enum ni::eCURLMessage
CURL message. 

### Values:
- __eCURLMessage_Started__ = __niMessageID('C','U','R','L','t')__: The request started. 
- __eCURLMessage_ResponseCode__ = __niMessageID('C','U','R','L','o')__: Received a response code from the server. 
- __eCURLMessage_ReceivingHeader__ = __niMessageID('C','U','R','L','h')__: Started receiving the header. 
- __eCURLMessage_ReceivingData__ = __niMessageID('C','U','R','L','r')__: Started receiving the data. 
- __eCURLMessage_ReceivedPart__ = __niMessageID('C','U','R','L','m')__: Received a part. 
- __eCURLMessage_Sending__ = __niMessageID('C','U','R','L','s')__: Started sending data. 
- __eCURLMessage_Completed__ = __niMessageID('C','U','R','L','C')__: The request has successfully completed. 
- __eCURLMessage_Failed__ = __niMessageID('C','U','R','L','F')__: The request failed. 
- __eCURLMessage_Progress__ = __niMessageID('C','U','R','L','p')__: Progress message 

## enum ni::eCURLHttpAuth
HTTP authentication modes 

### Remarks:
- This uses the same value as CURLOPT_HTTPAUTH options in libcurl for convenience. 

### Values:
- __eCURLHttpAuth_None__ = __0__
- __eCURLHttpAuth_Basic__ = __niBit(0)__
- __eCURLHttpAuth_Digest__ = __niBit(1)__
- __eCURLHttpAuth_Gssnegotiate__ = __niBit(2)__
- __eCURLHttpAuth_Ntlm__ = __niBit(3)__
- __eCURLHttpAuth_DigestIE__ = __niBit(4)__
- __eCURLHttpAuth_NtlmWB__ = __niBit(5)__
- __eCURLHttpAuth_Only__ = __niBit(31)__
- __eCURLHttpAuth_Any__ = __~eCURLHttpAuth_DigestIE__
- __eCURLHttpAuth_AnySafe__ = __~(eCURLHttpAuth_Basic|eCURLHttpAuth_DigestIE)__

## interface ni::iCURL
CURL interface. 

### Parents:
- iUnknown

### Methods:
- __iCURL::GetVersion__() -> _cString_
- __iCURL::GetProtocols__() -> _cString_
- __iCURL::SetConnectionTimeoutInSecs__(_tU32_ anInSecs) -> _void_
- __iCURL::GetConnectionTimeoutInSecs__() -> _tU32_
- __iCURL::SetRequestTimeoutInSecs__(_tU32_ anInSecs) -> _void_
- __iCURL::GetRequestTimeoutInSecs__() -> _tU32_
- __iCURL::SetUserAgent__(_const achar\*_ aaszUserAgent) -> _void_
- __iCURL::GetUserAgent__() -> _const achar\*_
- __iCURL::SetUserName__(_const achar\*_ aaszUserName) -> _void_
- __iCURL::GetUserName__() -> _const achar\*_
- __iCURL::SetUserPass__(_const achar\*_ aaszUserPass) -> _void_
- __iCURL::GetUserPass__() -> _const achar\*_
- __iCURL::SetHttpAuth__(_eCURLHttpAuth_ aHttpAuth) -> _void_
- __iCURL::GetHttpAuth__() -> _const eCURLHttpAuth_
- __iCURL::URLGet__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _const tStringCVec\*_ apHeaders) -> _Ptr<iRunnable>_
- __iCURL::URLPostFile__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _iFile\*_ apPostData, _const tStringCVec\*_ apHeaders, _const achar\*_ aContentType) -> _Ptr<iRunnable>_
- __iCURL::URLPostFields__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _const achar\*_ aPostFields, _const tStringCVec\*_ apHeaders, _const achar\*_ aContentType) -> _Ptr<iRunnable>_
- __iCURL::URLPostRaw__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _tPtr_ aPostData, _tSize_ anPostDataSize, _const tStringCVec\*_ apHeaders, _const achar\*_ aContentType) -> _Ptr<iRunnable>_
- __iCURL::URLPostMultiPart__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _tStringCMap\*_ apPostFields) -> _Ptr<iRunnable>_: Post with Content-Type: multipart/form-data. Fields are similar to the command line version of CURL, @path will upload the file located at the specified location. 
- __iCURL::URLGetMultiPart__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _const achar\*_ aPartExt) -> _Ptr<iRunnable>_
- __iCURL::URLGetString__(_const achar\*_ aURL) -> _cString_: Does a simple get on a URL and return the result as a string. 
- __iCURL::URLGetDataTable__(_const achar\*_ aURL, _iDataTable\*_ apResult) -> _tI32_: Does a simple get on a URL and return the result as a datatable. 

## enum ni::eCURLMessage
CURL message. 

### Values:
- __eCURLMessage_Started__ = __niMessageID('C','U','R','L','t')__: The request started. 
- __eCURLMessage_ResponseCode__ = __niMessageID('C','U','R','L','o')__: Received a response code from the server. 
- __eCURLMessage_ReceivingHeader__ = __niMessageID('C','U','R','L','h')__: Started receiving the header. 
- __eCURLMessage_ReceivingData__ = __niMessageID('C','U','R','L','r')__: Started receiving the data. 
- __eCURLMessage_ReceivedPart__ = __niMessageID('C','U','R','L','m')__: Received a part. 
- __eCURLMessage_Sending__ = __niMessageID('C','U','R','L','s')__: Started sending data. 
- __eCURLMessage_Completed__ = __niMessageID('C','U','R','L','C')__: The request has successfully completed. 
- __eCURLMessage_Failed__ = __niMessageID('C','U','R','L','F')__: The request failed. 
- __eCURLMessage_Progress__ = __niMessageID('C','U','R','L','p')__: Progress message 

## enum ni::eCURLMessage
CURL message. 

### Values:
- __eCURLMessage_Started__ = __niMessageID('C','U','R','L','t')__: The request started. 
- __eCURLMessage_ResponseCode__ = __niMessageID('C','U','R','L','o')__: Received a response code from the server. 
- __eCURLMessage_ReceivingHeader__ = __niMessageID('C','U','R','L','h')__: Started receiving the header. 
- __eCURLMessage_ReceivingData__ = __niMessageID('C','U','R','L','r')__: Started receiving the data. 
- __eCURLMessage_ReceivedPart__ = __niMessageID('C','U','R','L','m')__: Received a part. 
- __eCURLMessage_Sending__ = __niMessageID('C','U','R','L','s')__: Started sending data. 
- __eCURLMessage_Completed__ = __niMessageID('C','U','R','L','C')__: The request has successfully completed. 
- __eCURLMessage_Failed__ = __niMessageID('C','U','R','L','F')__: The request failed. 
- __eCURLMessage_Progress__ = __niMessageID('C','U','R','L','p')__: Progress message 

## enum ni::eCURLHttpAuth
HTTP authentication modes 

### Remarks:
- This uses the same value as CURLOPT_HTTPAUTH options in libcurl for convenience. 

### Values:
- __eCURLHttpAuth_None__ = __0__
- __eCURLHttpAuth_Basic__ = __niBit(0)__
- __eCURLHttpAuth_Digest__ = __niBit(1)__
- __eCURLHttpAuth_Gssnegotiate__ = __niBit(2)__
- __eCURLHttpAuth_Ntlm__ = __niBit(3)__
- __eCURLHttpAuth_DigestIE__ = __niBit(4)__
- __eCURLHttpAuth_NtlmWB__ = __niBit(5)__
- __eCURLHttpAuth_Only__ = __niBit(31)__
- __eCURLHttpAuth_Any__ = __~eCURLHttpAuth_DigestIE__
- __eCURLHttpAuth_AnySafe__ = __~(eCURLHttpAuth_Basic|eCURLHttpAuth_DigestIE)__

## interface ni::iCURL
CURL interface. 

### Parents:
- iUnknown

### Methods:
- __iCURL::GetVersion__() -> _cString_
- __iCURL::GetProtocols__() -> _cString_
- __iCURL::SetConnectionTimeoutInSecs__(_tU32_ anInSecs) -> _void_
- __iCURL::GetConnectionTimeoutInSecs__() -> _tU32_
- __iCURL::SetRequestTimeoutInSecs__(_tU32_ anInSecs) -> _void_
- __iCURL::GetRequestTimeoutInSecs__() -> _tU32_
- __iCURL::SetUserAgent__(_const achar\*_ aaszUserAgent) -> _void_
- __iCURL::GetUserAgent__() -> _const achar\*_
- __iCURL::SetUserName__(_const achar\*_ aaszUserName) -> _void_
- __iCURL::GetUserName__() -> _const achar\*_
- __iCURL::SetUserPass__(_const achar\*_ aaszUserPass) -> _void_
- __iCURL::GetUserPass__() -> _const achar\*_
- __iCURL::SetHttpAuth__(_eCURLHttpAuth_ aHttpAuth) -> _void_
- __iCURL::GetHttpAuth__() -> _const eCURLHttpAuth_
- __iCURL::URLGet__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _const tStringCVec\*_ apHeaders) -> _Ptr<iRunnable>_
- __iCURL::URLPostFile__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _iFile\*_ apPostData, _const tStringCVec\*_ apHeaders, _const achar\*_ aContentType) -> _Ptr<iRunnable>_
- __iCURL::URLPostFields__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _const achar\*_ aPostFields, _const tStringCVec\*_ apHeaders, _const achar\*_ aContentType) -> _Ptr<iRunnable>_
- __iCURL::URLPostRaw__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _tPtr_ aPostData, _tSize_ anPostDataSize, _const tStringCVec\*_ apHeaders, _const achar\*_ aContentType) -> _Ptr<iRunnable>_
- __iCURL::URLPostMultiPart__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _iFile\*_ apRecvData, _iFile\*_ apRecvHeader, _tStringCMap\*_ apPostFields) -> _Ptr<iRunnable>_: Post with Content-Type: multipart/form-data. Fields are similar to the command line version of CURL, @path will upload the file located at the specified location. 
- __iCURL::URLGetMultiPart__(_iMessageHandler\*_ apMessageHandler, _const achar\*_ aURL, _const achar\*_ aPartExt) -> _Ptr<iRunnable>_
- __iCURL::URLGetString__(_const achar\*_ aURL) -> _cString_: Does a simple get on a URL and return the result as a string. 
- __iCURL::URLGetDataTable__(_const achar\*_ aURL, _iDataTable\*_ apResult) -> _tI32_: Does a simple get on a URL and return the result as a datatable. 

## enum ni::eCURLMessage
CURL message. 

### Values:
- __eCURLMessage_Started__ = __niMessageID('C','U','R','L','t')__: The request started. 
- __eCURLMessage_ResponseCode__ = __niMessageID('C','U','R','L','o')__: Received a response code from the server. 
- __eCURLMessage_ReceivingHeader__ = __niMessageID('C','U','R','L','h')__: Started receiving the header. 
- __eCURLMessage_ReceivingData__ = __niMessageID('C','U','R','L','r')__: Started receiving the data. 
- __eCURLMessage_ReceivedPart__ = __niMessageID('C','U','R','L','m')__: Received a part. 
- __eCURLMessage_Sending__ = __niMessageID('C','U','R','L','s')__: Started sending data. 
- __eCURLMessage_Completed__ = __niMessageID('C','U','R','L','C')__: The request has successfully completed. 
- __eCURLMessage_Failed__ = __niMessageID('C','U','R','L','F')__: The request failed. 
- __eCURLMessage_Progress__ = __niMessageID('C','U','R','L','p')__: Progress message 
