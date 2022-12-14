<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Worker](./bullmq.worker.md) &gt; [getNextJob](./bullmq.worker.getnextjob.md)

## Worker.getNextJob() method

Returns a promise that resolves to the next job in queue.

<b>Signature:</b>

```typescript
getNextJob(token: string, { block }?: GetNextJobOptions): Promise<Job<DataType, ResultType, NameType>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  token | string | worker token to be assigned to retrieved job |
|  { block } | [GetNextJobOptions](./bullmq.getnextjoboptions.md) |  |

<b>Returns:</b>

Promise&lt;[Job](./bullmq.job.md)<!-- -->&lt;DataType, ResultType, NameType&gt;&gt;

a Job or undefined if no job was available in the queue.

