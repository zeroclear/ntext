# Windows XP API补全计划
可以解决的问题：  
GetCurrentProcessorNumber  
InitializeCriticalSectionEx  
ws2_32.inet_ntop  
ws2_32.inet_pton  
读写锁相关API  
条件变量相关API  
RaiseFailFastException  
CreateEventExA  
GetFinalPathNameByHandleW  
  
目前还有些难度的问题：  
GetTickCount64  
运行时TLS动态分配槽的问题  
advapi.RegGetValueW  
IoConnectInterruptEx和MSIX  
CreateRemoteThreadEx  
  
有生之年可能都无法解决的问题：  
Core Audio系列API  
NTFS的transacted  
NtQueryObject用在某些对象上会卡死  
完成端口的CloseHandle可以直接唤醒线程并返回-1  
CancelIoEx  
GetOverlappedResultEx  
