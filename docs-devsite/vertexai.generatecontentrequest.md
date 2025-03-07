Project: /docs/reference/js/_project.yaml
Book: /docs/reference/_book.yaml
page_type: reference

{% comment %}
DO NOT EDIT THIS FILE!
This is generated by the JS SDK team, and any local changes will be
overwritten. Changes should be made in the source code at
https://github.com/firebase/firebase-js-sdk
{% endcomment %}

# GenerateContentRequest interface
Request sent through [GenerativeModel.generateContent()](./vertexai.generativemodel.md#generativemodelgeneratecontent)

<b>Signature:</b>

```typescript
export interface GenerateContentRequest extends BaseParams 
```
<b>Extends:</b> [BaseParams](./vertexai.baseparams.md#baseparams_interface)

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [contents](./vertexai.generatecontentrequest.md#generatecontentrequestcontents) | [Content](./vertexai.content.md#content_interface)<!-- -->\[\] |  |
|  [systemInstruction](./vertexai.generatecontentrequest.md#generatecontentrequestsysteminstruction) | string \| [Part](./vertexai.md#part) \| [Content](./vertexai.content.md#content_interface) |  |
|  [toolConfig](./vertexai.generatecontentrequest.md#generatecontentrequesttoolconfig) | [ToolConfig](./vertexai.toolconfig.md#toolconfig_interface) |  |
|  [tools](./vertexai.generatecontentrequest.md#generatecontentrequesttools) | [Tool](./vertexai.md#tool)<!-- -->\[\] |  |

## GenerateContentRequest.contents

<b>Signature:</b>

```typescript
contents: Content[];
```

## GenerateContentRequest.systemInstruction

<b>Signature:</b>

```typescript
systemInstruction?: string | Part | Content;
```

## GenerateContentRequest.toolConfig

<b>Signature:</b>

```typescript
toolConfig?: ToolConfig;
```

## GenerateContentRequest.tools

<b>Signature:</b>

```typescript
tools?: Tool[];
```
