# Utils

## API

<docgen-index>

* [`convertBytesToHex(...)`](#convertbytestohex)
* [`convertBytesToString(...)`](#convertbytestostring)
* [`convertHexToBytes(...)`](#converthextobytes)
* [`convertStringToBytes(...)`](#convertstringtobytes)
* [`createNdefRecord(...)`](#createndefrecord)
* [`createNdefEmptyRecord()`](#createndefemptyrecord)
* [`createNdefTextRecord(...)`](#createndeftextrecord)
* [`createNdefUriRecord(...)`](#createndefurirecord)
* [`createNdefAbsoluteUriRecord(...)`](#createndefabsoluteurirecord)
* [`createNdefMimeMediaRecord(...)`](#createndefmimemediarecord)
* [`createNdefExternalRecord(...)`](#createndefexternalrecord)
* [`getTextFromNdefTextRecord(...)`](#gettextfromndeftextrecord)
* [`getLanguageFromNdefTextRecord(...)`](#getlanguagefromndeftextrecord)
* [`mapBytesToRecordTypeDefinition(...)`](#mapbytestorecordtypedefinition)
* [Interfaces](#interfaces)
* [Enums](#enums)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### convertBytesToHex(...)

```typescript
convertBytesToHex(options: ConvertBytesToHexOptions) => { hex: string; }
```

Convert a byte array to a string.

| Param         | Type                                                                          |
| ------------- | ----------------------------------------------------------------------------- |
| **`options`** | <code><a href="#convertbytestohexoptions">ConvertBytesToHexOptions</a></code> |

**Returns:** <code>{ hex: string; }</code>

**Since:** 0.3.1

--------------------


### convertBytesToString(...)

```typescript
convertBytesToString(options: ConvertBytesToStringOptions) => { text: string; }
```

Convert a byte array to a string.

| Param         | Type                                                                                |
| ------------- | ----------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#convertbytestostringoptions">ConvertBytesToStringOptions</a></code> |

**Returns:** <code>{ text: string; }</code>

**Since:** 0.0.1

--------------------


### convertHexToBytes(...)

```typescript
convertHexToBytes(options: ConvertHexToBytesOptions) => { bytes: number[]; }
```

Convert a byte array to a string.

| Param         | Type                                                                          |
| ------------- | ----------------------------------------------------------------------------- |
| **`options`** | <code><a href="#converthextobytesoptions">ConvertHexToBytesOptions</a></code> |

**Returns:** <code>{ bytes: number[]; }</code>

**Since:** 0.3.1

--------------------


### convertStringToBytes(...)

```typescript
convertStringToBytes(options: ConvertStringToBytesOptions) => { bytes: number[]; }
```

Convert a string to a byte array.

| Param         | Type                                                                                |
| ------------- | ----------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#convertstringtobytesoptions">ConvertStringToBytesOptions</a></code> |

**Returns:** <code>{ bytes: number[]; }</code>

**Since:** 0.0.1

--------------------


### createNdefRecord(...)

```typescript
createNdefRecord(options: CreateNdefRecordOptions) => CreateNdefRecordResult
```

Create a NDEF record.

| Param         | Type                                                                        |
| ------------- | --------------------------------------------------------------------------- |
| **`options`** | <code><a href="#createndefrecordoptions">CreateNdefRecordOptions</a></code> |

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### createNdefEmptyRecord()

```typescript
createNdefEmptyRecord() => CreateNdefRecordResult
```

Create an empty NDEF record.

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### createNdefTextRecord(...)

```typescript
createNdefTextRecord(options: CreateNdefTextRecordOptions) => CreateNdefRecordResult
```

Create a NDEF text record.

| Param         | Type                                                                                |
| ------------- | ----------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#createndeftextrecordoptions">CreateNdefTextRecordOptions</a></code> |

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### createNdefUriRecord(...)

```typescript
createNdefUriRecord(options: CreateNdefUriRecordOptions) => CreateNdefRecordResult
```

Create a NDEF URI record.

| Param         | Type                                                                              |
| ------------- | --------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#createndefurirecordoptions">CreateNdefUriRecordOptions</a></code> |

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### createNdefAbsoluteUriRecord(...)

```typescript
createNdefAbsoluteUriRecord(options: CreateNdefAbsoluteUriRecordOptions) => CreateNdefRecordResult
```

Create a NDEF absolute URI record.

| Param         | Type                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#createndefabsoluteurirecordoptions">CreateNdefAbsoluteUriRecordOptions</a></code> |

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### createNdefMimeMediaRecord(...)

```typescript
createNdefMimeMediaRecord(options: CreateNdefMimeMediaRecordOptions) => CreateNdefRecordResult
```

Create a NDEF mime media record.

| Param         | Type                                                                                          |
| ------------- | --------------------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#createndefmimemediarecordoptions">CreateNdefMimeMediaRecordOptions</a></code> |

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### createNdefExternalRecord(...)

```typescript
createNdefExternalRecord(options: CreateNdefExternalRecordOptions) => CreateNdefRecordResult
```

Create a NDEF external type record.

| Param         | Type                                                                                        |
| ------------- | ------------------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#createndefexternalrecordoptions">CreateNdefExternalRecordOptions</a></code> |

**Returns:** <code><a href="#createndefrecordresult">CreateNdefRecordResult</a></code>

**Since:** 0.0.1

--------------------


### getTextFromNdefTextRecord(...)

```typescript
getTextFromNdefTextRecord(options: GetTextFromNdefTextRecordOptions) => { text: string | undefined; }
```

Get the text from a NDEF text record.

| Param         | Type                                                                                          |
| ------------- | --------------------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#gettextfromndeftextrecordoptions">GetTextFromNdefTextRecordOptions</a></code> |

**Returns:** <code>{ text: string; }</code>

**Since:** 0.0.1

--------------------


### getLanguageFromNdefTextRecord(...)

```typescript
getLanguageFromNdefTextRecord(options: GetLanguageFromNdefTextRecordOptions) => { language: string | undefined; }
```

Get the language code from a NDEF text record.

| Param         | Type                                                                                                  |
| ------------- | ----------------------------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#getlanguagefromndeftextrecordoptions">GetLanguageFromNdefTextRecordOptions</a></code> |

**Returns:** <code>{ language: string; }</code>

**Since:** 0.0.1

--------------------


### mapBytesToRecordTypeDefinition(...)

```typescript
mapBytesToRecordTypeDefinition(options: { bytes: number[]; }) => { type: RecordTypeDefinition | undefined; }
```

Map a byte array to a the corresponding NDEF record type.

| Param         | Type                              |
| ------------- | --------------------------------- |
| **`options`** | <code>{ bytes: number[]; }</code> |

**Returns:** <code>{ type: <a href="#recordtypedefinition">RecordTypeDefinition</a>; }</code>

**Since:** 0.0.1

--------------------


### Interfaces


#### ConvertBytesToHexOptions

| Prop            | Type                  | Description                                | Default           | Since |
| --------------- | --------------------- | ------------------------------------------ | ----------------- | ----- |
| **`bytes`**     | <code>number[]</code> | The byte array to convert to a hex string. |                   | 0.3.1 |
| **`start`**     | <code>string</code>   | The text to prepend to the hex string.     | <code>'0x'</code> | 0.3.1 |
| **`separator`** | <code>string</code>   | The separator to use between each byte.    | <code>''</code>   | 0.3.1 |


#### ConvertBytesToStringOptions

| Prop        | Type                  | Description                            | Since |
| ----------- | --------------------- | -------------------------------------- | ----- |
| **`bytes`** | <code>number[]</code> | The byte array to convert to a string. | 0.0.1 |


#### ConvertHexToBytesOptions

| Prop            | Type                | Description                                              | Default           | Since |
| --------------- | ------------------- | -------------------------------------------------------- | ----------------- | ----- |
| **`hex`**       | <code>string</code> | The hex string to convert to a byte array.               |                   | 0.3.1 |
| **`start`**     | <code>string</code> | The text to remove from the beginning of the hex string. | <code>'0x'</code> | 0.3.1 |
| **`separator`** | <code>string</code> | The separator which is used between each byte.           | <code>''</code>   | 0.3.1 |


#### ConvertStringToBytesOptions

| Prop       | Type                | Description                            | Since |
| ---------- | ------------------- | -------------------------------------- | ----- |
| **`text`** | <code>string</code> | The string to convert to a byte array. | 0.0.1 |


#### CreateNdefRecordResult

| Prop         | Type                                              | Since |
| ------------ | ------------------------------------------------- | ----- |
| **`record`** | <code><a href="#ndefrecord">NdefRecord</a></code> | 0.0.1 |


#### NdefRecord

| Prop          | Type                                                      | Description                                                                                                              | Since |
| ------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ----- |
| **`id`**      | <code>number[]</code>                                     | The record identifier as byte array.                                                                                     | 0.0.1 |
| **`payload`** | <code>number[]</code>                                     | The payload field data as byte array.                                                                                    | 0.0.1 |
| **`tnf`**     | <code><a href="#typenameformat">TypeNameFormat</a></code> | The record type name format which indicates the structure of the value of the `type` field.                              | 0.0.1 |
| **`type`**    | <code>number[]</code>                                     | The type of the record payload. This should be used in conjunction with the `tnf` field to determine the payload format. | 0.0.1 |


#### CreateNdefRecordOptions

| Prop          | Type                                                      | Since |
| ------------- | --------------------------------------------------------- | ----- |
| **`id`**      | <code>string \| number[]</code>                           | 0.0.1 |
| **`payload`** | <code>string \| number[]</code>                           | 0.0.1 |
| **`tnf`**     | <code><a href="#typenameformat">TypeNameFormat</a></code> | 0.0.1 |
| **`type`**    | <code>string \| number[]</code>                           | 0.0.1 |


#### CreateNdefTextRecordOptions

| Prop           | Type                            | Description                       | Default         | Since |
| -------------- | ------------------------------- | --------------------------------- | --------------- | ----- |
| **`id`**       | <code>string \| number[]</code> |                                   |                 | 0.0.1 |
| **`text`**     | <code>string \| number[]</code> |                                   |                 | 0.0.1 |
| **`language`** | <code>string \| number[]</code> | The ISO/IANA language identifier. | <code>en</code> | 0.0.1 |


#### CreateNdefUriRecordOptions

| Prop      | Type                            | Since |
| --------- | ------------------------------- | ----- |
| **`id`**  | <code>string \| number[]</code> | 0.0.1 |
| **`uri`** | <code>string \| number[]</code> | 0.0.1 |


#### CreateNdefAbsoluteUriRecordOptions

| Prop      | Type                            | Since |
| --------- | ------------------------------- | ----- |
| **`id`**  | <code>string \| number[]</code> | 0.0.1 |
| **`uri`** | <code>string \| number[]</code> | 0.0.1 |


#### CreateNdefMimeMediaRecordOptions

| Prop           | Type                            | Description                       | Since |
| -------------- | ------------------------------- | --------------------------------- | ----- |
| **`id`**       | <code>string \| number[]</code> |                                   | 0.0.1 |
| **`mimeType`** | <code>string \| number[]</code> | A valid MIME type.                | 0.0.1 |
| **`mimeData`** | <code>string \| number[]</code> | The MIME data as bytes or string. | 0.0.1 |


#### CreateNdefExternalRecordOptions

| Prop          | Type                            | Description                              | Since |
| ------------- | ------------------------------- | ---------------------------------------- | ----- |
| **`id`**      | <code>string \| number[]</code> |                                          | 0.0.1 |
| **`payload`** | <code>string \| number[]</code> |                                          | 0.0.1 |
| **`domain`**  | <code>string \| number[]</code> | The domain-name of issuing organization. | 0.0.1 |
| **`type`**    | <code>string \| number[]</code> | The domain-specific type of data.        | 0.0.1 |


#### GetTextFromNdefTextRecordOptions

| Prop         | Type                                              | Since |
| ------------ | ------------------------------------------------- | ----- |
| **`record`** | <code><a href="#ndefrecord">NdefRecord</a></code> | 0.0.1 |


#### GetLanguageFromNdefTextRecordOptions

| Prop         | Type                                              | Since |
| ------------ | ------------------------------------------------- | ----- |
| **`record`** | <code><a href="#ndefrecord">NdefRecord</a></code> | 0.0.1 |


### Enums


#### TypeNameFormat

| Members           | Value          | Description                                                                                            | Since |
| ----------------- | -------------- | ------------------------------------------------------------------------------------------------------ | ----- |
| **`Empty`**       | <code>0</code> | An empty record with no type or payload.                                                               | 0.0.1 |
| **`WellKnown`**   | <code>1</code> | A predefined type defined in the RTD specification of the NFC Forum.                                   | 0.0.1 |
| **`MimeMedia`**   | <code>2</code> | An Internet media type as defined in RFC 2046.                                                         | 0.0.1 |
| **`AbsoluteUri`** | <code>3</code> | A URI as defined in RFC 3986.                                                                          | 0.0.1 |
| **`External`**    | <code>4</code> | A user-defined value that is based on the rules of the NFC Forum Record Type Definition specification. | 0.0.1 |
| **`Unknown`**     | <code>5</code> | Type is unknown.                                                                                       | 0.0.1 |
| **`Unchanged`**   | <code>6</code> | Indicates the payload is an intermediate or final chunk of a chunked NDEF Record.                      | 0.0.1 |


#### RecordTypeDefinition

| Members                  | Value                          | Since |
| ------------------------ | ------------------------------ | ----- |
| **`AndroidApp`**         | <code>'android.com:pkg'</code> | 0.0.1 |
| **`AlternativeCarrier`** | <code>'ac'</code>              | 0.0.1 |
| **`HandoverCarrier`**    | <code>'Hc'</code>              | 0.0.1 |
| **`HandoverRequest`**    | <code>'Hr'</code>              | 0.0.1 |
| **`HandoverSelect`**     | <code>'Hs'</code>              | 0.0.1 |
| **`SmartPoster`**        | <code>'Sp'</code>              | 0.0.1 |
| **`Text`**               | <code>'T'</code>               | 0.0.1 |
| **`Uri`**                | <code>'U'</code>               | 0.0.1 |

</docgen-api>
