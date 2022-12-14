<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [ScriptLoader](./bullmq.scriptloader.md) &gt; [loadScripts](./bullmq.scriptloader.loadscripts.md)

## ScriptLoader.loadScripts() method

Load redis lua scripts. The name of the script must have the following format:

cmdName-numKeys.lua

cmdName must be in camel case format.

For example: moveToFinish-3.lua

<b>Signature:</b>

```typescript
loadScripts(dir?: string, cache?: Map<string, ScriptMetadata>): Promise<Command[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  dir | string |  |
|  cache | Map&lt;string, [ScriptMetadata](./bullmq.scriptmetadata.md)<!-- -->&gt; |  |

<b>Returns:</b>

Promise&lt;[Command](./bullmq.command.md)<!-- -->\[\]&gt;

