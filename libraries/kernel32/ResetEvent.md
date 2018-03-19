
## Function name : ResetEvent
Group: Synchronization - Library: kernel32    
***  


#### The ResetEvent function sets the specified event object to the nonsignaled state.
***  


## Code examples:
[Using an Event Object. Part B: running an application responding to events](../../samples/sample_149.md)  

## Declaration:
```foxpro  
BOOL ResetEvent(
  HANDLE hEvent   // handle to event
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER ResetEvent IN kernel32;
	INTEGER hEvent  
```  
***  


## Parameters:
hEvent 
[in] Handle to the event object. The CreateEvent or OpenEvent function returns this handle.  
***  


## Return value:
If the function succeeds, the return value is nonzero.  
***  
