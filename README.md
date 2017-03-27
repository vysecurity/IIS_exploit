# CVE-2017-7269

[Description]
Buffer overflow in the ScStoragePathFromUrl function in the WebDAV service in Internet Information Services (IIS) 6.0 in Microsoft Windows Server 2003 R2 allows remote attackers to execute arbitrary code via a long header beginning with "If: &lt;http://" in a PROPFIND request, as exploited in the wild in July or August 2016.


[Additional Information]
the ScStoragePathFromUrl function is called twice

[Vulnerability Type]
Buffer overflow

[Vendor of Product]
Microsoft

[Affected Product Code Base]
Windows Server 2003 R2

[Affected Component]
ScStoragePathFromUrl

[Attack Type]
Remote

[Impact Code execution]
true

[Attack Vectors]
crafted PROPFIND data

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Zhiniang Peng and Chen Wu.

Information Security Lab & School of Computer Science & Engineering, South China University of Technology 
Guangzhou, China



