<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Job](./bullmq.job.md) &gt; [getState](./bullmq.job.getstate.md)

## Job.getState() method

Get current state.

<b>Signature:</b>

```typescript
getState(): Promise<JobState | 'unknown'>;
```
<b>Returns:</b>

Promise&lt;[JobState](./bullmq.jobstate.md) \| 'unknown'&gt;

Returns one of these values: 'completed', 'failed', 'delayed', 'active', 'waiting', 'waiting-children', 'unknown'.

