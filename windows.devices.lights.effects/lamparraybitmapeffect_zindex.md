---
-api-id: P:Windows.Devices.Lights.Effects.LampArrayBitmapEffect.ZIndex
-api-type: winrt property
---

<!-- Property syntax.
public int ZIndex { get;  set; }
-->

# Windows.Devices.Lights.Effects.LampArrayBitmapEffect.ZIndex

## -description
Gets or sets the global precedence (across all playlists) for two effects that modify the same lamp (on the same [LampArray](../windows.devices.lights/lamparray.md)).

## -property-value
Default value is 0.

## -remarks
Higher zIndex implies higher precedence.

If two effects with the same zIndex operate on the same lamp (via two seperate [LampArrayEffectPlaylists](lamparrayeffectplaylist.md)), the behavior is undefined.

Once the effect has been [Appended](lamparrayeffectplaylist_append_292269384.md) to a [LampArrayEffectPlaylist](lamparrayeffectplaylist.md), the value is locked and is no longer possible to set the value.

## -see-also

## -examples

