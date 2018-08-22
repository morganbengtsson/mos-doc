# group `aud` {#group__aud}

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Assets`](#group__aud_1ga66726a07d892045355a1ab7b31f637e5)`(const std::string directory)`            | 
`public  `[`Assets`](#group__aud_1ga789a9b3bb9699438b975291ee168593f)`(const Assets & audio_assets) = delete`            | 
`public  `[`~Assets`](#group__aud_1ga8b0ae781301dc352362a13a7d73f2b45)`()`            | 
`public SharedBuffer `[`audio_buffer`](#group__aud_1gad5631a6676c5e9445ed6a129ed24ed5a)`(const std::string & path)`            | Loads an *.ogg file into a buffer and caches it.
`public void `[`clear_unused`](#group__aud_1ga10b0b82191724041778acc509f296ff6)`()`            | Remove unused buffers.
`namespace `[`mos::aud`](#namespacemos_1_1aud) | 

## Members

#### `public  `[`Assets`](#group__aud_1ga66726a07d892045355a1ab7b31f637e5)`(const std::string directory)` {#group__aud_1ga66726a07d892045355a1ab7b31f637e5}

#### `public  `[`Assets`](#group__aud_1ga789a9b3bb9699438b975291ee168593f)`(const Assets & audio_assets) = delete` {#group__aud_1ga789a9b3bb9699438b975291ee168593f}

#### `public  `[`~Assets`](#group__aud_1ga8b0ae781301dc352362a13a7d73f2b45)`()` {#group__aud_1ga8b0ae781301dc352362a13a7d73f2b45}

#### `public SharedBuffer `[`audio_buffer`](#group__aud_1gad5631a6676c5e9445ed6a129ed24ed5a)`(const std::string & path)` {#group__aud_1gad5631a6676c5e9445ed6a129ed24ed5a}

Loads an *.ogg file into a buffer and caches it.

#### `public void `[`clear_unused`](#group__aud_1ga10b0b82191724041778acc509f296ff6)`()` {#group__aud_1ga10b0b82191724041778acc509f296ff6}

Remove unused buffers.

# namespace `mos::aud` {#namespacemos_1_1aud}

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`mos::aud::Assets`](api-aud.md#classmos_1_1aud_1_1Assets) | Handles heavy audio assets.

# class `mos::aud::Assets` {#classmos_1_1aud_1_1Assets}

Handles heavy audio assets.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Assets`](#group__aud_1ga66726a07d892045355a1ab7b31f637e5)`(const std::string directory)` | 
`public  `[`Assets`](#group__aud_1ga789a9b3bb9699438b975291ee168593f)`(const `[`Assets`](#classmos_1_1aud_1_1Assets)` & audio_assets) = delete` | 
`public  `[`~Assets`](#group__aud_1ga8b0ae781301dc352362a13a7d73f2b45)`()` | 
`public SharedBuffer `[`audio_buffer`](#group__aud_1gad5631a6676c5e9445ed6a129ed24ed5a)`(const std::string & path)` | Loads an *.ogg file into a buffer and caches it.
`public void `[`clear_unused`](#group__aud_1ga10b0b82191724041778acc509f296ff6)`()` | Remove unused buffers.
`typedef `[`BufferMap`](#group__aud_1ga23d5adc673bcdb6225cf65928519c18d) | 
`typedef `[`BufferPair`](#group__aud_1gae4093f0bf4f75b7aeefc13857a2204a4) | 

## Members

#### `public  `[`Assets`](#group__aud_1ga66726a07d892045355a1ab7b31f637e5)`(const std::string directory)` {#group__aud_1ga66726a07d892045355a1ab7b31f637e5}

#### `public  `[`Assets`](#group__aud_1ga789a9b3bb9699438b975291ee168593f)`(const `[`Assets`](#classmos_1_1aud_1_1Assets)` & audio_assets) = delete` {#group__aud_1ga789a9b3bb9699438b975291ee168593f}

#### `public  `[`~Assets`](#group__aud_1ga8b0ae781301dc352362a13a7d73f2b45)`()` {#group__aud_1ga8b0ae781301dc352362a13a7d73f2b45}

#### `public SharedBuffer `[`audio_buffer`](#group__aud_1gad5631a6676c5e9445ed6a129ed24ed5a)`(const std::string & path)` {#group__aud_1gad5631a6676c5e9445ed6a129ed24ed5a}

Loads an *.ogg file into a buffer and caches it.

#### `public void `[`clear_unused`](#group__aud_1ga10b0b82191724041778acc509f296ff6)`()` {#group__aud_1ga10b0b82191724041778acc509f296ff6}

Remove unused buffers.

#### `typedef `[`BufferMap`](#group__aud_1ga23d5adc673bcdb6225cf65928519c18d) {#group__aud_1ga23d5adc673bcdb6225cf65928519c18d}

#### `typedef `[`BufferPair`](#group__aud_1gae4093f0bf4f75b7aeefc13857a2204a4) {#group__aud_1gae4093f0bf4f75b7aeefc13857a2204a4}

