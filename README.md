<p align="center"><br><img src="https://avatars.githubusercontent.com/u/105555861" width="128" height="128" /></p>
<h3 align="center">NFC</h3>
<p align="center"><strong><code>@capawesome-team/capacitor-nfc</code></strong></p>
<p align="center">
  Capacitor plugin for reading and writing NFC tags.
</p>

<p align="center">
  <img src="https://img.shields.io/maintenance/yes/2022?style=flat-square" />
  <!-- <a href="https://github.com/capawesome-team/capacitor-nfc/actions?query=workflow%3A%22CI%22"><img src="https://img.shields.io/github/workflow/status/capawesome-team/capacitor-nfc/CI/main?style=flat-square" /></a> -->
  <a href="https://github.com/capawesome-team/capacitor-nfc"><img src="https://img.shields.io/github/license/capawesome-team/capacitor-nfc?style=flat-square" /></a>
<!-- <br> -->
  <!-- <a href="https://www.npmjs.com/package/@capawesome/capacitor-nfc"><img src="https://img.shields.io/npm/dw/@capawesome/capacitor-nfc?style=flat-square" /></a>
  <a href="https://www.npmjs.com/package/@capawesome/capacitor-nfc"><img src="https://img.shields.io/npm/v/@capawesome/capacitor-nfc?style=flat-square" /></a> -->
  <a href="https://github.com/capawesome-team"><img src="https://img.shields.io/badge/part%20of-capawesome-%234f46e5?style=flat-square" /></a>
</p>

## Maintainers

| Maintainer | GitHub                                    | Social                                        |
| ---------- | ----------------------------------------- | --------------------------------------------- |
| Robin Genz | [robingenz](https://github.com/robingenz) | [@robin_genz](https://twitter.com/robin_genz) |

## Sponsors

This is an MIT-licensed open source project.
It can grow thanks to the support by these awesome people.
If you'd like to join them, please read more [here](https://github.com/sponsors/capawesome-team).

### Base Sponsor

<a href="https://nfc21.de/?_locale=en&utm_source=github&utm_medium=referral&utm_campaign=capawesome">
<p align="center"><br><img src="https://user-images.githubusercontent.com/13857929/184146236-f1e6140c-2e31-434c-8859-c782ac8c283c.png" width="125" height="84" /></p>
<h4 align="center">NFC21 - NFC Tag Shop and Service Provider</h4>
</a>

<!-- sponsors --><!-- sponsors -->

## Sponsorware

This project is available as **Sponsorware**.

> Sponsorware is a release strategy for open-source software that enables developers to be compensated for their open-source work with fewer downsides than traditional open-source funding models. ([Source](https://github.com/sponsorware/docs))

This means...

- The source code will be published as soon as [our GitHub Sponsors goal](https://github.com/sponsors/capawesome-team) is reached.
- Any GitHub sponsor with a [sponsorware tier](https://github.com/sponsors/capawesome-team?frequency=recurring) gets **immediate access** to our sponsors-only repository and can start using the project right away.

## Terms

This project is licensed under the terms of the MIT license.  
However, we kindly ask you to respect our **fair use policy**:

- Please **don't distribute the source code** of the sponsors-only repository. You may freely use it for public, private or commercial projects, privately fork or mirror it, but please don't make the source code public, as it would counteract the sponsorware strategy.
- If you cancel your subscription, you're automatically removed as a collaborator and will miss out on all future updates. However, **you may use the latest version that's available to you as long as you like**.

## Demo

A working example can be found here: [capawesome-team/capacitor-nfc-demo](https://github.com/capawesome-team/capacitor-nfc-demo)

| Android                                                                                                                         | iOS                                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://user-images.githubusercontent.com/13857929/184409092-7fdc3a77-67b1-4155-b1b1-0fd34a92a77b.gif" width="324" /> | <img src="https://user-images.githubusercontent.com/13857929/184409000-a81243a3-93e5-4d51-817a-e006c0a385cf.gif" width="266" /> |

## Roadmap

This plugin is still **under development**. We have already received many feature requests. This is our approximate roadmap:

| Q3 2022                     | Q4 2022                |
| --------------------------- | ---------------------- |
| - Capacitor 4 compatibility | - Android Reader Mode  |
|                             | - [Raw commands support](https://github.com/capawesome-team/capacitor-nfc/issues/6) |

⚠️ **Disclaimer**: This roadmap does not represent a commitment, guarantee, obligation or promise to deliver any product or feature, or to deliver any product and feature by any particular date, and is intended to outline the general development plans. You should not rely on this roadmap to make any sponsorship decision.

## FAQ

1. **Which platforms are supported?**  
   This plugin supports Android 5+, iOS 13+ and Web (see [Browser compatibility](https://developer.mozilla.org/en-US/docs/Web/API/Web_NFC_API#browser_compatibility)). But not all platforms and devices support all technologies. You can read more about this in the plugin documentation.
1. **Which Capacitor versions are supported?**  
   There is a version for Capacitor 3 and Capacitor 4. However, new updates are only ever provided for the latest Capacitor major version (currently Capacitor 4).
1. **What do I do when I have a feature request?**  
   This always depends on your device and the specific tag. The easiest way to find out is to download our demo app and give it a try.
1. **What do I do when I have a feature request?**  
   Please submit your feature request [here](https://github.com/capawesome-team/capacitor-nfc/issues/new/choose). We will then review it and possibly put it on our roadmap.
1. **What do I do when I have found a bug?**  
   Bug reports have top priority. Please submit your bug report [here](https://github.com/capawesome-team/capacitor-nfc/issues/new/choose). We will take a look at it as soon as possible.

## Installation

As long as the project is available as [Sponsorware](#sponsorware), the project will be distributed via GitHub packages.

1. Log in to GitHub package registry ([GitHub Docs](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#authenticating-to-github-packages)):

   ```
   $ npm login --scope=@capawesome-team --registry=https://npm.pkg.github.com

   > Username: USERNAME
   > Password: TOKEN
   > Email: PUBLIC-EMAIL-ADDRESS
   ```

1. In the same directory as your `package.json` file, create or edit an `.npmrc` file to include the following line ([GitHub Docs](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#installing-a-package)):
   ```
   @capawesome-team:registry=https://npm.pkg.github.com
   ```
1. Install the package with **Capacitor 3**:

   ```bash
   npm install @capawesome-team/capacitor-nfc@0.0.1
   npx cap sync
   ```

   Install the package with **Capacitor 4**:

   ```bash
   npm install @capawesome-team/capacitor-nfc
   npx cap sync
   ```

   🆘 If you have any problems please [contact us by mail](mailto:support@capawesome.io) or [create a GitHub discussion](https://docs.github.com/en/discussions/quickstart#creating-a-new-discussion) in this repository.  
   ⚠️ **Attention**: Be careful not to disclose your npm auth token! If you have any questions (CI configuration etc.) please let us know.

### Android

This API requires the following permissions be added to your `AndroidManifest.xml` before the `application` tag:

```xml
<!-- To get access to the NFC hardware. -->
<uses-permission android:name="android.permission.NFC" />
<!-- The minimum SDK version that your application can support. -->
<uses-sdk android:minSdkVersion="10"/>
<!-- (Optional) This will ensure that your app appears in Google Play only for devices with NFC hardware. -->
<uses-feature android:name="android.hardware.nfc" android:required="true" />
```

If you want to launch your app through an NFC tag, please take a look at the [Android documentation](https://developer.android.com/guide/topics/connectivity/nfc/nfc#dispatching).
There you will find which changes you have to apply to your `AndroidManifest.xml` ([example](https://developer.android.com/guide/topics/connectivity/nfc/nfc#ndef-disc)).

### iOS

Ensure `Near Field Communication Tag Reading` capabilities have been enabled in your application in Xcode.
See [Add a capability to a target](https://help.apple.com/xcode/mac/current/#/dev88ff319e7) for more information.

Finally, add the `NFCReaderUsageDescription` key to the `ios/App/App/Info.plist` file, which tells the user why the app needs to use NFC:

```diff
+ <key>NFCReaderUsageDescription</key>
+ <string>The app enables the reading and writing of various NFC tags.</string>
```

If you want to launch your app through an NFC tag, please take a look at the [Core NFC documentation](https://developer.apple.com/documentation/corenfc/adding_support_for_background_tag_reading#3032598).
The NFC tag requires a [URI record](https://w3c.github.io/web-nfc/#uri-record) (see [`createNdefUriRecord(...)`](https://github.com/capawesome-team/capacitor-nfc/tree/main/docs/utils#createndefurirecord)) that must contain either a universal link (see [Deep Linking with Universal and App Links](https://capacitorjs.com/docs/guides/deep-links)) or a [supported URL scheme](https://developer.apple.com/documentation/corenfc/adding_support_for_background_tag_reading#3032600).

## Configuration

No configuration required for this plugin.

## Usage

```typescript
import { Nfc, NfcUtils, NfcTagTechType } from '@capawesome-team/capacitor-nfc';

const createNdefTextRecord = async () => {
  const utils = new NfcUtils();
  const { record } = utils.createNdefTextRecord({ text: 'Capacitor NFC Plugin' });
  return record;
};

const write = async () => {
  const record = createNdefTextRecord();

  Nfc.addListener('nfcTagScanned', async (event) => {
    await Nfc.write({ message: { records: [record] } });
  });

  await Nfc.startScanSession();
};

const read = async () => {
  return new Promise((resolve) => {
    Nfc.addListener('nfcTagScanned', async (event) => {
      resolve(event.nfcTag);
    });

    Nfc.startScanSession();
  });
};

const makeReadOnly = async () => {
  const record = createNdefTextRecord();

  Nfc.addListener('nfcTagScanned', async (event) => {
    await Nfc.makeReadOnly();
  });

  await Nfc.startScanSession();
};

const isSupported = async () => {
  const { isSupported } = await Nfc.isSupported();
  return isSupported;
};

const isEnabled = async () => {
  const { isEnabled } = await Nfc.isEnabled();
  return isEnabled;
};

const openSettings = async () => {
  await Nfc.openSettings();
};

const checkPermissions = async () => {
  const { nfc } = await Nfc.checkPermissions();
  return nfc;
};

const requestPermissions = async () => {
  const { nfc } = await Nfc.requestPermissions();
  return nfc;
};

const removeAllListeners = async () => {
  await Nfc.removeAllListeners();
};

const readSignature = async () => {
  Nfc.addListener('nfcTagScanned', async (event) => {
    const { response } = await Nfc.transceive({ techType: NfcTagTechType.NfcA, data: [60, 0] });
    return response;
  });

  await Nfc.startScanSession();
};
```

## API

<docgen-index>

* [`startScanSession(...)`](#startscansession)
* [`stopScanSession(...)`](#stopscansession)
* [`write(...)`](#write)
* [`makeReadOnly()`](#makereadonly)
* [`transceive(...)`](#transceive)
* [`isSupported()`](#issupported)
* [`isEnabled()`](#isenabled)
* [`openSettings()`](#opensettings)
* [`checkPermissions()`](#checkpermissions)
* [`requestPermissions()`](#requestpermissions)
* [`addListener('nfcTagScanned', ...)`](#addlistenernfctagscanned-)
* [`addListener('scanSessionCanceled', ...)`](#addlistenerscansessioncanceled-)
* [`addListener('scanSessionError', ...)`](#addlistenerscansessionerror-)
* [`removeAllListeners()`](#removealllisteners)
* [Interfaces](#interfaces)
* [Type Aliases](#type-aliases)
* [Enums](#enums)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### startScanSession(...)

```typescript
startScanSession(options?: StartScanSessionOptions | undefined) => Promise<void>
```

Starts a scan session.
Only one session can be active at a time.

On iOS, this will trigger the NFC Reader Session alert.

| Param         | Type                                                                        |
| ------------- | --------------------------------------------------------------------------- |
| **`options`** | <code><a href="#startscansessionoptions">StartScanSessionOptions</a></code> |

**Since:** 0.0.1

--------------------


### stopScanSession(...)

```typescript
stopScanSession(options?: StopScanSessionOptions | undefined) => Promise<void>
```

Stops the active scan session.

| Param         | Type                                                                      |
| ------------- | ------------------------------------------------------------------------- |
| **`options`** | <code><a href="#stopscansessionoptions">StopScanSessionOptions</a></code> |

**Since:** 0.0.1

--------------------


### write(...)

```typescript
write(options: WriteOptions) => Promise<void>
```

Writes to a NFC tag.

This method must be called from within a `nfcTagScanned` handler.

| Param         | Type                                                  |
| ------------- | ----------------------------------------------------- |
| **`options`** | <code><a href="#writeoptions">WriteOptions</a></code> |

**Since:** 0.0.1

--------------------


### makeReadOnly()

```typescript
makeReadOnly() => Promise<void>
```

Makes a NFC tag readonly.

This method must be called from within a `nfcTagScanned` handler.

**Attention:** This is permanent and can not be undone.

**Since:** 0.0.1

--------------------


### transceive(...)

```typescript
transceive(options: TransceiveOptions) => Promise<TransceiveResult>
```

Send raw command to the tag and receive the response.

This method must be called from within a `nfcTagScanned` handler.

⚠️ **Experimental:** This method could not be tested extensively yet. Please let us know if you discover any issues!

⚠️ **Attention**: A bad command can damage the tag forever. Please read the Android and iOS documentation linked below first.

More information on how to use this method on Android: https://developer.android.com/reference/android/nfc/tech/package-summary
More information on how to use this method on iOS with...
- ISO 15693-3: https://developer.apple.com/documentation/corenfc/nfciso15693tag/3043799-customcommand
- FeliCa: https://developer.apple.com/documentation/corenfc/nfcfelicatag/3043786-sendfelicacommand

Only available on Android and iOS.

| Param         | Type                                                            |
| ------------- | --------------------------------------------------------------- |
| **`options`** | <code><a href="#transceiveoptions">TransceiveOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#transceiveresult">TransceiveResult</a>&gt;</code>

**Since:** 0.3.0

--------------------


### isSupported()

```typescript
isSupported() => Promise<IsSupportedResult>
```

Returns whether or not NFC is supported.

**Returns:** <code>Promise&lt;<a href="#issupportedresult">IsSupportedResult</a>&gt;</code>

**Since:** 0.0.1

--------------------


### isEnabled()

```typescript
isEnabled() => Promise<IsEnabledResult>
```

Returns whether or not NFC is enabled.

Only available on Android.

**Returns:** <code>Promise&lt;<a href="#isenabledresult">IsEnabledResult</a>&gt;</code>

**Since:** 0.0.1

--------------------


### openSettings()

```typescript
openSettings() => Promise<void>
```

Opens the NFC device settings so that the user can enable or disable NFC.

Only available on Android.

**Since:** 0.0.1

--------------------


### checkPermissions()

```typescript
checkPermissions() => Promise<PermissionResult>
```

Check permission for reading and writing NFC tags.

This method is only needed on Web.
On Android and iOS, `granted` is always returned.

**Returns:** <code>Promise&lt;<a href="#permissionresult">PermissionResult</a>&gt;</code>

**Since:** 0.0.1

--------------------


### requestPermissions()

```typescript
requestPermissions() => Promise<PermissionResult>
```

Request permission for reading and writing NFC tags.

This method is only needed on Web.
On Android and iOS, `granted` is always returned.

**Returns:** <code>Promise&lt;<a href="#permissionresult">PermissionResult</a>&gt;</code>

**Since:** 0.0.1

--------------------


### addListener('nfcTagScanned', ...)

```typescript
addListener(eventName: 'nfcTagScanned', listenerFunc: (event: NfcTagScannedEvent) => void) => Promise<PluginListenerHandle> & PluginListenerHandle
```

Called when a new NFC tag is scanned.

| Param              | Type                                                                                  |
| ------------------ | ------------------------------------------------------------------------------------- |
| **`eventName`**    | <code>'nfcTagScanned'</code>                                                          |
| **`listenerFunc`** | <code>(event: <a href="#nfctagscannedevent">NfcTagScannedEvent</a>) =&gt; void</code> |

**Returns:** <code>Promise&lt;<a href="#pluginlistenerhandle">PluginListenerHandle</a>&gt; & <a href="#pluginlistenerhandle">PluginListenerHandle</a></code>

**Since:** 0.0.1

--------------------


### addListener('scanSessionCanceled', ...)

```typescript
addListener(eventName: 'scanSessionCanceled', listenerFunc: () => void) => Promise<PluginListenerHandle> & PluginListenerHandle
```

Called when the scan session was canceled.

Only available on iOS.

| Param              | Type                               |
| ------------------ | ---------------------------------- |
| **`eventName`**    | <code>'scanSessionCanceled'</code> |
| **`listenerFunc`** | <code>() =&gt; void</code>         |

**Returns:** <code>Promise&lt;<a href="#pluginlistenerhandle">PluginListenerHandle</a>&gt; & <a href="#pluginlistenerhandle">PluginListenerHandle</a></code>

**Since:** 0.0.1

--------------------


### addListener('scanSessionError', ...)

```typescript
addListener(eventName: 'scanSessionError', listenerFunc: (event: ScanSessionErrorEvent) => void) => Promise<PluginListenerHandle> & PluginListenerHandle
```

Called when an error occurs during the scan session.

| Param              | Type                                                                                        |
| ------------------ | ------------------------------------------------------------------------------------------- |
| **`eventName`**    | <code>'scanSessionError'</code>                                                             |
| **`listenerFunc`** | <code>(event: <a href="#scansessionerrorevent">ScanSessionErrorEvent</a>) =&gt; void</code> |

**Returns:** <code>Promise&lt;<a href="#pluginlistenerhandle">PluginListenerHandle</a>&gt; & <a href="#pluginlistenerhandle">PluginListenerHandle</a></code>

**Since:** 0.0.1

--------------------


### removeAllListeners()

```typescript
removeAllListeners() => Promise<void>
```

Remove all listeners for this plugin.

**Since:** 0.0.1

--------------------


### Interfaces


#### StartScanSessionOptions

| Prop                 | Type                          | Description                                                                                  | Default                                                       | Since |
| -------------------- | ----------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | ----- |
| **`alertMessage`**   | <code>string</code>           | A custom message, which is displayed in the NFC Reader Session alert. Only available on iOS. |                                                               | 0.0.1 |
| **`techTypes`**      | <code>NfcTagTechType[]</code> | The NFC tag technologies to filter on in this session. Only available on Android.            |                                                               | 0.0.1 |
| **`mimeTypes`**      | <code>string[]</code>         | Mime types to filter on in this session. Only available on Android.                          |                                                               | 0.0.1 |
| **`pollingOptions`** | <code>PollingOption[]</code>  | Type of tags to detect during a polling sequence. Only available on iOS.                     | <code>[PollingOption.iso14443, PollingOption.iso15693]</code> | 0.2.0 |


#### StopScanSessionOptions

| Prop               | Type                | Description                                                                                        | Since |
| ------------------ | ------------------- | -------------------------------------------------------------------------------------------------- | ----- |
| **`errorMessage`** | <code>string</code> | A custom error message, which is displayed in the NFC Reader Session alert. Only available on iOS. | 0.0.1 |


#### WriteOptions

| Prop          | Type                                                | Description                | Since |
| ------------- | --------------------------------------------------- | -------------------------- | ----- |
| **`message`** | <code><a href="#ndefmessage">NdefMessage</a></code> | The NDEF message to write. | 0.0.1 |


#### NdefMessage

| Prop          | Type                      | Description                      | Since |
| ------------- | ------------------------- | -------------------------------- | ----- |
| **`records`** | <code>NdefRecord[]</code> | The records of the NDEF message. | 0.0.1 |


#### NdefRecord

| Prop          | Type                                                      | Description                                                                                                              | Since |
| ------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ----- |
| **`id`**      | <code>number[]</code>                                     | The record identifier as byte array.                                                                                     | 0.0.1 |
| **`payload`** | <code>number[]</code>                                     | The payload field data as byte array.                                                                                    | 0.0.1 |
| **`tnf`**     | <code><a href="#typenameformat">TypeNameFormat</a></code> | The record type name format which indicates the structure of the value of the `type` field.                              | 0.0.1 |
| **`type`**    | <code>number[]</code>                                     | The type of the record payload. This should be used in conjunction with the `tnf` field to determine the payload format. | 0.0.1 |


#### TransceiveResult

| Prop           | Type                  | Description                 | Since |
| -------------- | --------------------- | --------------------------- | ----- |
| **`response`** | <code>number[]</code> | Bytes received in response. | 0.3.0 |


#### TransceiveOptions

| Prop                       | Type                                                      | Description                                                                                                                                                                     | Since |
| -------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| **`techType`**             | <code><a href="#nfctagtechtype">NfcTagTechType</a></code> | The NFC tag technology to connect with. On iOS, only <a href="#nfctagtechtype">`NfcTagTechType.NfcF`</a> and <a href="#nfctagtechtype">`NfcTagTechType.NfcV`</a> are supported. | 0.3.0 |
| **`data`**                 | <code>number[]</code>                                     | Bytes to send.                                                                                                                                                                  | 0.3.0 |
| **`iso15693RequestFlags`** | <code>Iso15693RequestFlag[]</code>                        | The request flags for the NFC tag technology type `NfcV` (ISO 15693-3). Only available on iOS 14+                                                                               | 0.3.0 |
| **`iso15693CommandCode`**  | <code>number</code>                                       | The custom command code defined by the IC manufacturer for the NFC tag technology type `NfcV` (ISO 15693-3). Valid range is 0xA0 to 0xDF inclusively. Only available on iOS 14+ | 0.3.0 |


#### IsSupportedResult

| Prop              | Type                 | Since |
| ----------------- | -------------------- | ----- |
| **`isSupported`** | <code>boolean</code> | 0.0.1 |


#### IsEnabledResult

| Prop            | Type                 | Since |
| --------------- | -------------------- | ----- |
| **`isEnabled`** | <code>boolean</code> | 0.0.1 |


#### PermissionResult

| Prop      | Type                                                        | Description                                        | Since |
| --------- | ----------------------------------------------------------- | -------------------------------------------------- | ----- |
| **`nfc`** | <code><a href="#permissionstate">PermissionState</a></code> | Permission state for reading and writing NFC tags. | 0.0.1 |


#### PluginListenerHandle

| Prop         | Type                                      |
| ------------ | ----------------------------------------- |
| **`remove`** | <code>() =&gt; Promise&lt;void&gt;</code> |


#### NfcTagScannedEvent

| Prop         | Type                                      | Description          | Since |
| ------------ | ----------------------------------------- | -------------------- | ----- |
| **`nfcTag`** | <code><a href="#nfctag">NfcTag</a></code> | The scanned NFC tag. | 0.0.1 |


#### NfcTag

| Prop                  | Type                                                | Description                                                                                        | Since |
| --------------------- | --------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ----- |
| **`atqa`**            | <code>number[]</code>                               | The ATQA/SENS_RES bytes of an NFC A tag. Only available on Android.                                | 0.0.1 |
| **`applicationData`** | <code>number[]</code>                               | The Application Data bytes from ATQB/SENSB_RES of an NFC B tag. Only available on Android and iOS. | 0.0.1 |
| **`barcode`**         | <code>number[]</code>                               | The barcode bytes of an NfcBarcode tag. Only available on Android.                                 | 0.0.1 |
| **`canMakeReadOnly`** | <code>boolean</code>                                | Whether the NDEF tag can be made read-only or not. Only available on Android.                      | 0.0.1 |
| **`dsfId`**           | <code>number[]</code>                               | The DSF ID bytes of an NFC V tag. Only available on Android.                                       | 0.0.1 |
| **`hiLayerResponse`** | <code>number[]</code>                               | The higher layer response bytes of an ISO-DEP tag. Only available on Android.                      | 0.0.1 |
| **`historicalBytes`** | <code>number[]</code>                               | The historical bytes of an ISO-DEP tag. Only available on Android and iOS.                         | 0.0.1 |
| **`id`**              | <code>number[]</code>                               | The tag identifier (low level serial number) which is used for anti-collision and identification.  | 0.0.1 |
| **`isWritable`**      | <code>boolean</code>                                | Whether the NDEF tag is writable or not. Only available on Android and iOS.                        | 0.0.1 |
| **`manufacturer`**    | <code>number[]</code>                               | The Manufacturer bytes of an NFC F tag. Only available on Android and iOS.                         | 0.0.1 |
| **`maxSize`**         | <code>number</code>                                 | The maximum NDEF message size in bytes. Only available on Android and iOS.                         | 0.0.1 |
| **`message`**         | <code><a href="#ndefmessage">NdefMessage</a></code> | The NDEF-formatted message.                                                                        | 0.0.1 |
| **`protocolInfo`**    | <code>number[]</code>                               | The Protocol Info bytes from ATQB/SENSB_RES of an NFC B tag. Only available on Android.            | 0.0.1 |
| **`responseFlags`**   | <code>number[]</code>                               | The Response Flag bytes of an NFC V tag. Only available on Android.                                | 0.0.1 |
| **`sak`**             | <code>number[]</code>                               | The SAK/SEL_RES bytes of an NFC A tag. Only available on Android.                                  | 0.0.1 |
| **`systemCode`**      | <code>number[]</code>                               | The System Code bytes of an NFC F tag. Only available on Android and iOS.                          | 0.0.1 |
| **`techTypes`**       | <code>NfcTagTechType[]</code>                       | The technologies available in this tag. Only available on Android and iOS.                         | 0.0.1 |
| **`type`**            | <code><a href="#nfctagtype">NfcTagType</a></code>   | The NDEF tag type. Only available on Android and iOS.                                              | 0.0.1 |


#### ScanSessionErrorEvent

| Prop          | Type                | Description        | Since |
| ------------- | ------------------- | ------------------ | ----- |
| **`message`** | <code>string</code> | The error message. | 0.0.1 |


### Type Aliases


#### PermissionState

<code>"denied" | "granted" | "prompt"</code>


### Enums


#### NfcTagTechType

| Members                | Value                            | Since |
| ---------------------- | -------------------------------- | ----- |
| **`NfcA`**             | <code>'NFC_A'</code>             | 0.0.1 |
| **`NfcB`**             | <code>'NFC_B'</code>             | 0.0.1 |
| **`NfcF`**             | <code>'NFC_F'</code>             | 0.0.1 |
| **`NfcV`**             | <code>'NFC_V'</code>             | 0.0.1 |
| **`IsoDep`**           | <code>'ISO_DEP'</code>           | 0.0.1 |
| **`Ndef`**             | <code>'NDEF'</code>              | 0.0.1 |
| **`MifareClassic`**    | <code>'MIFARE_CLASSIC'</code>    | 0.0.1 |
| **`MifareUltralight`** | <code>'MIFARE_ULTRALIGHT'</code> | 0.0.1 |
| **`NfcBarcode`**       | <code>'NFC_BARCODE'</code>       | 0.0.1 |
| **`NdefFormatable`**   | <code>'NDEF_FORMATABLE'</code>   | 0.0.1 |


#### PollingOption

| Members        | Value                   | Description                                                   | Since |
| -------------- | ----------------------- | ------------------------------------------------------------- | ----- |
| **`iso14443`** | <code>'iso14443'</code> | The option for detecting ISO 7816-compatible and MIFARE tags. | 0.2.0 |
| **`iso15693`** | <code>'iso15693'</code> | The option for detecting ISO 15693 tags.                      | 0.2.0 |
| **`iso18092`** | <code>'iso18092'</code> | The option for detecting FeliCa tags.                         | 0.2.0 |


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


#### Iso15693RequestFlag

| Members                   | Value                              | Since |
| ------------------------- | ---------------------------------- | ----- |
| **`address`**             | <code>'address'</code>             | 0.3.0 |
| **`commandSpecificBit8`** | <code>'commandSpecificBit8'</code> | 0.3.0 |
| **`dualSubCarriers`**     | <code>'dualSubCarriers'</code>     | 0.3.0 |
| **`highDataRate`**        | <code>'highDataRate'</code>        | 0.3.0 |
| **`option`**              | <code>'option'</code>              | 0.3.0 |
| **`protocolExtension`**   | <code>'protocolExtension'</code>   | 0.3.0 |
| **`select`**              | <code>'select'</code>              | 0.3.0 |


#### NfcTagType

| Members                 | Value                              | Since |
| ----------------------- | ---------------------------------- | ----- |
| **`NfcForumType1`**     | <code>'NFC_FORUM_TYPE_1'</code>    | 0.0.1 |
| **`NfcForumType2`**     | <code>'NFC_FORUM_TYPE_2'</code>    | 0.0.1 |
| **`NfcForumType3`**     | <code>'NFC_FORUM_TYPE_3'</code>    | 0.0.1 |
| **`NfcForumType4`**     | <code>'NFC_FORUM_TYPE_4'</code>    | 0.0.1 |
| **`MifareClassic`**     | <code>'MIFARE_CLASSIC'</code>      | 0.0.1 |
| **`MifareDesfire`**     | <code>'MIFARE_DESFIRE'</code>      | 0.0.1 |
| **`MifarePlus`**        | <code>'MIFARE_PLUS'</code>         | 0.0.1 |
| **`MifarePro`**         | <code>'MIFARE_PRO'</code>          | 0.0.1 |
| **`MifareUltralight`**  | <code>'MIFARE_ULTRALIGHT'</code>   | 0.0.1 |
| **`MifareUltralightC`** | <code>'MIFARE_ULTRALIGHT_C'</code> | 0.0.1 |

</docgen-api>

## Utils

See [docs/utils/README.md](/docs/utils/README.md).

## Changelog

See [CHANGELOG.md](/CHANGELOG.md).

## License

See [LICENSE](/LICENSE).
