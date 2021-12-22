# oActivatorType
 "CLR.Au3" #include &lt;FileConstants.au3> #include &lt;MsgBoxConstants.au3>  Local $str = "Q0xTCiMgaHR0cHM6Ly9naXRodWIuY29tL1JpYmJvbldpbkZvcm1zL1JpYmJvbldpbkZvcm1zCiMgc2VlIGhlcmUgZm9yIHRpcHMgCiMgaHR0cHM6Ly93d3cueW91dHViZS5jb20vd2F0Y2g/dj1PUHJqN2MxQ1lJZwoKJFJ1bnNwYWNlID0gW3J1bnNwYWNlZmFjdG9yeV06OkNyZWF0ZVJ1bnNwYWNlKCkKCiRSdW5zcGFjZS5BcGFydG1lbnRTdGF0ZSA9ICJTVEEiICMgQ2hhbmdlIGhlcmUgIQokUnVuc3BhY2UuVGhyZWFkT3B0aW9ucyA9ICJSZXVzZVRocmVhZCIKCiRQb3dlclNoZWxsID0gW3Bvd2Vyc2hlbGxdOjpDcmVhdGUoKQoKJFBvd2VyU2hlbGwuUnVuc3BhY2UgPSAkUnVuc3BhY2UKCiRSdW5zcGFjZS5PcGVuKCkKCiRob3N0LlJ1bnNwYWNlLlRocmVhZE9wdGlvbnMudmFsdWVfXwokUnVuc3BhY2UuUnVuc3BhY2VTdGF0ZUluZm8KCiMgU3RhcnQgCiRzdHJpbmcgPSB7IAoKQWRkLVR5cGUgLVBhdGggKCIkUFdEXFN5c3RlbS5XaW5kb3dzLkZvcm1zLlJpYmJvbjM1LmRsbCIpCiRmb3JtID0gTmV3LU9iamVjdCBTeXN0ZW0uV2luZG93cy5Gb3Jtcy5Gb3JtCiRmb3JtLlNpemUgPSBOZXctT2JqZWN0IFN5c3RlbS5EcmF3aW5nLlNpemUoNjAwLDMwMCkKJGZvcm0uVG9wTW9zdCA9ICR0cnVlCiRmb3JtLlN0YXJ0UG9zaXRpb24gPSAiQ2VudGVyU2NyZWVuIgoKJGZvcm0uQXV0b1NjYWxlbW9kZSA9ICJGb250IiAjIEVudW0gRm9udCBvciBEUEkKJGZvcm0uQXV0b1NpemUgPSAkdHJ1ZQokZm9ybS5BdXRvU2l6ZU1vZGUgPSAiR3Jvd09ubHkiICAjICJHcm93QW5kU2hyaW5rIgoKJGZvcm0uU3VzcGVuZExheW91dCgpCgojIE9iamVjdHMKJHJpYmJvbiA9IE5ldy1PYmplY3QgU3lzdGVtLldpbmRvd3MuRm9ybXMuUmliYm9uCiR0YWIxID0gTmV3LW9iamVjdCBTeXN0ZW0uV2luZG93cy5Gb3Jtcy5SaWJib25UYWIKJHRhYjIgPSBOZXctb2JqZWN0IFN5c3RlbS5XaW5kb3dzLkZvcm1zLlJpYmJvblRhYgokTWVudUl0ZW0xID0gTmV3LW9iamVjdCBTeXN0ZW0uV2luZG93cy5Gb3Jtcy5SaWJib25PcmJNZW51SXRlbQokcGFuZWwxID0gTmV3LW9iamVjdCBTeXN0ZW0uV2luZG93cy5Gb3Jtcy5SaWJib25QYW5lbAokYnV0dG9uMSA9IE5ldy1vYmplY3QgU3lzdGVtLldpbmRvd3MuRm9ybXMuUmliYm9uQnV0dG9uCgojICRyaWJib24gfCBnZXQtbWVtYmVyCiMgJHJpYmJvbi5QYXJlbnQKCiMgcmliYm9uMQokcmliYm9uLkZvbnQgPSBOZXctT2JqZWN0IFN5c3RlbS5EcmF3aW5nLkZvbnQoIlNlZ29lIFVJIiwgOSk7CiRyaWJib24uTG9jYXRpb24gPSBOZXctT2JqZWN0IFN5c3RlbS5EcmF3aW5nLlBvaW50KDAsIDApOwokcmliYm9uLk1pbmltaXplZCA9ICRmYWxzZTsKJHJpYmJvbi5OYW1lID0gInJpYmJvbjEiOwoKJHJpYmJvbi5PcmJTdHlsZSA9ICJPZmZpY2VfMjAwNyIgIyAiT2ZmaWNlXzIwMTAiIG9yICJPZmZpY2VfMjAxMyIKIyRyaWJib24uVmlzaWJsZSA9ICR0cnVlCgokcmliYm9uLk9yYkRyb3BEb3duLkJvcmRlclJvdW5kbmVzcyA9IDg7CiRyaWJib24uT3JiRHJvcERvd24uTG9jYXRpb24gPSBOZXctT2JqZWN0IFN5c3RlbS5EcmF3aW5nLlBvaW50KDAsIDApOwokcmliYm9uLk9yYkRyb3BEb3duLk1lbnVJdGVtcy5BZGQoJE1lbnVJdG"       $str &amp;= "VtMSk7CiRyaWJib24uT3JiRHJvcERvd24uTmFtZSA9ICJEcm9wIjsKJHJpYmJvbi5PcmJEcm9wRG93bi5TaXplID0gTmV3LU9iamVjdCBTeXN0ZW0uRHJhd2luZy5TaXplKDUyNywgMTE2KTsKJHJpYmJvbi5PcmJEcm9wRG93bi5UYWJJbmRleCA9IDA7CiRyaWJib24uT3JiSW1hZ2UgPSAkbnVsbDsKJHJpYmJvbi5SaWJib25UYWJGb250ID0gTmV3LU9iamVjdCBTeXN0ZW0uRHJhd2luZy5Gb250KCJUcmVidWNoZXQgTVMiLCA5KTsKJHJpYmJvbi5TaXplID0gTmV3LU9iamVjdCBTeXN0ZW0uRHJhd2luZy5TaXplKDEyODAsIDIwMCk7CiRyaWJib24uVGFiSW5kZXggPSAwOwokcmliYm9uLlRhYnMuQWRkKCRUYWIxKTsKJHJpYmJvbi5UYWJzTWFyZ2luID0gTmV3LU9iamVjdCBTeXN0ZW0uV2luZG93cy5Gb3Jtcy5QYWRkaW5nKDEyLCAyNiwgMjAsIDApOwokcmliYm9uLlRleHQgPSAicmliYm9uMSI7CiRyaWJib24uVGhlbWVDb2xvciA9ICJCbHVlIjsKJHJpYmJvbi5IZWlnaHQgPSAxNTAKCiMgcmliYm9uT3JiTWVudUl0ZW0xCiRNZW51SXRlbTEuRHJvcERvd25BcnJvd0RpcmVjdGlvbiA9ICJMZWZ0IjsKJE1lbnVJdGVtMS5JbWFnZSA9IFtTeXN0ZW0uRHJhd2luZy5JbWFnZV06OkZyb21GaWxlKCIkUFdEXEFCRi1PdXRsb29rLUV4cHJlc3MtQmFja3VwLmdpZiIpIAojICgoU3lzdGVtLkRyYXdpbmcuSW1hZ2UpKHJlc291cmNlcy5HZXRPYmplY3QoInJpYmJvbk9yYk1lbnVJdGVtMS5JbWFnZSIpKSk7CiRNZW51SXRlbTEuU21hbGxJbWFnZSA9IFtTeXN0ZW0uRHJhd2luZy5JbWFnZV06OkZyb21GaWxlKCIkUFdEXEFCRi1PdXRsb29rLUV4cHJlc3MtQmFja3VwLmdpZiIpIAojICgoU3lzdGVtLkRyYXdpbmcuSW1hZ2UpKHJlc291cmNlcy5HZXRPYmplY3QoInJpYmJvbk9yYk1lbnVJdGVtMS5TbWFsbEltYWdlIikpKTsKJE1lbnVJdGVtMS5UZXh0ID0gInJpYmJvbk9yYk1lbnVJdGVtMSI7CgojIHJpYmJvblRhYjEKJFRhYjEuUGFuZWxzLkFkZCgkcGFuZWwxKTsKJFRhYjEuVGV4dCA9ICJyaWJib25UYWIxIjsKCiMgcmliYm9uUGFuZWwxCiRQYW5lbDEuSXRlbXMuQWRkKCRCdXR0b24xKTsKJFBhbmVsMS5UZXh0ID0gInJpYmJvblBhbmVsMSI7CgojIHJpYmJvbkJ1dHRvbjF6enp6enoKJEJ1dHRvbjEuSW1hZ2UgPSBbU3lzdGVtLkRyYXdpbmcuSW1hZ2VdOjpGcm9tRmlsZSgiJFBXRFxTYXZlSXRlbS5wbmciKSAKIygoU3lzdGVtLkRyYXdpbmcuSW1hZ2UpKHJlc291cmNlcy5HZXRPYmplY3QoInJpYmJvbkJ1dHRvbjEuSW1hZ2UiKSkpOwokQnV0dG9uMS5TbWFsbEltYWdlID0gW1N5c3RlbS5EcmF3aW5nLkltYWdlXTo6RnJvbUZpbGUoIiRQV0RcU2F2ZUl0ZW0ucG5nIikgCiMgKChTeXN0ZW0uRHJhd2luZy5JbWFnZSkocmVzb3VyY2VzLkdldE9iamVjdCgicmliYm9uQnV0dG9uMS5TbWFsbEltYWdlIikpKTsKJEJ1dHRvbjEuVGV4dCA9ICJyaWJib25CdXR0b24xIjsKCiRCdXR0b24xLmFkZF9jbGljayh7CiAgICAkbWVzc2FnZWJveHJlcGx5ID0gW1N5c3RlbS5XaW5kb3dzLkZvcm1zLk1lc3NhZ2VCb3hdOjpTaG93KCJEbyB5b3Ugd2lzaCB0byBjb250aW51ZSA/IiwiV2VsY29tZSIsMykKfSkKCiMgcmliYm9uVGFiMgokVGFiMi5UZXh0ID0gInJpYmJvblRhYjIiOwoKJGZvcm0uQ29udHJvbHMuQWRkKCRyaWJib24pCgokZm9ybS5SZXN1bWVMYXlvdXQoJGZhbHNlKQoKJGZvcm0uU2hvd0RpYWxvZygpCn0KCiNFbmQKClt2b2lkXSRQb3dlclNoZWxsLkFkZFNjcmlwdCgkc3RyaW5nKQoKJFBvd2VyU2hlbGwuSW52b2tlKCkgCgokUG93ZXJTaGVsbC5FbmRJbnZva2UKCiRSdW5zcGFjZS5DbG9zZSgpCiRQb3dlcnNoZWxsLkRpc3Bvc2UoKQ==" ConsoleWrite($str &amp; @CRLF)  $str = _Base64Decode($str)  _Run_PSHost_Script(BinaryToString($str,1))   Func _Run_PSHost_Script($PSScript)     Local $oAssembly = _CLR_LoadLibrary("System.Management.Automation")     ConsoleWrite("!$oAssembly: " &amp; IsObj($oAssembly) &amp; @CRLF)      ; Create Object     Local $pAssemblyType = 0     $oAssembly.GetType_2("System.Management.Automation.PowerShell", $pAssemblyType)     ConsoleWrite("$pAssemblyType = " &amp; Ptr($pAssemblyType) &amp; @CRLF)      Local $oActivatorType = ObjCreateInterface($pAssemblyType, $sIID_IType, $sTag_IType)     ConsoleWrite("IsObj( $oAssemblyType ) = " &amp; IsObj($oActivatorType) &amp; @TAB &amp; @CRLF)      ; Create Object     Local $pObjectPS = 0     $oActivatorType.InvokeMember_3("Create", 0x158, 0, 0, 0, $pObjectPS)     ConsoleWrite("IsObject: " &amp; IsObj($pObjectPS) &amp; @TAB &amp; "$pObject: " &amp; ObjName($pObjectPS) &amp; @CRLF)   ; &lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt; PS COMMAND HERE >>>>>>>>>>>>>>>>>>>>     $pObjectPS.AddScript($PSScript) ; Add Script here ;~  ConsoleWrite($PSScript &amp; @CRLF)      $objAsync = $pObjectPS.BeginInvoke ; (2); ($oActivatorType,$oActivatorType)      While $objAsync.IsCompleted = False
