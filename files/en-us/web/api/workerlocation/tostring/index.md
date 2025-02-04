---
title: WorkerLocation.toString()
slug: Web/API/WorkerLocation/toString
tags:
  - API
  - Method
  - Stringifier
  - Reference
  - WorkerLocation
browser-compat: api.WorkerLocation.toString
---
{{ApiRef("WorkerLocation")}}

The **`toString()`** {{Glossary("stringifier")}} method of a {{domxref("WorkerLocation")}} object returns a string containing the serialized {{domxref("URL")}} for the worker's location. It is a synonym for {{domxref("WorkerLocation.href")}}.

## Syntax

```js
toString()
```

### Parameters

None.

## Examples

```js
// In a Web worker, on the page https://developer.mozilla.org/en-US/docs/Web
var result = location.toString(); // Returns 'https://developer.mozilla.org/en-US/docs/Web'
```

## Browser compatibility

{{Compat}}

## See also

- The {{domxref("WorkerLocation")}} interface it belongs to.
