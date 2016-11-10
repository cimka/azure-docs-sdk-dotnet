---
uid: 
remarks: *content
---
## Remarks  
 This operation stops an ongoing resize operation on the pool.  The pool size will stabilize at the number of nodes it is at             when the stop operation is done.  During the stop operation, the pool [Microsoft.Azure.Batch](assetId:///N:Microsoft.Azure.Batch?qualifyHint=False&autoUpgrade=True) changes first             to [Stopping](assetId:///T:Microsoft.Azure.Batch.Common.AllocationState?qualifyHint=False&autoUpgrade=True) and then to [Steady](assetId:///T:Microsoft.Azure.Batch.Common.AllocationState?qualifyHint=False&autoUpgrade=True).  
  
 This is a blocking operation. For a non-blocking equivalent, see [StopResizeAsync](assetId:///M:Microsoft.Azure.Batch.CloudPool.StopResizeAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)?qualifyHint=False&autoUpgrade=True).