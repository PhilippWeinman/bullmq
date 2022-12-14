<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [RepeatOptions](./bullmq.repeatoptions.md)

## RepeatOptions interface

Settings for repeatable jobs

<b>Signature:</b>

```typescript
export interface RepeatOptions extends Omit<ParserOptions, 'iterator'> 
```
<b>Extends:</b> Omit&lt;ParserOptions, 'iterator'&gt;

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [count?](./bullmq.repeatoptions.count.md) | number | <i>(Optional)</i> The start value for the repeat iteration count. |
|  [cron?](./bullmq.repeatoptions.cron.md) | string | <i>(Optional)</i> A cron pattern |
|  [every?](./bullmq.repeatoptions.every.md) | number | <i>(Optional)</i> Repeat after this amount of milliseconds (<code>cron</code> setting cannot be used together with this setting.) |
|  [immediately?](./bullmq.repeatoptions.immediately.md) | boolean | <i>(Optional)</i> Repeated job should start right now ( work only with every settings) |
|  [jobId?](./bullmq.repeatoptions.jobid.md) | string | <i>(Optional)</i> |
|  [limit?](./bullmq.repeatoptions.limit.md) | number | <i>(Optional)</i> Number of times the job should repeat at max. |
|  [offset?](./bullmq.repeatoptions.offset.md) | number | <i>(Optional)</i> |
|  [prevMillis?](./bullmq.repeatoptions.prevmillis.md) | number | <i>(Optional)</i> |

