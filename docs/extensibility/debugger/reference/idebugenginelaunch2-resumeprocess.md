---
title: "IDebugEngineLaunch2::ResumeProcess | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
f1_keywords: 
  - "IDebugEngineLaunch2::ResumeProcess"
helpviewer_keywords: 
  - "IDebugEngineLaunch2::ResumeProcess"
ms.assetid: 61ccc14e-75c6-44e7-aae4-57a9aac52089
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# IDebugEngineLaunch2::ResumeProcess
Resumes process execution.  
  
## Syntax  
  
```cpp  
HRESULT ResumeProcess (   
   IDebugProcess2* pProcess  
);  
```  
  
```csharp  
int ResumeProcess (   
   IDebugProcess2 pProcess  
);  
```  
  
#### Parameters  
 `pProcess`  
 [in] An [IDebugProcess2](../../../extensibility/debugger/reference/idebugprocess2.md) object that represents the process to be resumed.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise returns an error code.  
  
## Remarks  
 This method is called after a process has been launched with a call to the [LaunchSuspended](../../../extensibility/debugger/reference/idebugenginelaunch2-launchsuspended.md) method.  
  
## See Also  
 [IDebugEngineLaunch2](../../../extensibility/debugger/reference/idebugenginelaunch2.md)   
 [IDebugProcess2](../../../extensibility/debugger/reference/idebugprocess2.md)   
 [LaunchSuspended](../../../extensibility/debugger/reference/idebugenginelaunch2-launchsuspended.md)