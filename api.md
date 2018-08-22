# Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`define `[`STB_IMAGE_IMPLEMENTATION`](#texture_8cpp_1a18372412ad2fc3ce1e3240b3cf0efe78)            | 
`namespace `[`mos`](#namespacemos) | 
`namespace `[`mos::aud`](#namespacemos_1_1aud) | 
`namespace `[`mos::exp`](#namespacemos_1_1exp) | 
`namespace `[`mos::gfx`](#namespacemos_1_1gfx) | 
`namespace `[`mos::gfx::exp`](#namespacemos_1_1gfx_1_1exp) | 
`namespace `[`mos::io`](#namespacemos_1_1io) | 
`namespace `[`mos::sim`](#namespacemos_1_1sim) | 
`class `[`mos::gfx::Renderer::EnvironmentProgram`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram) | Uniforms for the environment shader.
`class `[`mos::gfx::Renderer::Shader`](#classmos_1_1gfx_1_1Renderer_1_1Shader) | 
`class `[`mos::gfx::Renderer::StandardProgram`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram) | Uniforms for the standard shader.
`class `[`mos::gfx::Renderer::TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D) | 
`struct `[`mos::gfx::Renderer::BloomProgram`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram) | 
`struct `[`mos::gfx::Renderer::BlurProgram`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram) | 
`struct `[`mos::gfx::Renderer::BlurTarget`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget) | 
`struct `[`mos::gfx::Renderer::Box`](#structmos_1_1gfx_1_1Renderer_1_1Box) | 
`struct `[`mos::gfx::Renderer::BoxProgram`](#structmos_1_1gfx_1_1Renderer_1_1BoxProgram) | Uniforms for the bounding box shader program.
`struct `[`mos::gfx::Renderer::Buffer`](#structmos_1_1gfx_1_1Renderer_1_1Buffer) | 
`struct `[`mos::gfx::Renderer::DepthProgram`](#structmos_1_1gfx_1_1Renderer_1_1DepthProgram) | 
`struct `[`mos::gfx::Renderer::EnvironmentMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget) | 
`struct `[`mos::gfx::Renderer::EnvironmentProgram::EnvironmentUniforms`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms) | 
`struct `[`mos::gfx::Renderer::StandardProgram::EnvironmentUniforms`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms) | 
`struct `[`mos::gfx::Renderer::EnvironmentProgram::LightUniforms`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms) | 
`struct `[`mos::gfx::Renderer::StandardProgram::LightUniforms`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms) | 
`struct `[`mos::gfx::Renderer::MultisampleProgram`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram) | 
`struct `[`mos::gfx::Renderer::MultiTarget`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget) | 
`struct `[`mos::gfx::Renderer::ParticleProgram`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram) | Uniforms for the particle shader program.
`struct `[`mos::gfx::Renderer::Program`](#structmos_1_1gfx_1_1Renderer_1_1Program) | 
`struct `[`mos::gfx::Renderer::Quad`](#structmos_1_1gfx_1_1Renderer_1_1Quad) | 
`struct `[`mos::gfx::Renderer::RenderBuffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer) | 
`struct `[`mos::gfx::Renderer::ShadowMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget) | 
`struct `[`mos::gfx::Renderer::StandardTarget`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget) | 

## Members

#### `define `[`STB_IMAGE_IMPLEMENTATION`](#texture_8cpp_1a18372412ad2fc3ce1e3240b3cf0efe78) 

# namespace `mos` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public std::string `[`text`](#util_8hpp_1ae599c0a2a96e836433d0c37215ea55ae)`(const std::string path)`            | Load text from file.
`public std::vector< std::string > & `[`split`](#util_8hpp_1ac40ca495071775322bf246a9cd55603f)`(const std::string & s,char delim,std::vector< std::string > & elems)`            | 
`public std::vector< std::string > `[`split`](#util_8hpp_1aadb38b37e0fff416bbcfff6d793fea9e)`(const std::string & s,char delim)`            | 
`public glm::mat4 `[`jsonarray_to_mat4`](#util_8hpp_1a48fb6b30926fc9b40cb90cb2d7db3cde)`(const nlohmann::json & array)`            | 
`public glm::vec3 `[`jsonarray_to_vec3`](#util_8hpp_1a7ae4349e79f76225cd23fd8d13028db8)`(const nlohmann::json & array)`            | 
`public glm::vec3 `[`position`](#util_8hpp_1ad8d87bd7391f44069d1b433d17103fb1)`(const glm::mat4 & mat)`            | 
`public int `[`now_ms`](#util_8hpp_1ae1b9d517b0c3990061955ac95723b107)`()`            | 
`public `[`mos::sim::Ray`](#classmos_1_1sim_1_1Ray)` `[`un_project`](#util_8hpp_1ada7961800bc2cc2459e529038f333901)`(const glm::vec2 & position,const glm::mat4 & view,const glm::mat4 & projection,const glm::uvec2 & resolution)`            | 
`class `[`mos::Container`](#classmos_1_1Container) | [Container](#classmos_1_1Container).
`class `[`mos::TrackedContainer`](#classmos_1_1TrackedContainer) | [Container](#classmos_1_1Container) with modified time stamp.

## Members

#### `public std::string `[`text`](#util_8hpp_1ae599c0a2a96e836433d0c37215ea55ae)`(const std::string path)` 

Load text from file.

#### Parameters
* `path` Full path. 

#### Returns
String with all content.

#### `public std::vector< std::string > & `[`split`](#util_8hpp_1ac40ca495071775322bf246a9cd55603f)`(const std::string & s,char delim,std::vector< std::string > & elems)` 

#### `public std::vector< std::string > `[`split`](#util_8hpp_1aadb38b37e0fff416bbcfff6d793fea9e)`(const std::string & s,char delim)` 

#### `public glm::mat4 `[`jsonarray_to_mat4`](#util_8hpp_1a48fb6b30926fc9b40cb90cb2d7db3cde)`(const nlohmann::json & array)` 

#### `public glm::vec3 `[`jsonarray_to_vec3`](#util_8hpp_1a7ae4349e79f76225cd23fd8d13028db8)`(const nlohmann::json & array)` 

#### `public glm::vec3 `[`position`](#util_8hpp_1ad8d87bd7391f44069d1b433d17103fb1)`(const glm::mat4 & mat)` 

#### `public int `[`now_ms`](#util_8hpp_1ae1b9d517b0c3990061955ac95723b107)`()` 

#### `public `[`mos::sim::Ray`](#classmos_1_1sim_1_1Ray)` `[`un_project`](#util_8hpp_1ada7961800bc2cc2459e529038f333901)`(const glm::vec2 & position,const glm::mat4 & view,const glm::mat4 & projection,const glm::uvec2 & resolution)` 

# class `mos::Container` 

[Container](#classmos_1_1Container).

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Container`](#classmos_1_1Container_1abbdc048864e8797a6d4092384e685353)`() = default` | 
`public template<>`  <br/>`inline  `[`Container`](#classmos_1_1Container_1ad6d10a9ae434ecab4dd55af0c87194da)`(const std::initializer_list< It > list)` | 
`public template<>`  <br/>`inline  `[`Container`](#classmos_1_1Container_1a8321a2e8286e8d68187ebbe3dc6c9a64)`(It begin,It end)` | 
`public inline  `[`Container`](#classmos_1_1Container_1ad377eef4d5691ee1d40dd467c6728fd8)`(const `[`TrackedContainer`](#classmos_1_1TrackedContainer)`< T > & container)` | 
`public template<>`  <br/>`inline void `[`assign`](#classmos_1_1Container_1a5865789de0167a9dc644f8d2b8ecd112)`(It begin,It end)` | 
`public template<>`  <br/>`inline Items::iterator `[`insert`](#classmos_1_1Container_1ae4bc5ea36a8fd113789006414588753d)`(typename Items::const_iterator pos,It begin,It end)` | 
`public inline Items::iterator `[`begin`](#classmos_1_1Container_1ab0a693af6c7af86f0ce6240847c03c25)`()` | 
`public inline Items::iterator `[`end`](#classmos_1_1Container_1a1c37e0a5d34aee0b8ce333104981f334)`()` | 
`public inline Items::const_iterator `[`begin`](#classmos_1_1Container_1a106a49455b2de03e6e2b352cd838d39a)`() const` | 
`public inline Items::const_iterator `[`end`](#classmos_1_1Container_1a1e1a5249b67efdd30aa33c921729a425)`() const` | 
`public inline void `[`assign`](#classmos_1_1Container_1a3688a44bb526491f5e98ee9b7770f8e2)`(const std::initializer_list< T > & list)` | 
`public inline Items::reference `[`operator[]`](#classmos_1_1Container_1af4e95626acb02183946adbca0d8e20e8)`(typename Items::size_type pos)` | 
`public inline Items::const_reference `[`operator[]`](#classmos_1_1Container_1a66c8ddaba3b1c6a54293e146bc79106b)`(typename Items::size_type pos) const` | 
`public inline Items::size_type `[`size`](#classmos_1_1Container_1a032bed1ba9db555e79b4cfcd4dfa26cb)`() const` | 
`public inline Items::reference `[`back`](#classmos_1_1Container_1a4414942ee2ce56bd637808e177fa200f)`()` | 
`public inline const T * `[`data`](#classmos_1_1Container_1ac06512422674bc2e7c79db68c1f4f841)`() const noexcept` | 
`public inline void `[`clear`](#classmos_1_1Container_1ab33be9c65987bd003b5995270aa26be0)`()` | 
`public inline void `[`push_back`](#classmos_1_1Container_1a4f32a1e3191351f36f72e5fd49595515)`(const T & item)` | 
`public inline void `[`append`](#classmos_1_1Container_1af773d4a1b0f69e96ea2b19825eb41160)`(const `[`Container`](#classmos_1_1Container)`< T > & container)` | 
`typedef `[`Items`](#classmos_1_1Container_1abe0c4a5442787c742862dda4382dfca4) | 

## Members

#### `public  `[`Container`](#classmos_1_1Container_1abbdc048864e8797a6d4092384e685353)`() = default` 

#### `public template<>`  <br/>`inline  `[`Container`](#classmos_1_1Container_1ad6d10a9ae434ecab4dd55af0c87194da)`(const std::initializer_list< It > list)` 

#### `public template<>`  <br/>`inline  `[`Container`](#classmos_1_1Container_1a8321a2e8286e8d68187ebbe3dc6c9a64)`(It begin,It end)` 

#### `public inline  `[`Container`](#classmos_1_1Container_1ad377eef4d5691ee1d40dd467c6728fd8)`(const `[`TrackedContainer`](#classmos_1_1TrackedContainer)`< T > & container)` 

#### `public template<>`  <br/>`inline void `[`assign`](#classmos_1_1Container_1a5865789de0167a9dc644f8d2b8ecd112)`(It begin,It end)` 

#### `public template<>`  <br/>`inline Items::iterator `[`insert`](#classmos_1_1Container_1ae4bc5ea36a8fd113789006414588753d)`(typename Items::const_iterator pos,It begin,It end)` 

#### `public inline Items::iterator `[`begin`](#classmos_1_1Container_1ab0a693af6c7af86f0ce6240847c03c25)`()` 

#### `public inline Items::iterator `[`end`](#classmos_1_1Container_1a1c37e0a5d34aee0b8ce333104981f334)`()` 

#### `public inline Items::const_iterator `[`begin`](#classmos_1_1Container_1a106a49455b2de03e6e2b352cd838d39a)`() const` 

#### `public inline Items::const_iterator `[`end`](#classmos_1_1Container_1a1e1a5249b67efdd30aa33c921729a425)`() const` 

#### `public inline void `[`assign`](#classmos_1_1Container_1a3688a44bb526491f5e98ee9b7770f8e2)`(const std::initializer_list< T > & list)` 

#### `public inline Items::reference `[`operator[]`](#classmos_1_1Container_1af4e95626acb02183946adbca0d8e20e8)`(typename Items::size_type pos)` 

#### `public inline Items::const_reference `[`operator[]`](#classmos_1_1Container_1a66c8ddaba3b1c6a54293e146bc79106b)`(typename Items::size_type pos) const` 

#### `public inline Items::size_type `[`size`](#classmos_1_1Container_1a032bed1ba9db555e79b4cfcd4dfa26cb)`() const` 

#### `public inline Items::reference `[`back`](#classmos_1_1Container_1a4414942ee2ce56bd637808e177fa200f)`()` 

#### `public inline const T * `[`data`](#classmos_1_1Container_1ac06512422674bc2e7c79db68c1f4f841)`() const noexcept` 

#### `public inline void `[`clear`](#classmos_1_1Container_1ab33be9c65987bd003b5995270aa26be0)`()` 

#### `public inline void `[`push_back`](#classmos_1_1Container_1a4f32a1e3191351f36f72e5fd49595515)`(const T & item)` 

#### `public inline void `[`append`](#classmos_1_1Container_1af773d4a1b0f69e96ea2b19825eb41160)`(const `[`Container`](#classmos_1_1Container)`< T > & container)` 

#### `typedef `[`Items`](#classmos_1_1Container_1abe0c4a5442787c742862dda4382dfca4) 

# class `mos::TrackedContainer` 

[Container](#classmos_1_1Container) with modified time stamp.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1a9ac23de0e4014f39fb970a629f2b613f)`()` | 
`public template<>`  <br/>`inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1a202a939b438f26ec065d72de67c5312f)`(const std::initializer_list< It > list)` | 
`public template<>`  <br/>`inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1aa16411db26c744c52d5b599d993fa04e)`(It begin,It end)` | 
`public inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1af974eb82466bf7d149eed232d12e6680)`(const `[`Container`](#classmos_1_1Container)`< T > & container)` | 
`public template<>`  <br/>`inline void `[`assign`](#classmos_1_1TrackedContainer_1a5ba8890010107a02269c314b282bd32c)`(It begin,It end)` | 
`public inline Items::iterator `[`begin`](#classmos_1_1TrackedContainer_1a37dbf6d351dd21feb09625a7150f7433)`()` | 
`public inline Items::iterator `[`end`](#classmos_1_1TrackedContainer_1a76ac63d3fb524865c7a7fd7b40972ff0)`()` | 
`public inline Items::const_iterator `[`begin`](#classmos_1_1TrackedContainer_1acde334cb96a5bfc9ca01b10a8d56e415)`() const` | 
`public inline Items::const_iterator `[`end`](#classmos_1_1TrackedContainer_1ab41f7fc25edea65528c7c824288461ac)`() const` | 
`public inline Items::reference `[`operator[]`](#classmos_1_1TrackedContainer_1a10c94022918e0d5bbf6392aa0dcee83e)`(typename Items::size_type pos)` | 
`public inline Items::const_reference `[`operator[]`](#classmos_1_1TrackedContainer_1a442cc9f9be0362e73716a8fd7bd4d238)`(typename Items::size_type pos) const` | 
`public inline Items::size_type `[`size`](#classmos_1_1TrackedContainer_1a2cc64acd9bedab8ff0953bc8b087ae27)`() const` | 
`public inline Items::reference `[`back`](#classmos_1_1TrackedContainer_1a95d85a9751e2ed938e4ac6016499ddb0)`()` | 
`public inline const T * `[`data`](#classmos_1_1TrackedContainer_1a944e4e87ac232094e401fdff6a312fcf)`() const noexcept` | 
`public inline void `[`clear`](#classmos_1_1TrackedContainer_1a2afc6e4003abefda87c2d21edcb8d430)`()` | 
`public inline void `[`push_back`](#classmos_1_1TrackedContainer_1a4f3d9435a06e29e110494650a380f3b5)`(const T & item)` | 
`public inline TimePoint `[`modified`](#classmos_1_1TrackedContainer_1aec06def1b52c5c079c1a796b160ea4d4)`() const` | 
`typedef `[`Items`](#classmos_1_1TrackedContainer_1a02c192c0869732a3b6e8a391315aec17) | 
`typedef `[`TimePoint`](#classmos_1_1TrackedContainer_1a32531e2014f132cec4e8536aac54f16d) | 

## Members

#### `public inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1a9ac23de0e4014f39fb970a629f2b613f)`()` 

#### `public template<>`  <br/>`inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1a202a939b438f26ec065d72de67c5312f)`(const std::initializer_list< It > list)` 

#### `public template<>`  <br/>`inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1aa16411db26c744c52d5b599d993fa04e)`(It begin,It end)` 

#### `public inline  `[`TrackedContainer`](#classmos_1_1TrackedContainer_1af974eb82466bf7d149eed232d12e6680)`(const `[`Container`](#classmos_1_1Container)`< T > & container)` 

#### `public template<>`  <br/>`inline void `[`assign`](#classmos_1_1TrackedContainer_1a5ba8890010107a02269c314b282bd32c)`(It begin,It end)` 

#### `public inline Items::iterator `[`begin`](#classmos_1_1TrackedContainer_1a37dbf6d351dd21feb09625a7150f7433)`()` 

#### `public inline Items::iterator `[`end`](#classmos_1_1TrackedContainer_1a76ac63d3fb524865c7a7fd7b40972ff0)`()` 

#### `public inline Items::const_iterator `[`begin`](#classmos_1_1TrackedContainer_1acde334cb96a5bfc9ca01b10a8d56e415)`() const` 

#### `public inline Items::const_iterator `[`end`](#classmos_1_1TrackedContainer_1ab41f7fc25edea65528c7c824288461ac)`() const` 

#### `public inline Items::reference `[`operator[]`](#classmos_1_1TrackedContainer_1a10c94022918e0d5bbf6392aa0dcee83e)`(typename Items::size_type pos)` 

#### `public inline Items::const_reference `[`operator[]`](#classmos_1_1TrackedContainer_1a442cc9f9be0362e73716a8fd7bd4d238)`(typename Items::size_type pos) const` 

#### `public inline Items::size_type `[`size`](#classmos_1_1TrackedContainer_1a2cc64acd9bedab8ff0953bc8b087ae27)`() const` 

#### `public inline Items::reference `[`back`](#classmos_1_1TrackedContainer_1a95d85a9751e2ed938e4ac6016499ddb0)`()` 

#### `public inline const T * `[`data`](#classmos_1_1TrackedContainer_1a944e4e87ac232094e401fdff6a312fcf)`() const noexcept` 

#### `public inline void `[`clear`](#classmos_1_1TrackedContainer_1a2afc6e4003abefda87c2d21edcb8d430)`()` 

#### `public inline void `[`push_back`](#classmos_1_1TrackedContainer_1a4f3d9435a06e29e110494650a380f3b5)`(const T & item)` 

#### `public inline TimePoint `[`modified`](#classmos_1_1TrackedContainer_1aec06def1b52c5c079c1a796b160ea4d4)`() const` 

#### `typedef `[`Items`](#classmos_1_1TrackedContainer_1a02c192c0869732a3b6e8a391315aec17) 

#### `typedef `[`TimePoint`](#classmos_1_1TrackedContainer_1a32531e2014f132cec4e8536aac54f16d) 

# namespace `mos::aud` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`mos::aud::Assets`](#classmos_1_1aud_1_1Assets) | Handles heavy audio assets.
`class `[`mos::aud::Buffer`](#classmos_1_1aud_1_1Buffer) | Audio 16bit integer buffer.
`class `[`mos::aud::BufferSource`](#classmos_1_1aud_1_1BufferSource) | Audio buffer and audio source combined.
`class `[`mos::aud::Listener`](#classmos_1_1aud_1_1Listener) | Where the audio system listens from.
`class `[`mos::aud::Renderer`](#classmos_1_1aud_1_1Renderer) | Audio system.
`class `[`mos::aud::Scene`](#classmos_1_1aud_1_1Scene) | Full scene for audio processing.
`class `[`mos::aud::Source`](#classmos_1_1aud_1_1Source) | Base class for the audio sources.
`class `[`mos::aud::Stream`](#classmos_1_1aud_1_1Stream) | Audio streaming from *.ogg file.
`class `[`mos::aud::StreamSource`](#classmos_1_1aud_1_1StreamSource) | [Stream](#classmos_1_1aud_1_1Stream) audio from file, combined with source data.

# class `mos::aud::Assets` 

Handles heavy audio assets.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Assets`](#classmos_1_1aud_1_1Assets_1a66726a07d892045355a1ab7b31f637e5)`(const std::string directory)` | 
`public  `[`Assets`](#classmos_1_1aud_1_1Assets_1a789a9b3bb9699438b975291ee168593f)`(const `[`Assets`](#classmos_1_1aud_1_1Assets)` & audio_assets) = delete` | 
`public  `[`~Assets`](#classmos_1_1aud_1_1Assets_1a8b0ae781301dc352362a13a7d73f2b45)`()` | 
`public SharedBuffer `[`audio_buffer`](#classmos_1_1aud_1_1Assets_1ad5631a6676c5e9445ed6a129ed24ed5a)`(const std::string & path)` | Loads an *.ogg file into a buffer and caches it.
`public void `[`clear_unused`](#classmos_1_1aud_1_1Assets_1a10b0b82191724041778acc509f296ff6)`()` | Remove unused buffers.
`typedef `[`BufferMap`](#classmos_1_1aud_1_1Assets_1a23d5adc673bcdb6225cf65928519c18d) | 
`typedef `[`BufferPair`](#classmos_1_1aud_1_1Assets_1ae4093f0bf4f75b7aeefc13857a2204a4) | 

## Members

#### `public  `[`Assets`](#classmos_1_1aud_1_1Assets_1a66726a07d892045355a1ab7b31f637e5)`(const std::string directory)` 

#### `public  `[`Assets`](#classmos_1_1aud_1_1Assets_1a789a9b3bb9699438b975291ee168593f)`(const `[`Assets`](#classmos_1_1aud_1_1Assets)` & audio_assets) = delete` 

#### `public  `[`~Assets`](#classmos_1_1aud_1_1Assets_1a8b0ae781301dc352362a13a7d73f2b45)`()` 

#### `public SharedBuffer `[`audio_buffer`](#classmos_1_1aud_1_1Assets_1ad5631a6676c5e9445ed6a129ed24ed5a)`(const std::string & path)` 

Loads an *.ogg file into a buffer and caches it.

#### `public void `[`clear_unused`](#classmos_1_1aud_1_1Assets_1a10b0b82191724041778acc509f296ff6)`()` 

Remove unused buffers.

#### `typedef `[`BufferMap`](#classmos_1_1aud_1_1Assets_1a23d5adc673bcdb6225cf65928519c18d) 

#### `typedef `[`BufferPair`](#classmos_1_1aud_1_1Assets_1ae4093f0bf4f75b7aeefc13857a2204a4) 

# class `mos::aud::Buffer` 

Audio 16bit integer buffer.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public template<>`  <br/>`inline  `[`Buffer`](#classmos_1_1aud_1_1Buffer_1a7ff2e23c0f962eabe013ee6c15197db9)`(const T begin,const T end,const int channels,const unsigned int sample_rate)` | Construct buffer from a container of shorts.
`public  `[`Buffer`](#classmos_1_1aud_1_1Buffer_1aa5223bb463025bad8d5b1b6551d1ecd4)`(const int channels)` | Empty buffer constructor.
`public  `[`Buffer`](#classmos_1_1aud_1_1Buffer_1a559d5e5fe723a91e3ce9286e78546354)`(const std::string & path)` | Construct from *.ogg file.
`public  `[`~Buffer`](#classmos_1_1aud_1_1Buffer_1a8d2b9b5dc3cd28ce5f1f445fda2f79a6)`()` | 
`public Samples::const_iterator `[`begin`](#classmos_1_1aud_1_1Buffer_1aa9c06835b738493ba65d2ff0d84e22d0)`() const` | 
`public Samples::const_iterator `[`end`](#classmos_1_1aud_1_1Buffer_1a7abbdf873837b467c2b9602f23b0991d)`() const` | 
`public const short * `[`data`](#classmos_1_1aud_1_1Buffer_1ae2815214d0bb3cf53f587589feb9a2d9)`() const` | Raw data.
`public unsigned int `[`id`](#classmos_1_1aud_1_1Buffer_1a6418d77b6db3a86c634fb23a098f119d)`() const` | Unique id.
`public int `[`channels`](#classmos_1_1aud_1_1Buffer_1ab8b6e7be23bb7560daa6913221c78a44)`() const` | Get number of channels.
`public int `[`sample_rate`](#classmos_1_1aud_1_1Buffer_1a547e3cfbba33fc3632abe71ea0662b03)`() const` | Get sample rate.
`public float `[`length`](#classmos_1_1aud_1_1Buffer_1abd2a4491f9c403e3a299f2a08ab84bb1)`() const` | Length in seconds.
`typedef `[`Samples`](#classmos_1_1aud_1_1Buffer_1a7d483ee163cf23a99f4995154eb27e8e) | 

## Members

#### `public template<>`  <br/>`inline  `[`Buffer`](#classmos_1_1aud_1_1Buffer_1a7ff2e23c0f962eabe013ee6c15197db9)`(const T begin,const T end,const int channels,const unsigned int sample_rate)` 

Construct buffer from a container of shorts.

#### `public  `[`Buffer`](#classmos_1_1aud_1_1Buffer_1aa5223bb463025bad8d5b1b6551d1ecd4)`(const int channels)` 

Empty buffer constructor.

#### `public  `[`Buffer`](#classmos_1_1aud_1_1Buffer_1a559d5e5fe723a91e3ce9286e78546354)`(const std::string & path)` 

Construct from *.ogg file.

#### `public  `[`~Buffer`](#classmos_1_1aud_1_1Buffer_1a8d2b9b5dc3cd28ce5f1f445fda2f79a6)`()` 

#### `public Samples::const_iterator `[`begin`](#classmos_1_1aud_1_1Buffer_1aa9c06835b738493ba65d2ff0d84e22d0)`() const` 

#### `public Samples::const_iterator `[`end`](#classmos_1_1aud_1_1Buffer_1a7abbdf873837b467c2b9602f23b0991d)`() const` 

#### `public const short * `[`data`](#classmos_1_1aud_1_1Buffer_1ae2815214d0bb3cf53f587589feb9a2d9)`() const` 

Raw data.

#### `public unsigned int `[`id`](#classmos_1_1aud_1_1Buffer_1a6418d77b6db3a86c634fb23a098f119d)`() const` 

Unique id.

#### `public int `[`channels`](#classmos_1_1aud_1_1Buffer_1ab8b6e7be23bb7560daa6913221c78a44)`() const` 

Get number of channels.

#### `public int `[`sample_rate`](#classmos_1_1aud_1_1Buffer_1a547e3cfbba33fc3632abe71ea0662b03)`() const` 

Get sample rate.

#### `public float `[`length`](#classmos_1_1aud_1_1Buffer_1abd2a4491f9c403e3a299f2a08ab84bb1)`() const` 

Length in seconds.

#### `typedef `[`Samples`](#classmos_1_1aud_1_1Buffer_1a7d483ee163cf23a99f4995154eb27e8e) 

# class `mos::aud::BufferSource` 

Audio buffer and audio source combined.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SharedBuffer `[`buffer`](#classmos_1_1aud_1_1BufferSource_1aae261ca3a53aea9d7f6b62ed9512821a) | 
`public `[`Source`](#classmos_1_1aud_1_1Source)` `[`source`](#classmos_1_1aud_1_1BufferSource_1a00e328d76117d137de46de32b0da6da5) | 
`public  `[`BufferSource`](#classmos_1_1aud_1_1BufferSource_1ad57ddb9062917be826b4f964d9e65e17)`(const SharedBuffer & buffer,const `[`Source`](#classmos_1_1aud_1_1Source)` & source)` | 
`public  `[`~BufferSource`](#classmos_1_1aud_1_1BufferSource_1ad4c6e0ae150d854f2648bff2a925d79c)`()` | 
`public void `[`input`](#classmos_1_1aud_1_1BufferSource_1a05dd11a2fcfa780b7ca76113916d0643)`(const float dt)` | Play the source.

## Members

#### `public SharedBuffer `[`buffer`](#classmos_1_1aud_1_1BufferSource_1aae261ca3a53aea9d7f6b62ed9512821a) 

#### `public `[`Source`](#classmos_1_1aud_1_1Source)` `[`source`](#classmos_1_1aud_1_1BufferSource_1a00e328d76117d137de46de32b0da6da5) 

#### `public  `[`BufferSource`](#classmos_1_1aud_1_1BufferSource_1ad57ddb9062917be826b4f964d9e65e17)`(const SharedBuffer & buffer,const `[`Source`](#classmos_1_1aud_1_1Source)` & source)` 

#### `public  `[`~BufferSource`](#classmos_1_1aud_1_1BufferSource_1ad4c6e0ae150d854f2648bff2a925d79c)`()` 

#### `public void `[`input`](#classmos_1_1aud_1_1BufferSource_1a05dd11a2fcfa780b7ca76113916d0643)`(const float dt)` 

Play the source.

# class `mos::aud::Listener` 

Where the audio system listens from.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`position`](#classmos_1_1aud_1_1Listener_1a3a54776a7f0c97b5a41560bb03fa2a2f) | 
`public glm::vec3 `[`direction`](#classmos_1_1aud_1_1Listener_1a4f2761b4bbcbe3dea2f6f2e4fdb7f82b) | 
`public glm::vec3 `[`up`](#classmos_1_1aud_1_1Listener_1a53e4f58c3d58b4097dfbaa6930657601) | 
`public glm::vec3 `[`velocity`](#classmos_1_1aud_1_1Listener_1a35670196c6dfc95f7a2baf3ff12c5b0c) | 
`public float `[`gain`](#classmos_1_1aud_1_1Listener_1ae73341fe32bcb208171cb2d137905645) | 
`public  `[`Listener`](#classmos_1_1aud_1_1Listener_1a838a29d88ecf83e3daa80b7012f7239e)`(const glm::vec3 & position,const glm::vec3 & direction,const glm::vec3 & up,const glm::vec3 & velocity,const float gain)` | 
`public  `[`~Listener`](#classmos_1_1aud_1_1Listener_1a6b5eb672adaf75bf9bfa76cbee59306e)`()` | 

## Members

#### `public glm::vec3 `[`position`](#classmos_1_1aud_1_1Listener_1a3a54776a7f0c97b5a41560bb03fa2a2f) 

#### `public glm::vec3 `[`direction`](#classmos_1_1aud_1_1Listener_1a4f2761b4bbcbe3dea2f6f2e4fdb7f82b) 

#### `public glm::vec3 `[`up`](#classmos_1_1aud_1_1Listener_1a53e4f58c3d58b4097dfbaa6930657601) 

#### `public glm::vec3 `[`velocity`](#classmos_1_1aud_1_1Listener_1a35670196c6dfc95f7a2baf3ff12c5b0c) 

#### `public float `[`gain`](#classmos_1_1aud_1_1Listener_1ae73341fe32bcb208171cb2d137905645) 

#### `public  `[`Listener`](#classmos_1_1aud_1_1Listener_1a838a29d88ecf83e3daa80b7012f7239e)`(const glm::vec3 & position,const glm::vec3 & direction,const glm::vec3 & up,const glm::vec3 & velocity,const float gain)` 

#### `public  `[`~Listener`](#classmos_1_1aud_1_1Listener_1a6b5eb672adaf75bf9bfa76cbee59306e)`()` 

# class `mos::aud::Renderer` 

Audio system.

Uses OpenAL for Windows/Linux/OSX.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Renderer`](#classmos_1_1aud_1_1Renderer_1a6a594e18e260efe52df3eadae3786270)`()` | 
`public  `[`Renderer`](#classmos_1_1aud_1_1Renderer_1a4d51c9b7ba13ab1899c117e1c970e0f6)`(const `[`Renderer`](#classmos_1_1aud_1_1Renderer)` & audio) = delete` | 
`public  `[`~Renderer`](#classmos_1_1aud_1_1Renderer_1a5009b51f1cea83ce072e04c7fbd8d3c1)`()` | 
`public `[`Listener`](#classmos_1_1aud_1_1Listener)` `[`listener`](#classmos_1_1aud_1_1Renderer_1aeebc8cff792b14cd1f7cbd8c3ad23715)`() const` | Get listener data.
`public void `[`render`](#classmos_1_1aud_1_1Renderer_1a8d8ce40ab8181c1a5148d82ed1d41c6b)`(const `[`Scene`](#classmos_1_1aud_1_1Scene)` & scene)` | Render and play audio scene.
`public void `[`clear`](#classmos_1_1aud_1_1Renderer_1a268d16754679952ec5329c465c827c3c)`()` | Clear buffers.

## Members

#### `public  `[`Renderer`](#classmos_1_1aud_1_1Renderer_1a6a594e18e260efe52df3eadae3786270)`()` 

#### `public  `[`Renderer`](#classmos_1_1aud_1_1Renderer_1a4d51c9b7ba13ab1899c117e1c970e0f6)`(const `[`Renderer`](#classmos_1_1aud_1_1Renderer)` & audio) = delete` 

#### `public  `[`~Renderer`](#classmos_1_1aud_1_1Renderer_1a5009b51f1cea83ce072e04c7fbd8d3c1)`()` 

#### `public `[`Listener`](#classmos_1_1aud_1_1Listener)` `[`listener`](#classmos_1_1aud_1_1Renderer_1aeebc8cff792b14cd1f7cbd8c3ad23715)`() const` 

Get listener data.

#### `public void `[`render`](#classmos_1_1aud_1_1Renderer_1a8d8ce40ab8181c1a5148d82ed1d41c6b)`(const `[`Scene`](#classmos_1_1aud_1_1Scene)` & scene)` 

Render and play audio scene.

#### `public void `[`clear`](#classmos_1_1aud_1_1Renderer_1a268d16754679952ec5329c465c827c3c)`()` 

Clear buffers.

# class `mos::aud::Scene` 

Full scene for audio processing.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`BufferSources`](#classmos_1_1Container)` `[`buffer_sources`](#classmos_1_1aud_1_1Scene_1a8bf22ecbeedb7386a075d91ad86ab8b5) | 
`public `[`StreamSources`](#classmos_1_1Container)` `[`stream_sources`](#classmos_1_1aud_1_1Scene_1adc4d37c6133e7766351a1d76cc104d91) | 
`public `[`Listener`](#classmos_1_1aud_1_1Listener)` `[`listener`](#classmos_1_1aud_1_1Scene_1a10d4b7b864a5543488a173d3f62813da) | 
`public  `[`Scene`](#classmos_1_1aud_1_1Scene_1a033df31a87b749e091cc5965f1afe499)`(const `[`BufferSources`](#classmos_1_1Container)` & buffer_sources,const `[`StreamSources`](#classmos_1_1Container)` & stream_sources,const `[`Listener`](#classmos_1_1aud_1_1Listener)` & listener)` | 
`public  `[`Scene`](#classmos_1_1aud_1_1Scene_1ae99fa95f77a9baff8fe9de1ddc94f26f)`()` | 

## Members

#### `public `[`BufferSources`](#classmos_1_1Container)` `[`buffer_sources`](#classmos_1_1aud_1_1Scene_1a8bf22ecbeedb7386a075d91ad86ab8b5) 

#### `public `[`StreamSources`](#classmos_1_1Container)` `[`stream_sources`](#classmos_1_1aud_1_1Scene_1adc4d37c6133e7766351a1d76cc104d91) 

#### `public `[`Listener`](#classmos_1_1aud_1_1Listener)` `[`listener`](#classmos_1_1aud_1_1Scene_1a10d4b7b864a5543488a173d3f62813da) 

#### `public  `[`Scene`](#classmos_1_1aud_1_1Scene_1a033df31a87b749e091cc5965f1afe499)`(const `[`BufferSources`](#classmos_1_1Container)` & buffer_sources,const `[`StreamSources`](#classmos_1_1Container)` & stream_sources,const `[`Listener`](#classmos_1_1aud_1_1Listener)` & listener)` 

#### `public  `[`Scene`](#classmos_1_1aud_1_1Scene_1ae99fa95f77a9baff8fe9de1ddc94f26f)`()` 

# class `mos::aud::Source` 

Base class for the audio sources.

Either streamed or direct from memory.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`position`](#classmos_1_1aud_1_1Source_1a91e8718a58247e7990b7b2b48b294988) | 
`public glm::vec3 `[`velocity`](#classmos_1_1aud_1_1Source_1a43ed5c826ecd7baae67d3f06129beebd) | 
`public float `[`pitch`](#classmos_1_1aud_1_1Source_1a06cd4fe9f6567a19b5ba6cfc150e45b0) | 
`public float `[`gain`](#classmos_1_1aud_1_1Source_1a773e63c1a469bea9fefd3e22a92ec798) | 
`public bool `[`loop`](#classmos_1_1aud_1_1Source_1aeb851f2f95b580aa0a2054f4b79e7953) | 
`public bool `[`playing`](#classmos_1_1aud_1_1Source_1a4b74513cc2df86180fd3c193655d1c7f) | 
`public float `[`obstructed`](#classmos_1_1aud_1_1Source_1a339875154e0e71b7030789f934d574b9) | 
`public  `[`Source`](#classmos_1_1aud_1_1Source_1ae2dab26caa7e79763e240c4e3f58c052)`(const glm::vec3 & position,const glm::vec3 & velocity,const float pitch,const float gain,const bool loop,const bool playing,const float obstructed)` | 
`public  `[`~Source`](#classmos_1_1aud_1_1Source_1a5086fb031df9d82440afb4b36e24e3ba)`()` | 
`public unsigned int `[`id`](#classmos_1_1aud_1_1Source_1a5e328dba51f1ead7b7ef870dbc143dc5)`() const` | Unique id.

## Members

#### `public glm::vec3 `[`position`](#classmos_1_1aud_1_1Source_1a91e8718a58247e7990b7b2b48b294988) 

#### `public glm::vec3 `[`velocity`](#classmos_1_1aud_1_1Source_1a43ed5c826ecd7baae67d3f06129beebd) 

#### `public float `[`pitch`](#classmos_1_1aud_1_1Source_1a06cd4fe9f6567a19b5ba6cfc150e45b0) 

#### `public float `[`gain`](#classmos_1_1aud_1_1Source_1a773e63c1a469bea9fefd3e22a92ec798) 

#### `public bool `[`loop`](#classmos_1_1aud_1_1Source_1aeb851f2f95b580aa0a2054f4b79e7953) 

#### `public bool `[`playing`](#classmos_1_1aud_1_1Source_1a4b74513cc2df86180fd3c193655d1c7f) 

#### `public float `[`obstructed`](#classmos_1_1aud_1_1Source_1a339875154e0e71b7030789f934d574b9) 

#### `public  `[`Source`](#classmos_1_1aud_1_1Source_1ae2dab26caa7e79763e240c4e3f58c052)`(const glm::vec3 & position,const glm::vec3 & velocity,const float pitch,const float gain,const bool loop,const bool playing,const float obstructed)` 

#### `public  `[`~Source`](#classmos_1_1aud_1_1Source_1a5086fb031df9d82440afb4b36e24e3ba)`()` 

#### `public unsigned int `[`id`](#classmos_1_1aud_1_1Source_1a5e328dba51f1ead7b7ef870dbc143dc5)`() const` 

Unique id.

# class `mos::aud::Stream` 

Audio streaming from *.ogg file.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  explicit `[`Stream`](#classmos_1_1aud_1_1Stream_1a8b41909d7992d82d93ac4e31db776c39)`(const std::string & path)` | 
`public  `[`~Stream`](#classmos_1_1aud_1_1Stream_1aa3c9949a04cc4661ae795f3d40e148d0)`()` | 
`public std::array< short, buffer_size > `[`read`](#classmos_1_1aud_1_1Stream_1a7e8ec8f30354ae2bc6b71ac2b97f66b2)`()` | 
`public bool `[`done`](#classmos_1_1aud_1_1Stream_1abf342e5f2ffb303fc66c7af2b34a11f7)`() const` | 
`public int `[`sample_rate`](#classmos_1_1aud_1_1Stream_1a4d1e206ecbd9941892eaa9e4014e3bab)`() const` | 
`public int `[`channels`](#classmos_1_1aud_1_1Stream_1a237906b3e7425db41a23af83c3ddaeef)`() const` | Get number of channels.
`public void `[`seek_start`](#classmos_1_1aud_1_1Stream_1ae3df731e30e7c7263c5951843927c662)`()` | Restart streaming.
`public unsigned int `[`id`](#classmos_1_1aud_1_1Stream_1a1313947dde2521203fcba8ce47df3e6d)`() const` | Unique id.

## Members

#### `public  explicit `[`Stream`](#classmos_1_1aud_1_1Stream_1a8b41909d7992d82d93ac4e31db776c39)`(const std::string & path)` 

#### `public  `[`~Stream`](#classmos_1_1aud_1_1Stream_1aa3c9949a04cc4661ae795f3d40e148d0)`()` 

#### `public std::array< short, buffer_size > `[`read`](#classmos_1_1aud_1_1Stream_1a7e8ec8f30354ae2bc6b71ac2b97f66b2)`()` 

#### `public bool `[`done`](#classmos_1_1aud_1_1Stream_1abf342e5f2ffb303fc66c7af2b34a11f7)`() const` 

#### `public int `[`sample_rate`](#classmos_1_1aud_1_1Stream_1a4d1e206ecbd9941892eaa9e4014e3bab)`() const` 

#### `public int `[`channels`](#classmos_1_1aud_1_1Stream_1a237906b3e7425db41a23af83c3ddaeef)`() const` 

Get number of channels.

#### `public void `[`seek_start`](#classmos_1_1aud_1_1Stream_1ae3df731e30e7c7263c5951843927c662)`()` 

Restart streaming.

#### `public unsigned int `[`id`](#classmos_1_1aud_1_1Stream_1a1313947dde2521203fcba8ce47df3e6d)`() const` 

Unique id.

# class `mos::aud::StreamSource` 

[Stream](#classmos_1_1aud_1_1Stream) audio from file, combined with source data.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SharedStream `[`stream`](#classmos_1_1aud_1_1StreamSource_1a4a8b81ae958b9c72f67aaacac5ef4c4f) | [Stream](#classmos_1_1aud_1_1Stream) used for the source.
`public `[`Source`](#classmos_1_1aud_1_1Source)` `[`source`](#classmos_1_1aud_1_1StreamSource_1a13f9d03b5d6117cb60dbc2b6eac3adc6) | [Source](#classmos_1_1aud_1_1Source) data.
`public  explicit `[`StreamSource`](#classmos_1_1aud_1_1StreamSource_1a6f730340f162e0c63570e58c404d7c5b)`(const SharedStream & stream,const `[`Source`](#classmos_1_1aud_1_1Source)` & source)` | 
`public  `[`~StreamSource`](#classmos_1_1aud_1_1StreamSource_1ac745f5597b8cf9d1f37289c1d881475c)`()` | 

## Members

#### `public SharedStream `[`stream`](#classmos_1_1aud_1_1StreamSource_1a4a8b81ae958b9c72f67aaacac5ef4c4f) 

[Stream](#classmos_1_1aud_1_1Stream) used for the source.

#### `public `[`Source`](#classmos_1_1aud_1_1Source)` `[`source`](#classmos_1_1aud_1_1StreamSource_1a13f9d03b5d6117cb60dbc2b6eac3adc6) 

[Source](#classmos_1_1aud_1_1Source) data.

#### `public  explicit `[`StreamSource`](#classmos_1_1aud_1_1StreamSource_1a6f730340f162e0c63570e58c404d7c5b)`(const SharedStream & stream,const `[`Source`](#classmos_1_1aud_1_1Source)` & source)` 

#### `public  `[`~StreamSource`](#classmos_1_1aud_1_1StreamSource_1ac745f5597b8cf9d1f37289c1d881475c)`()` 

# namespace `mos::exp` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`mos::exp::Trigger`](#classmos_1_1exp_1_1Trigger) | Triggers when the value changes.

# class `mos::exp::Trigger` 

Triggers when the value changes.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`Trigger`](#classmos_1_1exp_1_1Trigger_1a57eefb3e8a222ccfae67a0651dec03b8)`(const T & value)` | 
`public inline T `[`operator=`](#classmos_1_1exp_1_1Trigger_1a8a694771cabd7c47578b0bd4d5f57912)`(const T & value)` | 
`public inline T `[`operator-=`](#classmos_1_1exp_1_1Trigger_1ab458e8695f7d2e4354af99b6c2cb63c1)`(const T & value)` | 
`public inline  `[`operator T`](#classmos_1_1exp_1_1Trigger_1a35c683033de4fe17b38f889e48e23f1d)`() const` | 
`public inline bool `[`changed`](#classmos_1_1exp_1_1Trigger_1a13726ee6f2ab7acd8d7e30c4d56734e3)`() const` | 
`public inline T `[`old_value`](#classmos_1_1exp_1_1Trigger_1a57f20035be02c8fe9af7f7586d5d8e52)`() const` | 
`public inline T `[`delta`](#classmos_1_1exp_1_1Trigger_1aadeea2dd7fe81ce5e953e8d16cd43e05)`() const` | 

## Members

#### `public inline  `[`Trigger`](#classmos_1_1exp_1_1Trigger_1a57eefb3e8a222ccfae67a0651dec03b8)`(const T & value)` 

#### `public inline T `[`operator=`](#classmos_1_1exp_1_1Trigger_1a8a694771cabd7c47578b0bd4d5f57912)`(const T & value)` 

#### `public inline T `[`operator-=`](#classmos_1_1exp_1_1Trigger_1ab458e8695f7d2e4354af99b6c2cb63c1)`(const T & value)` 

#### `public inline  `[`operator T`](#classmos_1_1exp_1_1Trigger_1a35c683033de4fe17b38f889e48e23f1d)`() const` 

#### `public inline bool `[`changed`](#classmos_1_1exp_1_1Trigger_1a13726ee6f2ab7acd8d7e30c4d56734e3)`() const` 

#### `public inline T `[`old_value`](#classmos_1_1exp_1_1Trigger_1a57f20035be02c8fe9af7f7586d5d8e52)`() const` 

#### `public inline T `[`delta`](#classmos_1_1exp_1_1Trigger_1aadeea2dd7fe81ce5e953e8d16cd43e05)`() const` 

# namespace `mos::gfx` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`wrap_convert`](#gfx_2renderer_8cpp_1a030293511d85ab4d5eaf72f3521644b8)`(const Texture::Wrap & wrap)`            | 
`public `[`FormatPair`](#structmos_1_1gfx_1_1FormatPair)` `[`format_convert`](#gfx_2renderer_8cpp_1afecbd7f775e96822984bcb99eda1b330)`(const Texture::Format & format)`            | 
`public void APIENTRY `[`message_callback`](#gfx_2renderer_8cpp_1ac3d6350a46a6ce5ad34fa747947dca06)`(GLenum source,GLenum type,GLuint id,GLenum severity,GLsizei length,const GLchar * message,const void * userParam)`            | 
`class `[`mos::gfx::Animation`](#classmos_1_1gfx_1_1Animation) | Keyframe animation, interpolation between meshes.
`class `[`mos::gfx::Assets`](#classmos_1_1gfx_1_1Assets) | Handles heavy render assets, such as Textures and meshes.
`class `[`mos::gfx::Box`](#classmos_1_1gfx_1_1Box) | Bounding box for rendering.
`class `[`mos::gfx::Camera`](#classmos_1_1gfx_1_1Camera) | Rendering camera view.
`class `[`mos::gfx::CubeCamera`](#classmos_1_1gfx_1_1CubeCamera) | [Camera](#classmos_1_1gfx_1_1Camera) for environment rendering.
`class `[`mos::gfx::EnvironmentLight`](#classmos_1_1gfx_1_1EnvironmentLight) | Environment light, based on a cube map.
`class `[`mos::gfx::Fog`](#classmos_1_1gfx_1_1Fog) | [Fog](#classmos_1_1gfx_1_1Fog) with exponential falloff and near/far color blending.
`class `[`mos::gfx::Font`](#classmos_1_1gfx_1_1Font) | Bitmap font.
`class `[`mos::gfx::Light`](#classmos_1_1gfx_1_1Light) | Spotlight.
`class `[`mos::gfx::Material`](#classmos_1_1gfx_1_1Material) | Physically based material.
`class `[`mos::gfx::Mesh`](#classmos_1_1gfx_1_1Mesh) | Geometric data description.
`class `[`mos::gfx::Model`](#classmos_1_1gfx_1_1Model) | Collection of properties to render an object.
`class `[`mos::gfx::Particle`](#classmos_1_1gfx_1_1Particle) | [Particle](#classmos_1_1gfx_1_1Particle) used in a particle system.
`class `[`mos::gfx::ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud) | Collection of same particles for rendering.
`class `[`mos::gfx::Renderer`](#classmos_1_1gfx_1_1Renderer) | Render geometry shapes with OpenGL.
`class `[`mos::gfx::Scene`](#classmos_1_1gfx_1_1Scene) | [Scene](#classmos_1_1gfx_1_1Scene) for rendering.
`class `[`mos::gfx::Shape`](#classmos_1_1gfx_1_1Shape) | Base class for geometric shapes.
`class `[`mos::gfx::Target`](#classmos_1_1gfx_1_1Target) | Off screen rendering target.
`class `[`mos::gfx::Text`](#classmos_1_1gfx_1_1Text) | [Text](#classmos_1_1gfx_1_1Text) for rendering.
`class `[`mos::gfx::Texture`](#classmos_1_1gfx_1_1Texture) | 
`class `[`mos::gfx::Texture2D`](#classmos_1_1gfx_1_1Texture2D) | [Texture](#classmos_1_1gfx_1_1Texture) in two dimension.
`class `[`mos::gfx::Vertex`](#classmos_1_1gfx_1_1Vertex) | The vertex structure, supported by the renderer.
`struct `[`mos::gfx::Character`](#structmos_1_1gfx_1_1Character) | Measurements of a character glyph, for text rendering.
`struct `[`mos::gfx::Face`](#structmos_1_1gfx_1_1Face) | 
`struct `[`mos::gfx::FormatPair`](#structmos_1_1gfx_1_1FormatPair) | 
`struct `[`mos::gfx::TextureTarget`](#structmos_1_1gfx_1_1TextureTarget) | 

## Members

#### `public GLuint `[`wrap_convert`](#gfx_2renderer_8cpp_1a030293511d85ab4d5eaf72f3521644b8)`(const Texture::Wrap & wrap)` 

#### `public `[`FormatPair`](#structmos_1_1gfx_1_1FormatPair)` `[`format_convert`](#gfx_2renderer_8cpp_1afecbd7f775e96822984bcb99eda1b330)`(const Texture::Format & format)` 

#### `public void APIENTRY `[`message_callback`](#gfx_2renderer_8cpp_1ac3d6350a46a6ce5ad34fa747947dca06)`(GLenum source,GLenum type,GLuint id,GLenum severity,GLsizei length,const GLchar * message,const void * userParam)` 

# class `mos::gfx::Animation` 

Keyframe animation, interpolation between meshes.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1ab7b44b83886d2ef8e6b9acba2d3ec488)`() = default` | 
`public  `[`~Animation`](#classmos_1_1gfx_1_1Animation_1a50770d37663a0506fdaa0a2f68b28803)`() = default` | 
`public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1aa3d08cc79b18fc40ccad349df431e4bb)`(const std::map< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >> keyframes,const unsigned int frame_rate)` | 
`public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1a29aba724ec28e24df118b8aaa15e4fe1)`(std::initializer_list< std::pair< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >>> keyframes,const unsigned int frame_rate)` | 
`public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1a30d9fce1bef9a67d9374ba1c3e13b850)`(const std::string & path)` | 
`public void `[`update`](#classmos_1_1gfx_1_1Animation_1a9aca652764e1820efc32a286111367da)`(const float dt)` | 
`public int `[`frame`](#classmos_1_1gfx_1_1Animation_1a754b4c1a0390aa19f5e7bb0656fd30a8)`() const` | Current frame.
`public void `[`reset`](#classmos_1_1gfx_1_1Animation_1a6000a70e8e7987f6103555f42a79cf2c)`()` | Restart the animation.
`public void `[`frame_rate`](#classmos_1_1gfx_1_1Animation_1a0bd103ed4b9509d589fa7ecb83dd1b60)`(const unsigned int frame_rate)` | Set frame rate.
`public unsigned int `[`frame_rate`](#classmos_1_1gfx_1_1Animation_1aa075ed0576d8b072d27e105796b19e75)`() const` | Frames per second.
`public std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` > `[`mesh`](#classmos_1_1gfx_1_1Animation_1a2ef4cb3a4a9a85faae79e485c6c4a09b)`()` | The mesh being animated.

## Members

#### `public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1ab7b44b83886d2ef8e6b9acba2d3ec488)`() = default` 

#### `public  `[`~Animation`](#classmos_1_1gfx_1_1Animation_1a50770d37663a0506fdaa0a2f68b28803)`() = default` 

#### `public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1aa3d08cc79b18fc40ccad349df431e4bb)`(const std::map< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >> keyframes,const unsigned int frame_rate)` 

#### `public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1a29aba724ec28e24df118b8aaa15e4fe1)`(std::initializer_list< std::pair< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >>> keyframes,const unsigned int frame_rate)` 

#### `public  `[`Animation`](#classmos_1_1gfx_1_1Animation_1a30d9fce1bef9a67d9374ba1c3e13b850)`(const std::string & path)` 

#### `public void `[`update`](#classmos_1_1gfx_1_1Animation_1a9aca652764e1820efc32a286111367da)`(const float dt)` 

#### `public int `[`frame`](#classmos_1_1gfx_1_1Animation_1a754b4c1a0390aa19f5e7bb0656fd30a8)`() const` 

Current frame.

#### `public void `[`reset`](#classmos_1_1gfx_1_1Animation_1a6000a70e8e7987f6103555f42a79cf2c)`()` 

Restart the animation.

#### `public void `[`frame_rate`](#classmos_1_1gfx_1_1Animation_1a0bd103ed4b9509d589fa7ecb83dd1b60)`(const unsigned int frame_rate)` 

Set frame rate.

#### `public unsigned int `[`frame_rate`](#classmos_1_1gfx_1_1Animation_1aa075ed0576d8b072d27e105796b19e75)`() const` 

Frames per second.

#### `public std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` > `[`mesh`](#classmos_1_1gfx_1_1Animation_1a2ef4cb3a4a9a85faae79e485c6c4a09b)`()` 

The mesh being animated.

# class `mos::gfx::Assets` 

Handles heavy render assets, such as Textures and meshes.

Caches things internally, so nothing is loaded twice.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Assets`](#classmos_1_1gfx_1_1Assets_1af6910df6d63d0797a52618a11c3a9159)`(const std::string directory)` | #### Parameters
`public  `[`Assets`](#classmos_1_1gfx_1_1Assets_1a4ca04a099dc5f3ab3027e19efb78c2e0)`(const `[`Assets`](#classmos_1_1gfx_1_1Assets)` & assets) = delete` | 
`public  `[`~Assets`](#classmos_1_1gfx_1_1Assets_1a46ce6dbda63def8d71e1bdb112f2c4c5)`()` | 
`public `[`Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1Assets_1a7cd1dcb5ca01c5960e72a81e08e96a5b)`(const std::string & path,const glm::mat4 & parent_transform)` | Loads a [Model](#classmos_1_1gfx_1_1Model) from a *.model file.
`public `[`Model`](#classmos_1_1gfx_1_1Model)` `[`model_value`](#classmos_1_1gfx_1_1Assets_1a0bf50580bca12332ca88b4251702427c)`(const nlohmann::json & value,const glm::mat4 & parent_transform)` | Loads a [Model](#classmos_1_1gfx_1_1Model) from a json structure.
`public `[`Animation`](#classmos_1_1gfx_1_1Animation)` `[`animation`](#classmos_1_1gfx_1_1Assets_1aacf0dceaf94c4490543cd7da23102762)`(const std::string & path)` | Loads an animation from meshes specified in *.animation file.
`public `[`Material`](#classmos_1_1gfx_1_1Material)` `[`material`](#classmos_1_1gfx_1_1Assets_1ad4adbb603aacc6e9afec0cee10c2df59)`(const std::string & path)` | Loads a [Material](#classmos_1_1gfx_1_1Material) from a *.material file into a [Material](#classmos_1_1gfx_1_1Material) object.
`public `[`Light`](#classmos_1_1gfx_1_1Light)` `[`light`](#classmos_1_1gfx_1_1Assets_1a8c4d2abb896cc6d04a5ff59e36652b97)`(const std::string & path,const glm::mat4 & parent_transform)` | Loads a [Light](#classmos_1_1gfx_1_1Light) from a *.light file into a [Light](#classmos_1_1gfx_1_1Light) object.
`public `[`EnvironmentLight`](#classmos_1_1gfx_1_1EnvironmentLight)` `[`environment_light`](#classmos_1_1gfx_1_1Assets_1a0ba223ac1aa91d07088bcb5973621303)`(const std::string & path,const glm::mat4 & parent_transform)` | Loads a [EnvironmentLight](#classmos_1_1gfx_1_1EnvironmentLight) from a *.environment_light.
`public SharedMesh `[`mesh`](#classmos_1_1gfx_1_1Assets_1a675c39cd15bf03f2ee2f8b601f64f2ff)`(const std::string & path)` | Loads a [Mesh](#classmos_1_1gfx_1_1Mesh) from a *.mesh file and caches it internally.
`public SharedTexture2D `[`texture`](#classmos_1_1gfx_1_1Assets_1ac037577867b7ff6923ac1ca4ae8f9ad0)`(const std::string & path,const bool color_data,const bool mipmaps,const Texture2D::Wrap & wrap)` | Loads [Texture2D](#classmos_1_1gfx_1_1Texture2D) from a *.png file and caches it internally.
`public void `[`clear_unused`](#classmos_1_1gfx_1_1Assets_1a98cccbc96e5fca19702e4a99f682d1b2)`()` | Remove all unused assets.
`public std::string `[`directory`](#classmos_1_1gfx_1_1Assets_1a9e1500e595a6520a51ca850f0fbf270c)`() const` | 
`typedef `[`MeshMap`](#classmos_1_1gfx_1_1Assets_1a97087c4b44ca8f3c886a03ee04be965a) | 
`typedef `[`TextureMap`](#classmos_1_1gfx_1_1Assets_1addd87db22aa9b23dd9774d33d204a910) | 
`typedef `[`MeshPair`](#classmos_1_1gfx_1_1Assets_1a715d33d3c92b03356dde538d0516aad9) | 
`typedef `[`TexturePair`](#classmos_1_1gfx_1_1Assets_1a50837d6cfaf4421d15bbe0e59ef356a2) | 
`typedef `[`MaterialPair`](#classmos_1_1gfx_1_1Assets_1ad4cc0c3dcae1fbffe7e743743a2e1b09) | 
`typedef `[`SharedMaterial`](#classmos_1_1gfx_1_1Assets_1a00970c6295400c7e59c54b6781899ae2) | 

## Members

#### `public  `[`Assets`](#classmos_1_1gfx_1_1Assets_1af6910df6d63d0797a52618a11c3a9159)`(const std::string directory)` 

#### Parameters
* `directory` The directory where the assets exist, relative to the run directory.

#### `public  `[`Assets`](#classmos_1_1gfx_1_1Assets_1a4ca04a099dc5f3ab3027e19efb78c2e0)`(const `[`Assets`](#classmos_1_1gfx_1_1Assets)` & assets) = delete` 

#### `public  `[`~Assets`](#classmos_1_1gfx_1_1Assets_1a46ce6dbda63def8d71e1bdb112f2c4c5)`()` 

#### `public `[`Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1Assets_1a7cd1dcb5ca01c5960e72a81e08e96a5b)`(const std::string & path,const glm::mat4 & parent_transform)` 

Loads a [Model](#classmos_1_1gfx_1_1Model) from a *.model file.

#### `public `[`Model`](#classmos_1_1gfx_1_1Model)` `[`model_value`](#classmos_1_1gfx_1_1Assets_1a0bf50580bca12332ca88b4251702427c)`(const nlohmann::json & value,const glm::mat4 & parent_transform)` 

Loads a [Model](#classmos_1_1gfx_1_1Model) from a json structure.

#### `public `[`Animation`](#classmos_1_1gfx_1_1Animation)` `[`animation`](#classmos_1_1gfx_1_1Assets_1aacf0dceaf94c4490543cd7da23102762)`(const std::string & path)` 

Loads an animation from meshes specified in *.animation file.

#### `public `[`Material`](#classmos_1_1gfx_1_1Material)` `[`material`](#classmos_1_1gfx_1_1Assets_1ad4adbb603aacc6e9afec0cee10c2df59)`(const std::string & path)` 

Loads a [Material](#classmos_1_1gfx_1_1Material) from a *.material file into a [Material](#classmos_1_1gfx_1_1Material) object.

#### `public `[`Light`](#classmos_1_1gfx_1_1Light)` `[`light`](#classmos_1_1gfx_1_1Assets_1a8c4d2abb896cc6d04a5ff59e36652b97)`(const std::string & path,const glm::mat4 & parent_transform)` 

Loads a [Light](#classmos_1_1gfx_1_1Light) from a *.light file into a [Light](#classmos_1_1gfx_1_1Light) object.

#### `public `[`EnvironmentLight`](#classmos_1_1gfx_1_1EnvironmentLight)` `[`environment_light`](#classmos_1_1gfx_1_1Assets_1a0ba223ac1aa91d07088bcb5973621303)`(const std::string & path,const glm::mat4 & parent_transform)` 

Loads a [EnvironmentLight](#classmos_1_1gfx_1_1EnvironmentLight) from a *.environment_light.

#### `public SharedMesh `[`mesh`](#classmos_1_1gfx_1_1Assets_1a675c39cd15bf03f2ee2f8b601f64f2ff)`(const std::string & path)` 

Loads a [Mesh](#classmos_1_1gfx_1_1Mesh) from a *.mesh file and caches it internally.

#### `public SharedTexture2D `[`texture`](#classmos_1_1gfx_1_1Assets_1ac037577867b7ff6923ac1ca4ae8f9ad0)`(const std::string & path,const bool color_data,const bool mipmaps,const Texture2D::Wrap & wrap)` 

Loads [Texture2D](#classmos_1_1gfx_1_1Texture2D) from a *.png file and caches it internally.

#### `public void `[`clear_unused`](#classmos_1_1gfx_1_1Assets_1a98cccbc96e5fca19702e4a99f682d1b2)`()` 

Remove all unused assets.

#### `public std::string `[`directory`](#classmos_1_1gfx_1_1Assets_1a9e1500e595a6520a51ca850f0fbf270c)`() const` 

#### `typedef `[`MeshMap`](#classmos_1_1gfx_1_1Assets_1a97087c4b44ca8f3c886a03ee04be965a) 

#### `typedef `[`TextureMap`](#classmos_1_1gfx_1_1Assets_1addd87db22aa9b23dd9774d33d204a910) 

#### `typedef `[`MeshPair`](#classmos_1_1gfx_1_1Assets_1a715d33d3c92b03356dde538d0516aad9) 

#### `typedef `[`TexturePair`](#classmos_1_1gfx_1_1Assets_1a50837d6cfaf4421d15bbe0e59ef356a2) 

#### `typedef `[`MaterialPair`](#classmos_1_1gfx_1_1Assets_1ad4cc0c3dcae1fbffe7e743743a2e1b09) 

#### `typedef `[`SharedMaterial`](#classmos_1_1gfx_1_1Assets_1a00970c6295400c7e59c54b6781899ae2) 

# class `mos::gfx::Box` 

Bounding box for rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::mat4 `[`transform`](#classmos_1_1gfx_1_1Box_1a01250cfb3d8dd03073cd0d743bdabb8f) | 
`public glm::vec3 `[`extent`](#classmos_1_1gfx_1_1Box_1a2405c7c5eff876cd2889a81f9e06909c) | 
`public  `[`Box`](#classmos_1_1gfx_1_1Box_1a03f204dc7105d68170a4c1edf9711870)`()` | 
`public  `[`Box`](#classmos_1_1gfx_1_1Box_1a54d8b5966fe21269eb8b910bab1b79da)`(const glm::mat4 & transform,const glm::vec3 & extent)` | 
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Box_1ab8f3e0151421630725ef2d41dbaf3029)`() const` | 
`public glm::vec3 `[`size`](#classmos_1_1gfx_1_1Box_1a217dde8e291ccd830a8180a872cfa5df)`() const` | 
`public glm::vec3 `[`min`](#classmos_1_1gfx_1_1Box_1a4d0cb7894463e3c498599cc0837d1a3c)`() const` | 
`public glm::vec3 `[`max`](#classmos_1_1gfx_1_1Box_1a855637ae3311b90cb134ddf96c7fc17a)`() const` | 
`public bool `[`inside`](#classmos_1_1gfx_1_1Box_1a201a22dd78e3a0214e2fbccf467853ea)`(const glm::vec3 & point) const` | 

## Members

#### `public glm::mat4 `[`transform`](#classmos_1_1gfx_1_1Box_1a01250cfb3d8dd03073cd0d743bdabb8f) 

#### `public glm::vec3 `[`extent`](#classmos_1_1gfx_1_1Box_1a2405c7c5eff876cd2889a81f9e06909c) 

#### `public  `[`Box`](#classmos_1_1gfx_1_1Box_1a03f204dc7105d68170a4c1edf9711870)`()` 

#### `public  `[`Box`](#classmos_1_1gfx_1_1Box_1a54d8b5966fe21269eb8b910bab1b79da)`(const glm::mat4 & transform,const glm::vec3 & extent)` 

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Box_1ab8f3e0151421630725ef2d41dbaf3029)`() const` 

#### `public glm::vec3 `[`size`](#classmos_1_1gfx_1_1Box_1a217dde8e291ccd830a8180a872cfa5df)`() const` 

#### `public glm::vec3 `[`min`](#classmos_1_1gfx_1_1Box_1a4d0cb7894463e3c498599cc0837d1a3c)`() const` 

#### `public glm::vec3 `[`max`](#classmos_1_1gfx_1_1Box_1a855637ae3311b90cb134ddf96c7fc17a)`() const` 

#### `public bool `[`inside`](#classmos_1_1gfx_1_1Box_1a201a22dd78e3a0214e2fbccf467853ea)`(const glm::vec3 & point) const` 

# class `mos::gfx::Camera` 

Rendering camera view.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::mat4 `[`projection`](#classmos_1_1gfx_1_1Camera_1ae0fb6c370d8a3e2469fa696d9794b3bb) | 
`public glm::mat4 `[`view`](#classmos_1_1gfx_1_1Camera_1ac2acdd184f2502841fe845aa5df371b1) | 
`public  `[`Camera`](#classmos_1_1gfx_1_1Camera_1af99fe1e2d5c195c6efc363dfc64dc661)`()` | 
`public  `[`Camera`](#classmos_1_1gfx_1_1Camera_1a5d4d53b97c447af0f483471a83e3fd16)`(const glm::vec3 & position,const glm::vec3 & center,const glm::mat4 & projection,const glm::vec3 & up)` | 
`public glm::vec3 `[`up`](#classmos_1_1gfx_1_1Camera_1a3f0e1392a7f2ce89e550aed269ef364f)`() const` | 
`public void `[`up`](#classmos_1_1gfx_1_1Camera_1a80080926278046f7fefa0372c2a5fc80)`(const glm::vec3 & up)` | Set up vector.
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Camera_1aec5b80f811e86b15683f8e93711e437a)`() const` | 
`public void `[`position`](#classmos_1_1gfx_1_1Camera_1a60ed39769326636c53db3c6ba0b7be7e)`(const glm::vec3 & position)` | Set position.
`public glm::vec3 `[`center`](#classmos_1_1gfx_1_1Camera_1ad32db67564ecaf8bf843eb4c862e60e9)`() const` | 
`public void `[`center`](#classmos_1_1gfx_1_1Camera_1a4750b75049f0e7707c19f0987a8eb80f)`(const glm::vec3 & center)` | Set center/focus point.
`public glm::vec3 `[`direction`](#classmos_1_1gfx_1_1Camera_1ae653e18eb76806e10d49f981712878ee)`() const` | 
`public void `[`direction`](#classmos_1_1gfx_1_1Camera_1a913a3960978fffcf0907c7cb0b7e30fc)`(const glm::vec3 & direction)` | Set direction.
`public float `[`aspect_ratio`](#classmos_1_1gfx_1_1Camera_1aea1c65980325d42aa3edaa9f12cc5650)`() const` | 

## Members

#### `public glm::mat4 `[`projection`](#classmos_1_1gfx_1_1Camera_1ae0fb6c370d8a3e2469fa696d9794b3bb) 

#### `public glm::mat4 `[`view`](#classmos_1_1gfx_1_1Camera_1ac2acdd184f2502841fe845aa5df371b1) 

#### `public  `[`Camera`](#classmos_1_1gfx_1_1Camera_1af99fe1e2d5c195c6efc363dfc64dc661)`()` 

#### `public  `[`Camera`](#classmos_1_1gfx_1_1Camera_1a5d4d53b97c447af0f483471a83e3fd16)`(const glm::vec3 & position,const glm::vec3 & center,const glm::mat4 & projection,const glm::vec3 & up)` 

#### `public glm::vec3 `[`up`](#classmos_1_1gfx_1_1Camera_1a3f0e1392a7f2ce89e550aed269ef364f)`() const` 

#### `public void `[`up`](#classmos_1_1gfx_1_1Camera_1a80080926278046f7fefa0372c2a5fc80)`(const glm::vec3 & up)` 

Set up vector.

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Camera_1aec5b80f811e86b15683f8e93711e437a)`() const` 

#### `public void `[`position`](#classmos_1_1gfx_1_1Camera_1a60ed39769326636c53db3c6ba0b7be7e)`(const glm::vec3 & position)` 

Set position.

#### `public glm::vec3 `[`center`](#classmos_1_1gfx_1_1Camera_1ad32db67564ecaf8bf843eb4c862e60e9)`() const` 

#### `public void `[`center`](#classmos_1_1gfx_1_1Camera_1a4750b75049f0e7707c19f0987a8eb80f)`(const glm::vec3 & center)` 

Set center/focus point.

#### `public glm::vec3 `[`direction`](#classmos_1_1gfx_1_1Camera_1ae653e18eb76806e10d49f981712878ee)`() const` 

#### `public void `[`direction`](#classmos_1_1gfx_1_1Camera_1a913a3960978fffcf0907c7cb0b7e30fc)`(const glm::vec3 & direction)` 

Set direction.

#### `public float `[`aspect_ratio`](#classmos_1_1gfx_1_1Camera_1aea1c65980325d42aa3edaa9f12cc5650)`() const` 

# class `mos::gfx::CubeCamera` 

[Camera](#classmos_1_1gfx_1_1Camera) for environment rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public std::array< `[`Camera`](#classmos_1_1gfx_1_1Camera)`, 6 > `[`cameras`](#classmos_1_1gfx_1_1CubeCamera_1a2e9bb113dae2b45b2c9ee59476c46814) | Cameras for eac axis.
`public  `[`CubeCamera`](#classmos_1_1gfx_1_1CubeCamera_1a90f84312ac112ce13c7b0b03a99b3c97)`(const glm::vec3 & position,const float near,const float far)` | 
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1CubeCamera_1a9bdb95b46d91a06cc9c9df2b9861a31c)`() const` | 
`public void `[`position`](#classmos_1_1gfx_1_1CubeCamera_1aff8621c33265f2f766a9cb23d02fe6c7)`(const glm::vec3 & position)` | Set position.
`public void `[`near_far`](#classmos_1_1gfx_1_1CubeCamera_1ad70cc12b2239d4cb35703c844b509e94)`(const float near,const float far)` | Set near and far planes.

## Members

#### `public std::array< `[`Camera`](#classmos_1_1gfx_1_1Camera)`, 6 > `[`cameras`](#classmos_1_1gfx_1_1CubeCamera_1a2e9bb113dae2b45b2c9ee59476c46814) 

Cameras for eac axis.

#### `public  `[`CubeCamera`](#classmos_1_1gfx_1_1CubeCamera_1a90f84312ac112ce13c7b0b03a99b3c97)`(const glm::vec3 & position,const float near,const float far)` 

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1CubeCamera_1a9bdb95b46d91a06cc9c9df2b9861a31c)`() const` 

#### `public void `[`position`](#classmos_1_1gfx_1_1CubeCamera_1aff8621c33265f2f766a9cb23d02fe6c7)`(const glm::vec3 & position)` 

Set position.

#### `public void `[`near_far`](#classmos_1_1gfx_1_1CubeCamera_1ad70cc12b2239d4cb35703c844b509e94)`(const float near,const float far)` 

Set near and far planes.

# class `mos::gfx::EnvironmentLight` 

Environment light, based on a cube map.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`strength`](#classmos_1_1gfx_1_1EnvironmentLight_1afa8957bd558b5b65a98127c871afded5) | Strength.
`public  `[`EnvironmentLight`](#classmos_1_1gfx_1_1EnvironmentLight_1aa07b298a6ed01ff9bdc535edfc3be561)`(const glm::vec3 & position,const glm::vec3 & extent,const float strength)` | #### Parameters
`public void `[`position`](#classmos_1_1gfx_1_1EnvironmentLight_1abcc7ae02e40a84bfb886de028a58b499)`(const glm::vec3 & position)` | Set position.
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1EnvironmentLight_1a2183528ac04afd30d6ddb72f8dca8f71)`() const` | Get position.
`public void `[`extent`](#classmos_1_1gfx_1_1EnvironmentLight_1aca0edaf4836dcbccd291f0b0a2c53dd2)`(const glm::vec3 & extent)` | Set extent and recalculate cube camera projections.
`public glm::vec3 `[`extent`](#classmos_1_1gfx_1_1EnvironmentLight_1a1fd20abd41a028c9ed42210117114ec3)`() const` | Get extent.
`public bool `[`inside`](#classmos_1_1gfx_1_1EnvironmentLight_1a3ceb3ca256985ab8d3050ad1e5dff407)`(const glm::vec3 & point) const` | Check if a point is inside the environment light box.

## Members

#### `public float `[`strength`](#classmos_1_1gfx_1_1EnvironmentLight_1afa8957bd558b5b65a98127c871afded5) 

Strength.

#### `public  `[`EnvironmentLight`](#classmos_1_1gfx_1_1EnvironmentLight_1aa07b298a6ed01ff9bdc535edfc3be561)`(const glm::vec3 & position,const glm::vec3 & extent,const float strength)` 

#### Parameters
* `extent` Describes how big the environment is, for parallax/box correction.

#### `public void `[`position`](#classmos_1_1gfx_1_1EnvironmentLight_1abcc7ae02e40a84bfb886de028a58b499)`(const glm::vec3 & position)` 

Set position.

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1EnvironmentLight_1a2183528ac04afd30d6ddb72f8dca8f71)`() const` 

Get position.

#### `public void `[`extent`](#classmos_1_1gfx_1_1EnvironmentLight_1aca0edaf4836dcbccd291f0b0a2c53dd2)`(const glm::vec3 & extent)` 

Set extent and recalculate cube camera projections.

#### `public glm::vec3 `[`extent`](#classmos_1_1gfx_1_1EnvironmentLight_1a1fd20abd41a028c9ed42210117114ec3)`() const` 

Get extent.

#### `public bool `[`inside`](#classmos_1_1gfx_1_1EnvironmentLight_1a3ceb3ca256985ab8d3050ad1e5dff407)`(const glm::vec3 & point) const` 

Check if a point is inside the environment light box.

# class `mos::gfx::Fog` 

[Fog](#classmos_1_1gfx_1_1Fog) with exponential falloff and near/far color blending.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`color_near`](#classmos_1_1gfx_1_1Fog_1a5a1f60497f2b70a68e05d547618ae6b9) | 
`public glm::vec3 `[`color_far`](#classmos_1_1gfx_1_1Fog_1a9b1d90907c0a4bb25a1112752ada41dd) | 
`public float `[`attenuation_factor`](#classmos_1_1gfx_1_1Fog_1adbe1d7b1d9caead1690e2db182b5b22d) | 
`public  `[`Fog`](#classmos_1_1gfx_1_1Fog_1a766ee01bcad685ff9102ca97a3a0dc42)`(const glm::vec3 & color,const float attenuation_factor)` | #### Parameters
`public  `[`Fog`](#classmos_1_1gfx_1_1Fog_1a874afb1ece52983adfc7735c245c57df)`(const glm::vec3 & color_near,const glm::vec3 & color_far,const float attenuation_factor)` | #### Parameters
`public  `[`~Fog`](#classmos_1_1gfx_1_1Fog_1a83b56737a4a566d6f9ead0031c04264e)`()` | 

## Members

#### `public glm::vec3 `[`color_near`](#classmos_1_1gfx_1_1Fog_1a5a1f60497f2b70a68e05d547618ae6b9) 

#### `public glm::vec3 `[`color_far`](#classmos_1_1gfx_1_1Fog_1a9b1d90907c0a4bb25a1112752ada41dd) 

#### `public float `[`attenuation_factor`](#classmos_1_1gfx_1_1Fog_1adbe1d7b1d9caead1690e2db182b5b22d) 

#### `public  `[`Fog`](#classmos_1_1gfx_1_1Fog_1a766ee01bcad685ff9102ca97a3a0dc42)`(const glm::vec3 & color,const float attenuation_factor)` 

#### Parameters
* `color` Color of the fog. 

* `attenuation_factor` [Fog](#classmos_1_1gfx_1_1Fog) density.

#### `public  `[`Fog`](#classmos_1_1gfx_1_1Fog_1a874afb1ece52983adfc7735c245c57df)`(const glm::vec3 & color_near,const glm::vec3 & color_far,const float attenuation_factor)` 

#### Parameters
* `color_near` Close fog color. 

* `color_far` Far fog color. 

* `attenuation_factor` [Fog](#classmos_1_1gfx_1_1Fog) density.

#### `public  `[`~Fog`](#classmos_1_1gfx_1_1Fog_1a83b56737a4a566d6f9ead0031c04264e)`()` 

# class `mos::gfx::Font` 

Bitmap font.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SharedTexture2D `[`texture`](#classmos_1_1gfx_1_1Font_1aa27114f7bc9ca1cb88f062ee21650369) | [Texture](#classmos_1_1gfx_1_1Texture) with characters.
`public CharMap `[`characters`](#classmos_1_1gfx_1_1Font_1aa3732644cfb855e9000f771fb476f649) | Characters supported.
`public  `[`Font`](#classmos_1_1gfx_1_1Font_1a5afa9f24d6bc450a28e3f83058d4b9e3)`(const CharMap & characters,const SharedTexture2D & texture,const float height,const float ascender,const float descender)` | #### Parameters
`public  `[`Font`](#classmos_1_1gfx_1_1Font_1af01e5ea8af03c6f41a19d2bde72a3f7d)`(const std::string & path)` | 
`public  `[`~Font`](#classmos_1_1gfx_1_1Font_1afaa80a390b383e37b9c677081e1c191c)`()` | 
`public float `[`height`](#classmos_1_1gfx_1_1Font_1aa5d6adc813a89ebca548c6f7e32bea00)`() const` | 
`public float `[`base`](#classmos_1_1gfx_1_1Font_1aeec9cc9bae9cc74b4eaa4a353ca6ebac)`() const` | 
`typedef `[`CharMap`](#classmos_1_1gfx_1_1Font_1abd108cb8ada18370b83d1f798be46d20) | 

## Members

#### `public SharedTexture2D `[`texture`](#classmos_1_1gfx_1_1Font_1aa27114f7bc9ca1cb88f062ee21650369) 

[Texture](#classmos_1_1gfx_1_1Texture) with characters.

#### `public CharMap `[`characters`](#classmos_1_1gfx_1_1Font_1aa3732644cfb855e9000f771fb476f649) 

Characters supported.

#### `public  `[`Font`](#classmos_1_1gfx_1_1Font_1a5afa9f24d6bc450a28e3f83058d4b9e3)`(const CharMap & characters,const SharedTexture2D & texture,const float height,const float ascender,const float descender)` 

#### Parameters
* `characters` Chars supported. 

* `texture` Image with glyphs.

#### `public  `[`Font`](#classmos_1_1gfx_1_1Font_1af01e5ea8af03c6f41a19d2bde72a3f7d)`(const std::string & path)` 

#### `public  `[`~Font`](#classmos_1_1gfx_1_1Font_1afaa80a390b383e37b9c677081e1c191c)`()` 

#### `public float `[`height`](#classmos_1_1gfx_1_1Font_1aa5d6adc813a89ebca548c6f7e32bea00)`() const` 

#### `public float `[`base`](#classmos_1_1gfx_1_1Font_1aeec9cc9bae9cc74b4eaa4a353ca6ebac)`() const` 

#### `typedef `[`CharMap`](#classmos_1_1gfx_1_1Font_1abd108cb8ada18370b83d1f798be46d20) 

# class `mos::gfx::Light` 

Spotlight.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`color`](#classmos_1_1gfx_1_1Light_1a098614424fd86b98f4bc6b843db18a05) | 
`public float `[`strength`](#classmos_1_1gfx_1_1Light_1a5af6106c3843916ee943eecf4efe6a8a) | Strength of the lamp in watts.
`public `[`Camera`](#classmos_1_1gfx_1_1Camera)` `[`camera`](#classmos_1_1gfx_1_1Light_1aaacd4a39ff42cbb55af1c398fb6a9347) | [Camera](#classmos_1_1gfx_1_1Camera) for shadow map rendering.
`public  explicit `[`Light`](#classmos_1_1gfx_1_1Light_1a70ef9d61321a9839cdc5848319b87ffe)`(const glm::vec3 & position,const glm::vec3 & center,const float angle,const glm::vec3 & color,const float strength,const float near,const float far)` | 
`public virtual  `[`~Light`](#classmos_1_1gfx_1_1Light_1a8f682ec6664dc9869edbb915bd8c2085)`()` | 
`public void `[`angle`](#classmos_1_1gfx_1_1Light_1aa81a46fe66ace4ed5c374c2aba31e36a)`(const float angle)` | Set spot angle, in radans.
`public float `[`angle`](#classmos_1_1gfx_1_1Light_1a4e6533c02cd9aff2ae63fbf3d06ed2a1)`() const` | 
`public void `[`position`](#classmos_1_1gfx_1_1Light_1a08798cb4d85ef81a8d07f1aa44017233)`(const glm::vec3 & position)` | Set position.
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Light_1aa6f650a461a28d9d9466f60109e21c36)`() const` | 
`public void `[`center`](#classmos_1_1gfx_1_1Light_1aa84b55e6bc57833ce732a8a4688f9c47)`(const glm::vec3 & center)` | Set center/focus point.
`public glm::vec3 `[`center`](#classmos_1_1gfx_1_1Light_1aaa0d715e314e2be7d5290ecf702e813b)`() const` | 
`public glm::vec3 `[`direction`](#classmos_1_1gfx_1_1Light_1afd7e31e2adca30413718dccfef410c28)`() const` | 
`public void `[`near_far`](#classmos_1_1gfx_1_1Light_1adc14ff0dbf9ca62c86c0792c19c3e83a)`(const float near,const float far)` | Set near and far plane.

## Members

#### `public glm::vec3 `[`color`](#classmos_1_1gfx_1_1Light_1a098614424fd86b98f4bc6b843db18a05) 

#### `public float `[`strength`](#classmos_1_1gfx_1_1Light_1a5af6106c3843916ee943eecf4efe6a8a) 

Strength of the lamp in watts.

#### `public `[`Camera`](#classmos_1_1gfx_1_1Camera)` `[`camera`](#classmos_1_1gfx_1_1Light_1aaacd4a39ff42cbb55af1c398fb6a9347) 

[Camera](#classmos_1_1gfx_1_1Camera) for shadow map rendering.

#### `public  explicit `[`Light`](#classmos_1_1gfx_1_1Light_1a70ef9d61321a9839cdc5848319b87ffe)`(const glm::vec3 & position,const glm::vec3 & center,const float angle,const glm::vec3 & color,const float strength,const float near,const float far)` 

#### `public virtual  `[`~Light`](#classmos_1_1gfx_1_1Light_1a8f682ec6664dc9869edbb915bd8c2085)`()` 

#### `public void `[`angle`](#classmos_1_1gfx_1_1Light_1aa81a46fe66ace4ed5c374c2aba31e36a)`(const float angle)` 

Set spot angle, in radans.

#### `public float `[`angle`](#classmos_1_1gfx_1_1Light_1a4e6533c02cd9aff2ae63fbf3d06ed2a1)`() const` 

#### `public void `[`position`](#classmos_1_1gfx_1_1Light_1a08798cb4d85ef81a8d07f1aa44017233)`(const glm::vec3 & position)` 

Set position.

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Light_1aa6f650a461a28d9d9466f60109e21c36)`() const` 

#### `public void `[`center`](#classmos_1_1gfx_1_1Light_1aa84b55e6bc57833ce732a8a4688f9c47)`(const glm::vec3 & center)` 

Set center/focus point.

#### `public glm::vec3 `[`center`](#classmos_1_1gfx_1_1Light_1aaa0d715e314e2be7d5290ecf702e813b)`() const` 

#### `public glm::vec3 `[`direction`](#classmos_1_1gfx_1_1Light_1afd7e31e2adca30413718dccfef410c28)`() const` 

#### `public void `[`near_far`](#classmos_1_1gfx_1_1Light_1adc14ff0dbf9ca62c86c0792c19c3e83a)`(const float near,const float far)` 

Set near and far plane.

# class `mos::gfx::Material` 

Physically based material.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`albedo`](#classmos_1_1gfx_1_1Material_1aa38b654c9ba5db156a60959937500b5f) | 
`public glm::vec3 `[`emission`](#classmos_1_1gfx_1_1Material_1a951edf7d75464ecc6c48f8b3e7c9c813) | 
`public glm::vec3 `[`factor`](#classmos_1_1gfx_1_1Material_1a1269979ab07c98aa3cbc8365aded3192) | 
`public float `[`opacity`](#classmos_1_1gfx_1_1Material_1ac60f0458e10d161115db5096c97175b7) | 
`public float `[`roughness`](#classmos_1_1gfx_1_1Material_1af43f0a50a7a6a17abe71f154dbf63e5a) | 
`public float `[`metallic`](#classmos_1_1gfx_1_1Material_1a6f5bc6244db40c4f1b55e983843f760e) | 
`public float `[`emission_strength`](#classmos_1_1gfx_1_1Material_1a0a9f5daac647fe1dfaaa00cca2db7b56) | 
`public float `[`ambient_occlusion`](#classmos_1_1gfx_1_1Material_1a6cd47e0d34ac4da35c725a6f8db03c98) | 
`public SharedTexture2D `[`albedo_map`](#classmos_1_1gfx_1_1Material_1a2964fe6acb2d4f205f37532e33ec78fc) | 
`public SharedTexture2D `[`emission_map`](#classmos_1_1gfx_1_1Material_1a0f576662f9f9064b6f18de67f0dc8b85) | 
`public SharedTexture2D `[`normal_map`](#classmos_1_1gfx_1_1Material_1a181562b08ce29baf3559c4574a9c1683) | 
`public SharedTexture2D `[`metallic_map`](#classmos_1_1gfx_1_1Material_1a3d1b79e19f7a7c591b4261c3c3770da7) | 
`public SharedTexture2D `[`roughness_map`](#classmos_1_1gfx_1_1Material_1ac68594310abe20cd98cd0cfe450da7c7) | 
`public SharedTexture2D `[`ambient_occlusion_map`](#classmos_1_1gfx_1_1Material_1a969e97274c4c25ee0371d797912ca757) | 
`public  explicit `[`Material`](#classmos_1_1gfx_1_1Material_1a44a9ae3f4a7d8a75ed905571b872aec5)`(const SharedTexture2D & albedo_map,const SharedTexture2D & emission_map,const SharedTexture2D & normal_map,const SharedTexture2D & metallic_map,const SharedTexture2D & roughness_map,const SharedTexture2D & ambient_occlusion_map,const glm::vec3 & albedo,const float opacity,const float roughness,const float metallic,const glm::vec3 & emission,const float ambient_occlusion)` | 
`public  explicit `[`Material`](#classmos_1_1gfx_1_1Material_1a932712498402df8de28b4612ed811d9e)`(const glm::vec3 & albedo,const float opacity,const float roughness,const float metallic,const glm::vec3 & emission,const float ambient_occlusion)` | 
`public virtual  `[`~Material`](#classmos_1_1gfx_1_1Material_1a39dd56042706fffd6319ebdbdba293c1)`()` | 

## Members

#### `public glm::vec3 `[`albedo`](#classmos_1_1gfx_1_1Material_1aa38b654c9ba5db156a60959937500b5f) 

#### `public glm::vec3 `[`emission`](#classmos_1_1gfx_1_1Material_1a951edf7d75464ecc6c48f8b3e7c9c813) 

#### `public glm::vec3 `[`factor`](#classmos_1_1gfx_1_1Material_1a1269979ab07c98aa3cbc8365aded3192) 

#### `public float `[`opacity`](#classmos_1_1gfx_1_1Material_1ac60f0458e10d161115db5096c97175b7) 

#### `public float `[`roughness`](#classmos_1_1gfx_1_1Material_1af43f0a50a7a6a17abe71f154dbf63e5a) 

#### `public float `[`metallic`](#classmos_1_1gfx_1_1Material_1a6f5bc6244db40c4f1b55e983843f760e) 

#### `public float `[`emission_strength`](#classmos_1_1gfx_1_1Material_1a0a9f5daac647fe1dfaaa00cca2db7b56) 

#### `public float `[`ambient_occlusion`](#classmos_1_1gfx_1_1Material_1a6cd47e0d34ac4da35c725a6f8db03c98) 

#### `public SharedTexture2D `[`albedo_map`](#classmos_1_1gfx_1_1Material_1a2964fe6acb2d4f205f37532e33ec78fc) 

#### `public SharedTexture2D `[`emission_map`](#classmos_1_1gfx_1_1Material_1a0f576662f9f9064b6f18de67f0dc8b85) 

#### `public SharedTexture2D `[`normal_map`](#classmos_1_1gfx_1_1Material_1a181562b08ce29baf3559c4574a9c1683) 

#### `public SharedTexture2D `[`metallic_map`](#classmos_1_1gfx_1_1Material_1a3d1b79e19f7a7c591b4261c3c3770da7) 

#### `public SharedTexture2D `[`roughness_map`](#classmos_1_1gfx_1_1Material_1ac68594310abe20cd98cd0cfe450da7c7) 

#### `public SharedTexture2D `[`ambient_occlusion_map`](#classmos_1_1gfx_1_1Material_1a969e97274c4c25ee0371d797912ca757) 

#### `public  explicit `[`Material`](#classmos_1_1gfx_1_1Material_1a44a9ae3f4a7d8a75ed905571b872aec5)`(const SharedTexture2D & albedo_map,const SharedTexture2D & emission_map,const SharedTexture2D & normal_map,const SharedTexture2D & metallic_map,const SharedTexture2D & roughness_map,const SharedTexture2D & ambient_occlusion_map,const glm::vec3 & albedo,const float opacity,const float roughness,const float metallic,const glm::vec3 & emission,const float ambient_occlusion)` 

#### `public  explicit `[`Material`](#classmos_1_1gfx_1_1Material_1a932712498402df8de28b4612ed811d9e)`(const glm::vec3 & albedo,const float opacity,const float roughness,const float metallic,const glm::vec3 & emission,const float ambient_occlusion)` 

#### `public virtual  `[`~Material`](#classmos_1_1gfx_1_1Material_1a39dd56042706fffd6319ebdbdba293c1)`()` 

# class `mos::gfx::Mesh` 

```
class mos::gfx::Mesh
  : public mos::gfx::Shape
```  

Geometric data description.

Vertices and optional indices for rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`TrackedContainer](#classmos_1_1TrackedContainer)< [Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`vertices`](#classmos_1_1gfx_1_1Mesh_1a0e494934622e7e296ef16a6e0b6da752) | 
`public `[`TrackedContainer`](#classmos_1_1TrackedContainer)`< Triangle > `[`triangles`](#classmos_1_1gfx_1_1Mesh_1a57a349609b46bee0589f40daefe83706) | 
`public template<>`  <br/>`inline  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1a2e8e4cc39ac58a57deb5f1978c00a953)`(const Tv vertices_begin,const Tv vertices_end,Te triangles_begin,Te triangles_end)` | 
`public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1aa923071477d7b78f1f248456c00362ba)`(const std::initializer_list< `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` > & vertices,const std::initializer_list< Triangle > & triangles)` | 
`public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1aa67043af488f25f345a589abe6bcbadf)`(const std::string & path)` | Load from *.mesh file.
`public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1a5cafbeba800578f8de106e795d8a205c)`()` | 
`public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1ab03aebb6486caf6aef4640cea80d5992)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh)` | 
`public  `[`~Mesh`](#classmos_1_1gfx_1_1Mesh_1a597785ccefad3298f7114d4b6e4c146d)`()` | 
`public void `[`clear`](#classmos_1_1gfx_1_1Mesh_1afc095bb5ef2e4e5c7e88ec3d7b18560e)`()` | Erease all vertices and indices.
`public Positions `[`positions`](#classmos_1_1gfx_1_1Mesh_1a6c1f7d95f35ae06d9236e8e6f3dfb30f)`() const` | Get only positions from vertices.
`public void `[`mix`](#classmos_1_1gfx_1_1Mesh_1a0a589f065bfcfc3d39d7cacc3008c15a)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh1,const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh2,const float amount)` | 
`public void `[`apply_transform`](#classmos_1_1gfx_1_1Mesh_1a043bc8abf4f5bdb57edc929847b13430)`(const glm::mat4 & transform)` | 
`public void `[`calculate_normals`](#classmos_1_1gfx_1_1Mesh_1a46840e792ab3d9b59591b26e30978944)`()` | 
`public void `[`calculate_flat_normals`](#classmos_1_1gfx_1_1Mesh_1a5d578899d0c4bb281c0dc8359e625aed)`()` | 
`public void `[`calculate_tangents`](#classmos_1_1gfx_1_1Mesh_1a308a9fb4a97d6120f877d05b6bdb892f)`()` | 
`typedef `[`Positions`](#classmos_1_1gfx_1_1Mesh_1a67e8dfefa95500759b6b63a67fe647e0) | 
`typedef `[`TimePoint`](#classmos_1_1gfx_1_1Mesh_1a8ce9672417cdd0fd183ba7b2b3b9f06f) | 

## Members

#### `public `[`TrackedContainer](#classmos_1_1TrackedContainer)< [Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`vertices`](#classmos_1_1gfx_1_1Mesh_1a0e494934622e7e296ef16a6e0b6da752) 

#### `public `[`TrackedContainer`](#classmos_1_1TrackedContainer)`< Triangle > `[`triangles`](#classmos_1_1gfx_1_1Mesh_1a57a349609b46bee0589f40daefe83706) 

#### `public template<>`  <br/>`inline  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1a2e8e4cc39ac58a57deb5f1978c00a953)`(const Tv vertices_begin,const Tv vertices_end,Te triangles_begin,Te triangles_end)` 

#### `public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1aa923071477d7b78f1f248456c00362ba)`(const std::initializer_list< `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` > & vertices,const std::initializer_list< Triangle > & triangles)` 

#### `public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1aa67043af488f25f345a589abe6bcbadf)`(const std::string & path)` 

Load from *.mesh file.

#### Parameters
* `path` Full path

#### `public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1a5cafbeba800578f8de106e795d8a205c)`()` 

#### `public  `[`Mesh`](#classmos_1_1gfx_1_1Mesh_1ab03aebb6486caf6aef4640cea80d5992)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh)` 

#### `public  `[`~Mesh`](#classmos_1_1gfx_1_1Mesh_1a597785ccefad3298f7114d4b6e4c146d)`()` 

#### `public void `[`clear`](#classmos_1_1gfx_1_1Mesh_1afc095bb5ef2e4e5c7e88ec3d7b18560e)`()` 

Erease all vertices and indices.

#### `public Positions `[`positions`](#classmos_1_1gfx_1_1Mesh_1a6c1f7d95f35ae06d9236e8e6f3dfb30f)`() const` 

Get only positions from vertices.

#### `public void `[`mix`](#classmos_1_1gfx_1_1Mesh_1a0a589f065bfcfc3d39d7cacc3008c15a)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh1,const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh2,const float amount)` 

#### `public void `[`apply_transform`](#classmos_1_1gfx_1_1Mesh_1a043bc8abf4f5bdb57edc929847b13430)`(const glm::mat4 & transform)` 

#### `public void `[`calculate_normals`](#classmos_1_1gfx_1_1Mesh_1a46840e792ab3d9b59591b26e30978944)`()` 

#### `public void `[`calculate_flat_normals`](#classmos_1_1gfx_1_1Mesh_1a5d578899d0c4bb281c0dc8359e625aed)`()` 

#### `public void `[`calculate_tangents`](#classmos_1_1gfx_1_1Mesh_1a308a9fb4a97d6120f877d05b6bdb892f)`()` 

#### `typedef `[`Positions`](#classmos_1_1gfx_1_1Mesh_1a67e8dfefa95500759b6b63a67fe647e0) 

#### `typedef `[`TimePoint`](#classmos_1_1gfx_1_1Mesh_1a8ce9672417cdd0fd183ba7b2b3b9f06f) 

# class `mos::gfx::Model` 

Collection of properties to render an object.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SharedMesh `[`mesh`](#classmos_1_1gfx_1_1Model_1aa75e603b8721b55bce26aa43ebb27850) | A mesh shape.
`public `[`Material`](#classmos_1_1gfx_1_1Material)` `[`material`](#classmos_1_1gfx_1_1Model_1a82d469a0100df84c903970a7c804ad02) | A material.
`public glm::mat4 `[`transform`](#classmos_1_1gfx_1_1Model_1a5530e329e1f330417ecb1a0ce97e08f6) | A transform.
`public `[`Models`](#classmos_1_1Container)` `[`models`](#classmos_1_1gfx_1_1Model_1a493aa027c8f850a678dcd932caec602a) | Children models.
`public  `[`Model`](#classmos_1_1gfx_1_1Model_1abbc3b797fbfc131a8755977b02cc3fed)`()` | 
`public  `[`Model`](#classmos_1_1gfx_1_1Model_1a305edc8148ace55e5c076d9ebce2cb4f)`(const std::string & name,const SharedMesh & mesh,const glm::mat4 & transform,const `[`Material`](#classmos_1_1gfx_1_1Material)` & material)` | 
`public  `[`~Model`](#classmos_1_1gfx_1_1Model_1a39c8ab83580f5b1c72d844ef2258e56b)`()` | 
`public std::string `[`name`](#classmos_1_1gfx_1_1Model_1ad827793a20a065fa22f4134dfbb4fbc7)`() const` | 
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Model_1a3ada7b390841e934d47ad9d0fca33897)`() const` | 
`public void `[`position`](#classmos_1_1gfx_1_1Model_1a2457830d3816e8136803cd9c26e84a0a)`(const glm::vec3 & position)` | Set position.

## Members

#### `public SharedMesh `[`mesh`](#classmos_1_1gfx_1_1Model_1aa75e603b8721b55bce26aa43ebb27850) 

A mesh shape.

#### `public `[`Material`](#classmos_1_1gfx_1_1Material)` `[`material`](#classmos_1_1gfx_1_1Model_1a82d469a0100df84c903970a7c804ad02) 

A material.

#### `public glm::mat4 `[`transform`](#classmos_1_1gfx_1_1Model_1a5530e329e1f330417ecb1a0ce97e08f6) 

A transform.

#### `public `[`Models`](#classmos_1_1Container)` `[`models`](#classmos_1_1gfx_1_1Model_1a493aa027c8f850a678dcd932caec602a) 

Children models.

#### `public  `[`Model`](#classmos_1_1gfx_1_1Model_1abbc3b797fbfc131a8755977b02cc3fed)`()` 

#### `public  `[`Model`](#classmos_1_1gfx_1_1Model_1a305edc8148ace55e5c076d9ebce2cb4f)`(const std::string & name,const SharedMesh & mesh,const glm::mat4 & transform,const `[`Material`](#classmos_1_1gfx_1_1Material)` & material)` 

#### `public  `[`~Model`](#classmos_1_1gfx_1_1Model_1a39c8ab83580f5b1c72d844ef2258e56b)`()` 

#### `public std::string `[`name`](#classmos_1_1gfx_1_1Model_1ad827793a20a065fa22f4134dfbb4fbc7)`() const` 

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Model_1a3ada7b390841e934d47ad9d0fca33897)`() const` 

#### `public void `[`position`](#classmos_1_1gfx_1_1Model_1a2457830d3816e8136803cd9c26e84a0a)`(const glm::vec3 & position)` 

Set position.

# class `mos::gfx::Particle` 

[Particle](#classmos_1_1gfx_1_1Particle) used in a particle system.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Particle_1af4ef2eefd3d8a5af9a5014f4e0f82922) | 
`public glm::vec4 `[`color`](#classmos_1_1gfx_1_1Particle_1aa2527fee1e988ddd277d8644ed0a8778) | 
`public float `[`size`](#classmos_1_1gfx_1_1Particle_1a0ed9f5071df578f7d1f1fcfd0be97c76) | 
`public float `[`opacity`](#classmos_1_1gfx_1_1Particle_1a02e4e65d85692b16d9a58a0b47d3fbe8) | 
`public inline  explicit `[`Particle`](#classmos_1_1gfx_1_1Particle_1a801b9af4655db66f33d673ed77efb5b5)`(const glm::vec3 & position,const glm::vec4 & color,const float size,const float opacity)` | 
`public inline  `[`~Particle`](#classmos_1_1gfx_1_1Particle_1aeba188944ef19b2ebdd922328159976c)`()` | 

## Members

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Particle_1af4ef2eefd3d8a5af9a5014f4e0f82922) 

#### `public glm::vec4 `[`color`](#classmos_1_1gfx_1_1Particle_1aa2527fee1e988ddd277d8644ed0a8778) 

#### `public float `[`size`](#classmos_1_1gfx_1_1Particle_1a0ed9f5071df578f7d1f1fcfd0be97c76) 

#### `public float `[`opacity`](#classmos_1_1gfx_1_1Particle_1a02e4e65d85692b16d9a58a0b47d3fbe8) 

#### `public inline  explicit `[`Particle`](#classmos_1_1gfx_1_1Particle_1a801b9af4655db66f33d673ed77efb5b5)`(const glm::vec3 & position,const glm::vec4 & color,const float size,const float opacity)` 

#### `public inline  `[`~Particle`](#classmos_1_1gfx_1_1Particle_1aeba188944ef19b2ebdd922328159976c)`()` 

# class `mos::gfx::ParticleCloud` 

```
class mos::gfx::ParticleCloud
  : public mos::gfx::Shape
```  

Collection of same particles for rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SharedTexture2D `[`emission_map`](#classmos_1_1gfx_1_1ParticleCloud_1a6c55beea262fdfe4e7e82dfea4ffda0b) | [Texture](#classmos_1_1gfx_1_1Texture) for all particles.
`public `[`Particles`](#classmos_1_1TrackedContainer)` `[`particles`](#classmos_1_1gfx_1_1ParticleCloud_1a4971aa1ba37045e06b8539a392e456bd) | Particles.
`public  `[`ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud_1ad6f4dfc17fa0b9f5660eb2a56c869c93)`()` | 
`public  `[`ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud_1a3213d588f533f6baa8d4ab171a9f85c3)`(const SharedTexture2D & emission_map,const `[`Particles`](#classmos_1_1TrackedContainer)` & particles)` | 
`public  `[`~ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud_1a9d8d8e9a301377f5ebd84c5d235eeeb8)`()` | 
`public void `[`sort`](#classmos_1_1gfx_1_1ParticleCloud_1ab65a8c95329d16a5517f3b0e360f7781)`(const glm::vec3 & position)` | Sort particles relative to a position.

## Members

#### `public SharedTexture2D `[`emission_map`](#classmos_1_1gfx_1_1ParticleCloud_1a6c55beea262fdfe4e7e82dfea4ffda0b) 

[Texture](#classmos_1_1gfx_1_1Texture) for all particles.

#### `public `[`Particles`](#classmos_1_1TrackedContainer)` `[`particles`](#classmos_1_1gfx_1_1ParticleCloud_1a4971aa1ba37045e06b8539a392e456bd) 

Particles.

#### `public  `[`ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud_1ad6f4dfc17fa0b9f5660eb2a56c869c93)`()` 

#### `public  `[`ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud_1a3213d588f533f6baa8d4ab171a9f85c3)`(const SharedTexture2D & emission_map,const `[`Particles`](#classmos_1_1TrackedContainer)` & particles)` 

#### `public  `[`~ParticleCloud`](#classmos_1_1gfx_1_1ParticleCloud_1a9d8d8e9a301377f5ebd84c5d235eeeb8)`()` 

#### `public void `[`sort`](#classmos_1_1gfx_1_1ParticleCloud_1ab65a8c95329d16a5517f3b0e360f7781)`(const glm::vec3 & position)` 

Sort particles relative to a position.

# class `mos::gfx::Renderer` 

Render geometry shapes with OpenGL.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Renderer`](#classmos_1_1gfx_1_1Renderer_1ab7434597c696eeea68af4fb6093da4aa)`(const glm::vec4 & color,const glm::ivec2 & resolution)` | Inits the renderer, creates an OpenGL context with GLAD.
`public  `[`~Renderer`](#classmos_1_1gfx_1_1Renderer_1ac4b26e520c27342a1cb183290ed53f06)`()` | 
`public void `[`load`](#classmos_1_1gfx_1_1Renderer_1ad792447a8c6c2d8330a15b42a2a75143)`(const `[`Model`](#classmos_1_1gfx_1_1Model)` & model)` | Loads a model into renderers own memory.
`public void `[`load`](#classmos_1_1gfx_1_1Renderer_1ab165dc0a2f5641294fcd405dc346dbab)`(const `[`Models`](#classmos_1_1Container)` & models)` | 
`public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1a38d8681b16eb91431b2dfeb5e1352e4f)`(const `[`Model`](#classmos_1_1gfx_1_1Model)` & model)` | Unloads a model from renderers own memory.
`public void `[`load`](#classmos_1_1gfx_1_1Renderer_1a271a009d7b12c4210d19364133d816df)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh)` | Load a mesh in to memory.
`public void `[`load`](#classmos_1_1gfx_1_1Renderer_1a4f7ef9c2324c2e8c2f9163e6cd61b680)`(const SharedMesh & mesh)` | 
`public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1a9116a2b3aed22181ec198b2e69704ff3)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh)` | Unloads a mesh from memory.
`public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1a77eb66b35ee5ef3846daabe85c26ba08)`(const SharedMesh & mesh)` | 
`public void `[`load`](#classmos_1_1gfx_1_1Renderer_1a890235573398d0fa73e419263ff61005)`(const SharedTexture2D & texture)` | Loads a shared texture into renderer memory.
`public void `[`load_or_update`](#classmos_1_1gfx_1_1Renderer_1a4c57c5ae668e4949b216ea9f0c629012)`(const `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D)` & texture)` | Loads a texture into renderer memory.
`public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1acd7ab01dffe51c8390813107f89f6abc)`(const SharedTexture2D & texture)` | Unloads a shared texture from renderer memory.
`public void `[`render`](#classmos_1_1gfx_1_1Renderer_1a971508da9094c371eeeb1d04852b14fb)`(const `[`Scenes`](#classmos_1_1Container)` & scenes,const glm::vec4 & color,const glm::ivec2 & resolution)` | Render multiple scenes.
`public void `[`clear_buffers`](#classmos_1_1gfx_1_1Renderer_1a301c362962e97de48b9f745180c9226c)`()` | Clear all internal buffers/memory.

## Members

#### `public  `[`Renderer`](#classmos_1_1gfx_1_1Renderer_1ab7434597c696eeea68af4fb6093da4aa)`(const glm::vec4 & color,const glm::ivec2 & resolution)` 

Inits the renderer, creates an OpenGL context with GLAD.

#### `public  `[`~Renderer`](#classmos_1_1gfx_1_1Renderer_1ac4b26e520c27342a1cb183290ed53f06)`()` 

#### `public void `[`load`](#classmos_1_1gfx_1_1Renderer_1ad792447a8c6c2d8330a15b42a2a75143)`(const `[`Model`](#classmos_1_1gfx_1_1Model)` & model)` 

Loads a model into renderers own memory.

#### `public void `[`load`](#classmos_1_1gfx_1_1Renderer_1ab165dc0a2f5641294fcd405dc346dbab)`(const `[`Models`](#classmos_1_1Container)` & models)` 

#### `public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1a38d8681b16eb91431b2dfeb5e1352e4f)`(const `[`Model`](#classmos_1_1gfx_1_1Model)` & model)` 

Unloads a model from renderers own memory.

#### `public void `[`load`](#classmos_1_1gfx_1_1Renderer_1a271a009d7b12c4210d19364133d816df)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh)` 

Load a mesh in to memory.

#### `public void `[`load`](#classmos_1_1gfx_1_1Renderer_1a4f7ef9c2324c2e8c2f9163e6cd61b680)`(const SharedMesh & mesh)` 

#### `public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1a9116a2b3aed22181ec198b2e69704ff3)`(const `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh)` 

Unloads a mesh from memory.

#### `public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1a77eb66b35ee5ef3846daabe85c26ba08)`(const SharedMesh & mesh)` 

#### `public void `[`load`](#classmos_1_1gfx_1_1Renderer_1a890235573398d0fa73e419263ff61005)`(const SharedTexture2D & texture)` 

Loads a shared texture into renderer memory.

#### `public void `[`load_or_update`](#classmos_1_1gfx_1_1Renderer_1a4c57c5ae668e4949b216ea9f0c629012)`(const `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D)` & texture)` 

Loads a texture into renderer memory.

#### `public void `[`unload`](#classmos_1_1gfx_1_1Renderer_1acd7ab01dffe51c8390813107f89f6abc)`(const SharedTexture2D & texture)` 

Unloads a shared texture from renderer memory.

#### `public void `[`render`](#classmos_1_1gfx_1_1Renderer_1a971508da9094c371eeeb1d04852b14fb)`(const `[`Scenes`](#classmos_1_1Container)` & scenes,const glm::vec4 & color,const glm::ivec2 & resolution)` 

Render multiple scenes.

#### `public void `[`clear_buffers`](#classmos_1_1gfx_1_1Renderer_1a301c362962e97de48b9f745180c9226c)`()` 

Clear all internal buffers/memory.

# class `mos::gfx::Scene` 

[Scene](#classmos_1_1gfx_1_1Scene) for rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`Models`](#classmos_1_1Container)` `[`models`](#classmos_1_1gfx_1_1Scene_1a00122a1e7b77db4369d25325c9371f75) | 
`public `[`ParticleClouds`](#classmos_1_1Container)` `[`particle_clouds`](#classmos_1_1gfx_1_1Scene_1a2c02c6141fe312aa8e3496fc0d6117b2) | 
`public `[`Boxes`](#classmos_1_1Container)` `[`boxes`](#classmos_1_1gfx_1_1Scene_1af5ba1dc56b23c9f6b7ceb20db6592af4) | 
`public Lights `[`lights`](#classmos_1_1gfx_1_1Scene_1a20622e447e99b23365cdd302068d6f95) | 
`public `[`Camera`](#classmos_1_1gfx_1_1Camera)` `[`camera`](#classmos_1_1gfx_1_1Scene_1aa200941f51f1b6421181703374f7cb6d) | 
`public `[`Fog`](#classmos_1_1gfx_1_1Fog)` `[`fog`](#classmos_1_1gfx_1_1Scene_1a3e09879212d8dbdfc3f4ea587516b37b) | 
`public EnvironmentLights `[`environment_lights`](#classmos_1_1gfx_1_1Scene_1a16419cce6147cab762909af9feaddcd9) | 
`public `[`TextureTargets`](#classmos_1_1Container)` `[`texture_targets`](#classmos_1_1gfx_1_1Scene_1aaaf0777b791ef47c0af027e95d39ceb1) | 
`public  `[`Scene`](#classmos_1_1gfx_1_1Scene_1af3e3b1c871ee6bd7abbcf6f7b5d7407f)`()` | 
`public  `[`Scene`](#classmos_1_1gfx_1_1Scene_1abfda5ca770868181d8535f9a68a10bd7)`(const `[`Models`](#classmos_1_1Container)` & models,const `[`Camera`](#classmos_1_1gfx_1_1Camera)` & camera,const Lights & lights,const `[`Fog`](#classmos_1_1gfx_1_1Fog)` & fog,const EnvironmentLights & environment_lights,const `[`Boxes`](#classmos_1_1Container)` & boxes)` | 

## Members

#### `public `[`Models`](#classmos_1_1Container)` `[`models`](#classmos_1_1gfx_1_1Scene_1a00122a1e7b77db4369d25325c9371f75) 

#### `public `[`ParticleClouds`](#classmos_1_1Container)` `[`particle_clouds`](#classmos_1_1gfx_1_1Scene_1a2c02c6141fe312aa8e3496fc0d6117b2) 

#### `public `[`Boxes`](#classmos_1_1Container)` `[`boxes`](#classmos_1_1gfx_1_1Scene_1af5ba1dc56b23c9f6b7ceb20db6592af4) 

#### `public Lights `[`lights`](#classmos_1_1gfx_1_1Scene_1a20622e447e99b23365cdd302068d6f95) 

#### `public `[`Camera`](#classmos_1_1gfx_1_1Camera)` `[`camera`](#classmos_1_1gfx_1_1Scene_1aa200941f51f1b6421181703374f7cb6d) 

#### `public `[`Fog`](#classmos_1_1gfx_1_1Fog)` `[`fog`](#classmos_1_1gfx_1_1Scene_1a3e09879212d8dbdfc3f4ea587516b37b) 

#### `public EnvironmentLights `[`environment_lights`](#classmos_1_1gfx_1_1Scene_1a16419cce6147cab762909af9feaddcd9) 

#### `public `[`TextureTargets`](#classmos_1_1Container)` `[`texture_targets`](#classmos_1_1gfx_1_1Scene_1aaaf0777b791ef47c0af027e95d39ceb1) 

#### `public  `[`Scene`](#classmos_1_1gfx_1_1Scene_1af3e3b1c871ee6bd7abbcf6f7b5d7407f)`()` 

#### `public  `[`Scene`](#classmos_1_1gfx_1_1Scene_1abfda5ca770868181d8535f9a68a10bd7)`(const `[`Models`](#classmos_1_1Container)` & models,const `[`Camera`](#classmos_1_1gfx_1_1Camera)` & camera,const Lights & lights,const `[`Fog`](#classmos_1_1gfx_1_1Fog)` & fog,const EnvironmentLights & environment_lights,const `[`Boxes`](#classmos_1_1Container)` & boxes)` 

# class `mos::gfx::Shape` 

Base class for geometric shapes.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Shape`](#classmos_1_1gfx_1_1Shape_1a8c1d67b19ec21a09a0841e699b27da2a)`()` | 
`public unsigned int `[`id`](#classmos_1_1gfx_1_1Shape_1a6c04e390b183ce826964fb8af29c53c8)`() const` | Unique id.

## Members

#### `public  `[`Shape`](#classmos_1_1gfx_1_1Shape_1a8c1d67b19ec21a09a0841e699b27da2a)`()` 

#### `public unsigned int `[`id`](#classmos_1_1gfx_1_1Shape_1a6c04e390b183ce826964fb8af29c53c8)`() const` 

Unique id.

# class `mos::gfx::Target` 

Off screen rendering target.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Target`](#classmos_1_1gfx_1_1Target_1a3510cd0596dfd2fbf6f0fe45df09da66)`()` | 
`public unsigned int `[`id`](#classmos_1_1gfx_1_1Target_1a6dde5268529a0af4adbceced99609e5b)`() const` | Unique id.

## Members

#### `public  `[`Target`](#classmos_1_1gfx_1_1Target_1a3510cd0596dfd2fbf6f0fe45df09da66)`()` 

#### `public unsigned int `[`id`](#classmos_1_1gfx_1_1Target_1a6dde5268529a0af4adbceced99609e5b)`() const` 

Unique id.

# class `mos::gfx::Text` 

[Text](#classmos_1_1gfx_1_1Text) for rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`spacing`](#classmos_1_1gfx_1_1Text_1a463688f94dcd762b0836a2f4bf4ffe9c) | 
`public  `[`Text`](#classmos_1_1gfx_1_1Text_1a9f435f10d019b136450124f8b61ff500)`(const std::string & text,const `[`Font`](#classmos_1_1gfx_1_1Font)` & font,const glm::mat4 & transform,const bool emissive,const float spacing)` | 
`public virtual  `[`~Text`](#classmos_1_1gfx_1_1Text_1a8051864d9344603946450b80de883ff2)`()` | 
`public void `[`text`](#classmos_1_1gfx_1_1Text_1a440d59aa96745e9824f8b904c19e6359)`(const std::string & text)` | Set text.
`public std::string `[`text`](#classmos_1_1gfx_1_1Text_1a71e0d89c8e24b02acd8b2e1d758e4be2)`() const` | Get text.
`public float `[`width`](#classmos_1_1gfx_1_1Text_1a2fb11ee46a1d4b930f57381faecd65c8)`() const` | Approximate width.
`public float `[`height`](#classmos_1_1gfx_1_1Text_1a7bd81108012fe76d1391db42a475e5b4)`() const` | Approximate height.
`public void `[`position`](#classmos_1_1gfx_1_1Text_1a4db76ba7ff9bbd6819619ca306f1156c)`(const glm::vec2 & position)` | Set position.
`public void `[`position`](#classmos_1_1gfx_1_1Text_1a9982b4cfcfcc47d19a963518f4af0eb1)`(const glm::vec3 & position)` | Set position.
`public glm::vec2 `[`position`](#classmos_1_1gfx_1_1Text_1a51527f82c80a3724cf0d323562e162c7)`() const` | Get position.
`public void `[`scale`](#classmos_1_1gfx_1_1Text_1a315892d1ab3c0514ff7eb7833497562b)`(const float scale)` | 
`public void `[`material`](#classmos_1_1gfx_1_1Text_1adb8d3a962001dc4b32c17857b242e1f6)`(const `[`Material`](#classmos_1_1gfx_1_1Material)` & material)` | Set material.
`public void `[`transform`](#classmos_1_1gfx_1_1Text_1aaeb6a47cb47da85f0b0c2667aa5fb8fc)`(const glm::mat4 & transform)` | Set transform.
`public glm::mat4 `[`transform`](#classmos_1_1gfx_1_1Text_1a5491211bb937914e0338bb0734d56115)`() const` | Get transform.
`public `[`Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1Text_1af28a9439ce9df18f321ee33d843bc8e0)`() const` | Get model.
`public void `[`emissive`](#classmos_1_1gfx_1_1Text_1a85057fa4ec6a975b600f2b2706fee641)`(const bool emissive)` | Set if the text is emissive.
`public void `[`factor`](#classmos_1_1gfx_1_1Text_1a370e5445199b6c348be8b00eaef1ff2e)`(const glm::vec3 & factor)` | Set the color multiplier for the text.
`public void `[`opacity`](#classmos_1_1gfx_1_1Text_1af085194277f54392eb4b0783ea6eb70e)`(const float & opacity)` | Set opacity of text.
`public void `[`emission_strength`](#classmos_1_1gfx_1_1Text_1a71ce5b960ede5d0c7bb5746ba784ab6a)`(const float & strength)` | Set emission strength.
`public `[`Font`](#classmos_1_1gfx_1_1Font)` `[`font`](#classmos_1_1gfx_1_1Text_1a4d5f5264f8a7b41b09218820c9248713)`() const` | Get the font.
`public `[`Text`](#classmos_1_1gfx_1_1Text)` & `[`operator=`](#classmos_1_1gfx_1_1Text_1a3b9d2816ece66d0c4431b102453b3187)`(const std::string & text)` | 
`public `[`Text`](#classmos_1_1gfx_1_1Text)` & `[`operator+=`](#classmos_1_1gfx_1_1Text_1ab09fc6f334765ba42ee2f64e9394f868)`(const std::string & text)` | 
`typedef `[`CharMap`](#classmos_1_1gfx_1_1Text_1a4ea218b44f9b25c54f4ae3344b88a3f2) | 
`typedef `[`TexPtr`](#classmos_1_1gfx_1_1Text_1a122d1310518784e72c26cb728da5f810) | 

## Members

#### `public float `[`spacing`](#classmos_1_1gfx_1_1Text_1a463688f94dcd762b0836a2f4bf4ffe9c) 

#### `public  `[`Text`](#classmos_1_1gfx_1_1Text_1a9f435f10d019b136450124f8b61ff500)`(const std::string & text,const `[`Font`](#classmos_1_1gfx_1_1Font)` & font,const glm::mat4 & transform,const bool emissive,const float spacing)` 

#### `public virtual  `[`~Text`](#classmos_1_1gfx_1_1Text_1a8051864d9344603946450b80de883ff2)`()` 

#### `public void `[`text`](#classmos_1_1gfx_1_1Text_1a440d59aa96745e9824f8b904c19e6359)`(const std::string & text)` 

Set text.

#### `public std::string `[`text`](#classmos_1_1gfx_1_1Text_1a71e0d89c8e24b02acd8b2e1d758e4be2)`() const` 

Get text.

#### `public float `[`width`](#classmos_1_1gfx_1_1Text_1a2fb11ee46a1d4b930f57381faecd65c8)`() const` 

Approximate width.

#### `public float `[`height`](#classmos_1_1gfx_1_1Text_1a7bd81108012fe76d1391db42a475e5b4)`() const` 

Approximate height.

#### `public void `[`position`](#classmos_1_1gfx_1_1Text_1a4db76ba7ff9bbd6819619ca306f1156c)`(const glm::vec2 & position)` 

Set position.

#### `public void `[`position`](#classmos_1_1gfx_1_1Text_1a9982b4cfcfcc47d19a963518f4af0eb1)`(const glm::vec3 & position)` 

Set position.

#### `public glm::vec2 `[`position`](#classmos_1_1gfx_1_1Text_1a51527f82c80a3724cf0d323562e162c7)`() const` 

Get position.

#### `public void `[`scale`](#classmos_1_1gfx_1_1Text_1a315892d1ab3c0514ff7eb7833497562b)`(const float scale)` 

#### `public void `[`material`](#classmos_1_1gfx_1_1Text_1adb8d3a962001dc4b32c17857b242e1f6)`(const `[`Material`](#classmos_1_1gfx_1_1Material)` & material)` 

Set material.

#### `public void `[`transform`](#classmos_1_1gfx_1_1Text_1aaeb6a47cb47da85f0b0c2667aa5fb8fc)`(const glm::mat4 & transform)` 

Set transform.

#### `public glm::mat4 `[`transform`](#classmos_1_1gfx_1_1Text_1a5491211bb937914e0338bb0734d56115)`() const` 

Get transform.

#### `public `[`Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1Text_1af28a9439ce9df18f321ee33d843bc8e0)`() const` 

Get model.

#### `public void `[`emissive`](#classmos_1_1gfx_1_1Text_1a85057fa4ec6a975b600f2b2706fee641)`(const bool emissive)` 

Set if the text is emissive.

#### `public void `[`factor`](#classmos_1_1gfx_1_1Text_1a370e5445199b6c348be8b00eaef1ff2e)`(const glm::vec3 & factor)` 

Set the color multiplier for the text.

#### `public void `[`opacity`](#classmos_1_1gfx_1_1Text_1af085194277f54392eb4b0783ea6eb70e)`(const float & opacity)` 

Set opacity of text.

#### `public void `[`emission_strength`](#classmos_1_1gfx_1_1Text_1a71ce5b960ede5d0c7bb5746ba784ab6a)`(const float & strength)` 

Set emission strength.

#### `public `[`Font`](#classmos_1_1gfx_1_1Font)` `[`font`](#classmos_1_1gfx_1_1Text_1a4d5f5264f8a7b41b09218820c9248713)`() const` 

Get the font.

#### `public `[`Text`](#classmos_1_1gfx_1_1Text)` & `[`operator=`](#classmos_1_1gfx_1_1Text_1a3b9d2816ece66d0c4431b102453b3187)`(const std::string & text)` 

#### `public `[`Text`](#classmos_1_1gfx_1_1Text)` & `[`operator+=`](#classmos_1_1gfx_1_1Text_1ab09fc6f334765ba42ee2f64e9394f868)`(const std::string & text)` 

#### `typedef `[`CharMap`](#classmos_1_1gfx_1_1Text_1a4ea218b44f9b25c54f4ae3344b88a3f2) 

#### `typedef `[`TexPtr`](#classmos_1_1gfx_1_1Text_1a122d1310518784e72c26cb728da5f810) 

# class `mos::gfx::Texture` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public bool `[`mipmaps`](#classmos_1_1gfx_1_1Texture_1ac43d07da9c253a94bc0674dfff448a86) | 
`public Wrap `[`wrap`](#classmos_1_1gfx_1_1Texture_1ad9b11f90c922b6a6059a9b6ac70ae443) | 
`public Format `[`format`](#classmos_1_1gfx_1_1Texture_1a40204eb3a9753a0bbb5439177288a375) | 
`public `[`TrackedContainer`](#classmos_1_1TrackedContainer)`< Data > `[`layers`](#classmos_1_1gfx_1_1Texture_1aac539034637e12e7ee80fc8ac6005d1b) | 
`public template<>`  <br/>`inline  `[`Texture`](#classmos_1_1gfx_1_1Texture_1a3af4a7e3201817d58203a9e0de4ebd0d)`(T begin,T end,const int width,const int height,const Format & format,const Wrap & wrap,const bool mipmaps)` | 
`public  `[`Texture`](#classmos_1_1gfx_1_1Texture_1a4f301e411441713d18f30446ca40b7e2)`(const std::initializer_list< Data > & layers,const int width,const int height,const Format & format,const Wrap & wrap,const bool mipmaps)` | 
`public  `[`Texture`](#classmos_1_1gfx_1_1Texture_1acb943fd56dbbad50511f00d42c47019c)`(const int width,const int height,const Format & format,const Wrap & wrap,const bool mipmaps)` | 
`public  `[`Texture`](#classmos_1_1gfx_1_1Texture_1addce74957b5c118d7f6e542e36cbe250)`(const std::initializer_list< std::string > & paths,const bool color_data,const Wrap & wrap,const bool mipmaps)` | 
`public int `[`id`](#classmos_1_1gfx_1_1Texture_1a61633c2d5cfd26a93be62f7485f10047)`() const` | 
`public int `[`width`](#classmos_1_1gfx_1_1Texture_1ac38606999e941dc09ec51332d76b8531)`() const` | 
`public int `[`height`](#classmos_1_1gfx_1_1Texture_1a9c87d87e840bb2e26e63c13dc6147b8c)`() const` | 
`public int `[`depth`](#classmos_1_1gfx_1_1Texture_1a7f3167feb65346848fb6b36ffe273d5d)`() const` | 
`enum `[`Wrap`](#classmos_1_1gfx_1_1Texture_1aca6cb3b7c27c061951866707b31dd496) | 
`enum `[`Format`](#classmos_1_1gfx_1_1Texture_1ad4fee3cc1b044694dff6b8085c663b44) | 
`typedef `[`Data`](#classmos_1_1gfx_1_1Texture_1a984d73d01f899b3f4258903694721b5e) | 

## Members

#### `public bool `[`mipmaps`](#classmos_1_1gfx_1_1Texture_1ac43d07da9c253a94bc0674dfff448a86) 

#### `public Wrap `[`wrap`](#classmos_1_1gfx_1_1Texture_1ad9b11f90c922b6a6059a9b6ac70ae443) 

#### `public Format `[`format`](#classmos_1_1gfx_1_1Texture_1a40204eb3a9753a0bbb5439177288a375) 

#### `public `[`TrackedContainer`](#classmos_1_1TrackedContainer)`< Data > `[`layers`](#classmos_1_1gfx_1_1Texture_1aac539034637e12e7ee80fc8ac6005d1b) 

#### `public template<>`  <br/>`inline  `[`Texture`](#classmos_1_1gfx_1_1Texture_1a3af4a7e3201817d58203a9e0de4ebd0d)`(T begin,T end,const int width,const int height,const Format & format,const Wrap & wrap,const bool mipmaps)` 

#### `public  `[`Texture`](#classmos_1_1gfx_1_1Texture_1a4f301e411441713d18f30446ca40b7e2)`(const std::initializer_list< Data > & layers,const int width,const int height,const Format & format,const Wrap & wrap,const bool mipmaps)` 

#### `public  `[`Texture`](#classmos_1_1gfx_1_1Texture_1acb943fd56dbbad50511f00d42c47019c)`(const int width,const int height,const Format & format,const Wrap & wrap,const bool mipmaps)` 

#### `public  `[`Texture`](#classmos_1_1gfx_1_1Texture_1addce74957b5c118d7f6e542e36cbe250)`(const std::initializer_list< std::string > & paths,const bool color_data,const Wrap & wrap,const bool mipmaps)` 

#### `public int `[`id`](#classmos_1_1gfx_1_1Texture_1a61633c2d5cfd26a93be62f7485f10047)`() const` 

#### `public int `[`width`](#classmos_1_1gfx_1_1Texture_1ac38606999e941dc09ec51332d76b8531)`() const` 

#### `public int `[`height`](#classmos_1_1gfx_1_1Texture_1a9c87d87e840bb2e26e63c13dc6147b8c)`() const` 

#### `public int `[`depth`](#classmos_1_1gfx_1_1Texture_1a7f3167feb65346848fb6b36ffe273d5d)`() const` 

#### `enum `[`Wrap`](#classmos_1_1gfx_1_1Texture_1aca6cb3b7c27c061951866707b31dd496) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
REPEAT            | 
CLAMP            | 

#### `enum `[`Format`](#classmos_1_1gfx_1_1Texture_1ad4fee3cc1b044694dff6b8085c663b44) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
R            | 
RG            | 
RGB            | 
RGBA            | 
SRGB            | 
SRGBA            | 

#### `typedef `[`Data`](#classmos_1_1gfx_1_1Texture_1a984d73d01f899b3f4258903694721b5e) 

# class `mos::gfx::Texture2D` 

```
class mos::gfx::Texture2D
  : public mos::gfx::Texture
```  

[Texture](#classmos_1_1gfx_1_1Texture) in two dimension.

Contains iterable chars as data.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public template<>`  <br/>`inline  `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D_1acc1033eac4adc5e34ec38cd110b98c57)`(T begin,T end,unsigned int width,unsigned int height,const Format & format,const Wrap & wrap,const bool mipmaps)` | 
`public  `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D_1a36c0e00ebd483110653fca71de60cfbc)`(const unsigned int width,const unsigned int height,const Format & format,const Wrap & wrap,const bool mipmaps)` | 
`public virtual  `[`~Texture2D`](#classmos_1_1gfx_1_1Texture2D_1ab381e5a84efe756dae80278f6ff0baa6)`()` | 
`public  `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D_1a638099ac753ef620a340d0867754ecae)`(const std::string & path,const bool color_data,const bool mipmaps,const Texture::Wrap & wrap)` | Create from file.

## Members

#### `public template<>`  <br/>`inline  `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D_1acc1033eac4adc5e34ec38cd110b98c57)`(T begin,T end,unsigned int width,unsigned int height,const Format & format,const Wrap & wrap,const bool mipmaps)` 

#### `public  `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D_1a36c0e00ebd483110653fca71de60cfbc)`(const unsigned int width,const unsigned int height,const Format & format,const Wrap & wrap,const bool mipmaps)` 

#### `public virtual  `[`~Texture2D`](#classmos_1_1gfx_1_1Texture2D_1ab381e5a84efe756dae80278f6ff0baa6)`()` 

#### `public  `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D_1a638099ac753ef620a340d0867754ecae)`(const std::string & path,const bool color_data,const bool mipmaps,const Texture::Wrap & wrap)` 

Create from file.

# class `mos::gfx::Vertex` 

The vertex structure, supported by the renderer.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Vertex_1a70dd073f9c5be03e1a5de8e6db22d7aa) | 
`public glm::vec3 `[`normal`](#classmos_1_1gfx_1_1Vertex_1ab3c429de37dc9f753c7db890ffe5d68e) | 
`public glm::vec3 `[`tangent`](#classmos_1_1gfx_1_1Vertex_1a89f546edf7b37fbb5605cc7a8e0625a7) | 
`public glm::vec2 `[`uv`](#classmos_1_1gfx_1_1Vertex_1a41afb03975cc762bbfdde6b0bee89253) | 
`public float `[`weight`](#classmos_1_1gfx_1_1Vertex_1a4831f66107bc983ebfc6ada41c31b1cb) | 
`public  explicit `[`Vertex`](#classmos_1_1gfx_1_1Vertex_1ae5784aeefb9a0916a401c0b3379babf0)`(const glm::vec3 & position,const glm::vec3 & normal,const glm::vec3 & tangent,const glm::vec2 & uv,const float weight)` | 
`public  `[`~Vertex`](#classmos_1_1gfx_1_1Vertex_1a79dbe37bcfe0a30393507f2a6c5e4869)`()` | 

## Members

#### `public glm::vec3 `[`position`](#classmos_1_1gfx_1_1Vertex_1a70dd073f9c5be03e1a5de8e6db22d7aa) 

#### `public glm::vec3 `[`normal`](#classmos_1_1gfx_1_1Vertex_1ab3c429de37dc9f753c7db890ffe5d68e) 

#### `public glm::vec3 `[`tangent`](#classmos_1_1gfx_1_1Vertex_1a89f546edf7b37fbb5605cc7a8e0625a7) 

#### `public glm::vec2 `[`uv`](#classmos_1_1gfx_1_1Vertex_1a41afb03975cc762bbfdde6b0bee89253) 

#### `public float `[`weight`](#classmos_1_1gfx_1_1Vertex_1a4831f66107bc983ebfc6ada41c31b1cb) 

#### `public  explicit `[`Vertex`](#classmos_1_1gfx_1_1Vertex_1ae5784aeefb9a0916a401c0b3379babf0)`(const glm::vec3 & position,const glm::vec3 & normal,const glm::vec3 & tangent,const glm::vec2 & uv,const float weight)` 

#### `public  `[`~Vertex`](#classmos_1_1gfx_1_1Vertex_1a79dbe37bcfe0a30393507f2a6c5e4869)`()` 

# struct `mos::gfx::Character` 

Measurements of a character glyph, for text rendering.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`x_offset`](#structmos_1_1gfx_1_1Character_1a59fcef4cd19140b8a101d87fe73813d8) | 
`public float `[`y_offset`](#structmos_1_1gfx_1_1Character_1ae3b1652530bac5b71ed70d53330b0fdc) | 
`public float `[`x_advance`](#structmos_1_1gfx_1_1Character_1a4708d9bd76bea70d4c2b2f66dc68ad5a) | 
`public float `[`width`](#structmos_1_1gfx_1_1Character_1a55bbb11c75174782c4a240346b187000) | 
`public float `[`x`](#structmos_1_1gfx_1_1Character_1ae488cd2dc47c7b8d518e2f1e67575fa5) | 
`public float `[`y`](#structmos_1_1gfx_1_1Character_1affcb7fd1957bc9182809316491c082c7) | 
`public float `[`height`](#structmos_1_1gfx_1_1Character_1a3bc558239b6c9792ed63166ae06c068a) | 
`public char `[`id`](#structmos_1_1gfx_1_1Character_1a740b2274b606e9a955e4c0c071f5a774) | 

## Members

#### `public float `[`x_offset`](#structmos_1_1gfx_1_1Character_1a59fcef4cd19140b8a101d87fe73813d8) 

#### `public float `[`y_offset`](#structmos_1_1gfx_1_1Character_1ae3b1652530bac5b71ed70d53330b0fdc) 

#### `public float `[`x_advance`](#structmos_1_1gfx_1_1Character_1a4708d9bd76bea70d4c2b2f66dc68ad5a) 

#### `public float `[`width`](#structmos_1_1gfx_1_1Character_1a55bbb11c75174782c4a240346b187000) 

#### `public float `[`x`](#structmos_1_1gfx_1_1Character_1ae488cd2dc47c7b8d518e2f1e67575fa5) 

#### `public float `[`y`](#structmos_1_1gfx_1_1Character_1affcb7fd1957bc9182809316491c082c7) 

#### `public float `[`height`](#structmos_1_1gfx_1_1Character_1a3bc558239b6c9792ed63166ae06c068a) 

#### `public char `[`id`](#structmos_1_1gfx_1_1Character_1a740b2274b606e9a955e4c0c071f5a774) 

# struct `mos::gfx::Face` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` & `[`v0`](#structmos_1_1gfx_1_1Face_1a7a5fb20d5d74549d3c3e81a8ec191227) | 
`public `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` & `[`v1`](#structmos_1_1gfx_1_1Face_1aee6f697ae75d14140de664fc375ad817) | 
`public `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` & `[`v2`](#structmos_1_1gfx_1_1Face_1a708a11d453388cf5066a26ee676d3daf) | 
`public inline glm::vec3 `[`normal`](#structmos_1_1gfx_1_1Face_1a88fd62bf279ac2ea5dd59c12d97c9969)`() const` | 

## Members

#### `public `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` & `[`v0`](#structmos_1_1gfx_1_1Face_1a7a5fb20d5d74549d3c3e81a8ec191227) 

#### `public `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` & `[`v1`](#structmos_1_1gfx_1_1Face_1aee6f697ae75d14140de664fc375ad817) 

#### `public `[`Vertex`](#classmos_1_1gfx_1_1Vertex)` & `[`v2`](#structmos_1_1gfx_1_1Face_1a708a11d453388cf5066a26ee676d3daf) 

#### `public inline glm::vec3 `[`normal`](#structmos_1_1gfx_1_1Face_1a88fd62bf279ac2ea5dd59c12d97c9969)`() const` 

# struct `mos::gfx::FormatPair` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`internal_format`](#structmos_1_1gfx_1_1FormatPair_1a2cce8fa69ec9707de4de852b0d376d39) | 
`public GLuint `[`format`](#structmos_1_1gfx_1_1FormatPair_1a97740365ba14f725482e39ff945b1d30) | 

## Members

#### `public GLuint `[`internal_format`](#structmos_1_1gfx_1_1FormatPair_1a2cce8fa69ec9707de4de852b0d376d39) 

#### `public GLuint `[`format`](#structmos_1_1gfx_1_1FormatPair_1a97740365ba14f725482e39ff945b1d30) 

# struct `mos::gfx::TextureTarget` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`mos::gfx::Camera`](#classmos_1_1gfx_1_1Camera)` `[`camera`](#structmos_1_1gfx_1_1TextureTarget_1aa36ad2f1343269986b48ab0f3527934b) | 
`public mos::gfx::SharedTexture2D `[`texture`](#structmos_1_1gfx_1_1TextureTarget_1addf4099ba7d832d95dcbfd57cc3b7a33) | 
`public `[`mos::gfx::Target`](#classmos_1_1gfx_1_1Target)` `[`target`](#structmos_1_1gfx_1_1TextureTarget_1a9a1bfad273967fc5ef74b02daf405471) | 
`public inline  `[`TextureTarget`](#structmos_1_1gfx_1_1TextureTarget_1a9269132175aec5a08dd6e530910a83f5)`()` | 

## Members

#### `public `[`mos::gfx::Camera`](#classmos_1_1gfx_1_1Camera)` `[`camera`](#structmos_1_1gfx_1_1TextureTarget_1aa36ad2f1343269986b48ab0f3527934b) 

#### `public mos::gfx::SharedTexture2D `[`texture`](#structmos_1_1gfx_1_1TextureTarget_1addf4099ba7d832d95dcbfd57cc3b7a33) 

#### `public `[`mos::gfx::Target`](#classmos_1_1gfx_1_1Target)` `[`target`](#structmos_1_1gfx_1_1TextureTarget_1a9a1bfad273967fc5ef74b02daf405471) 

#### `public inline  `[`TextureTarget`](#structmos_1_1gfx_1_1TextureTarget_1a9269132175aec5a08dd6e530910a83f5)`()` 

# namespace `mos::gfx::exp` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`mos::gfx::exp::Button`](#classmos_1_1gfx_1_1exp_1_1Button) | 
`class `[`mos::gfx::exp::Menu`](#classmos_1_1gfx_1_1exp_1_1Menu) | 

# class `mos::gfx::exp::Button` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button_1a2d9951334574e1da028a4ebe7d978cd4)`(const `[`gfx::Text`](#classmos_1_1gfx_1_1Text)` & text,const State & state)` | 
`public  `[`~Button`](#classmos_1_1gfx_1_1exp_1_1Button_1a0e4b929da887c0f41e79b9ba26179439)`()` | 
`public `[`gfx::Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1exp_1_1Button_1af6364c6dac8ae1142cc0789c92669b7b)`()` | 
`public bool `[`selected`](#classmos_1_1gfx_1_1exp_1_1Button_1a9b608ce76224c6c99bfe618a5dde9a4c)`()` | 
`public void `[`state`](#classmos_1_1gfx_1_1exp_1_1Button_1a5a2f711baf2799fb2b085b02f3b36d08)`(const State & state)` | 
`public float `[`height`](#classmos_1_1gfx_1_1exp_1_1Button_1a413ef84ae04b8d188d9336ee12d37eaa)`() const` | 
`public float `[`width`](#classmos_1_1gfx_1_1exp_1_1Button_1a7a348cdf708d8ec4b330ba7e6eea572c)`() const` | 
`public State `[`state`](#classmos_1_1gfx_1_1exp_1_1Button_1a3433bb1f89130c6843bf46996529fd98)`() const` | 
`public void `[`click_callback`](#classmos_1_1gfx_1_1exp_1_1Button_1a692744c2f644dc9b220d89593f9bccc3)`(const Callback & callback)` | 
`public void `[`click`](#classmos_1_1gfx_1_1exp_1_1Button_1a52677ebb981d5e61591e8ce6c5d53627)`()` | 
`enum `[`State`](#classmos_1_1gfx_1_1exp_1_1Button_1a57e94864e4a43d63ebc0fe309a0193fc) | 
`typedef `[`Callback`](#classmos_1_1gfx_1_1exp_1_1Button_1a3711e7d184632ca77364003650343fd9) | 

## Members

#### `public  `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button_1a2d9951334574e1da028a4ebe7d978cd4)`(const `[`gfx::Text`](#classmos_1_1gfx_1_1Text)` & text,const State & state)` 

#### `public  `[`~Button`](#classmos_1_1gfx_1_1exp_1_1Button_1a0e4b929da887c0f41e79b9ba26179439)`()` 

#### `public `[`gfx::Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1exp_1_1Button_1af6364c6dac8ae1142cc0789c92669b7b)`()` 

#### `public bool `[`selected`](#classmos_1_1gfx_1_1exp_1_1Button_1a9b608ce76224c6c99bfe618a5dde9a4c)`()` 

#### `public void `[`state`](#classmos_1_1gfx_1_1exp_1_1Button_1a5a2f711baf2799fb2b085b02f3b36d08)`(const State & state)` 

#### `public float `[`height`](#classmos_1_1gfx_1_1exp_1_1Button_1a413ef84ae04b8d188d9336ee12d37eaa)`() const` 

#### `public float `[`width`](#classmos_1_1gfx_1_1exp_1_1Button_1a7a348cdf708d8ec4b330ba7e6eea572c)`() const` 

#### `public State `[`state`](#classmos_1_1gfx_1_1exp_1_1Button_1a3433bb1f89130c6843bf46996529fd98)`() const` 

#### `public void `[`click_callback`](#classmos_1_1gfx_1_1exp_1_1Button_1a692744c2f644dc9b220d89593f9bccc3)`(const Callback & callback)` 

#### `public void `[`click`](#classmos_1_1gfx_1_1exp_1_1Button_1a52677ebb981d5e61591e8ce6c5d53627)`()` 

#### `enum `[`State`](#classmos_1_1gfx_1_1exp_1_1Button_1a57e94864e4a43d63ebc0fe309a0193fc) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
IDLE            | 
SELECTED            | 
CLICKED            | 

#### `typedef `[`Callback`](#classmos_1_1gfx_1_1exp_1_1Button_1a3711e7d184632ca77364003650343fd9) 

# class `mos::gfx::exp::Menu` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Menu`](#classmos_1_1gfx_1_1exp_1_1Menu_1ab6294912faf495f1d3331b745bef5250)`()` | 
`public  `[`Menu`](#classmos_1_1gfx_1_1exp_1_1Menu_1aad4295f6d7f72feaa12d2e83cc37f036)`(const std::initializer_list< `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button)` > & buttons)` | 
`public void `[`add`](#classmos_1_1gfx_1_1exp_1_1Menu_1a37fffd092d80d503d6c4c31e3c37796b)`(const `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button)` & button)` | 
`public `[`mos::gfx::Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1exp_1_1Menu_1a6b391a7fa4c95ba4a69cdef1b0052b45)`()` | 
`public `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button)` & `[`selected`](#classmos_1_1gfx_1_1exp_1_1Menu_1a5e76501fff27dc2934701dcafab2b5b0)`()` | 
`public void `[`select_next`](#classmos_1_1gfx_1_1exp_1_1Menu_1a0a98bb644f8510a0be6927fa7eb0c47d)`()` | 
`public void `[`select_previos`](#classmos_1_1gfx_1_1exp_1_1Menu_1a67b223fbfc4e490cf29d0f9eaa4f2b03)`()` | 
`public  `[`~Menu`](#classmos_1_1gfx_1_1exp_1_1Menu_1ac4c14a10a1df26190e7872c1e284aea0)`()` | 
`typedef `[`Buttons`](#classmos_1_1gfx_1_1exp_1_1Menu_1a6593c5e65e959064a76c82c3b962291e) | 

## Members

#### `public  `[`Menu`](#classmos_1_1gfx_1_1exp_1_1Menu_1ab6294912faf495f1d3331b745bef5250)`()` 

#### `public  `[`Menu`](#classmos_1_1gfx_1_1exp_1_1Menu_1aad4295f6d7f72feaa12d2e83cc37f036)`(const std::initializer_list< `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button)` > & buttons)` 

#### `public void `[`add`](#classmos_1_1gfx_1_1exp_1_1Menu_1a37fffd092d80d503d6c4c31e3c37796b)`(const `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button)` & button)` 

#### `public `[`mos::gfx::Model`](#classmos_1_1gfx_1_1Model)` `[`model`](#classmos_1_1gfx_1_1exp_1_1Menu_1a6b391a7fa4c95ba4a69cdef1b0052b45)`()` 

#### `public `[`Button`](#classmos_1_1gfx_1_1exp_1_1Button)` & `[`selected`](#classmos_1_1gfx_1_1exp_1_1Menu_1a5e76501fff27dc2934701dcafab2b5b0)`()` 

#### `public void `[`select_next`](#classmos_1_1gfx_1_1exp_1_1Menu_1a0a98bb644f8510a0be6927fa7eb0c47d)`()` 

#### `public void `[`select_previos`](#classmos_1_1gfx_1_1exp_1_1Menu_1a67b223fbfc4e490cf29d0f9eaa4f2b03)`()` 

#### `public  `[`~Menu`](#classmos_1_1gfx_1_1exp_1_1Menu_1ac4c14a10a1df26190e7872c1e284aea0)`()` 

#### `typedef `[`Buttons`](#classmos_1_1gfx_1_1exp_1_1Menu_1a6593c5e65e959064a76c82c3b962291e) 

# namespace `mos::io` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`mos::io::Window`](#classmos_1_1io_1_1Window) | 

# class `mos::io::Window` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Window`](#classmos_1_1io_1_1Window_1aa8acca28fa9aae07c877280d597c088a)`(const std::string & title,const glm::ivec2 & resolution,const int swap_interval)` | 
`public  `[`~Window`](#classmos_1_1io_1_1Window_1ad0bafcb980d685ea25b6f8309caf17e5)`()` | 
`public glm::ivec2 `[`framebuffer_size`](#classmos_1_1io_1_1Window_1a8c2cf3c33e675525ad2e343e989f414c)`() const` | 
`public void `[`poll_events`](#classmos_1_1io_1_1Window_1a15b2538c9394bcb339ccd2c8ae9d49c3)`()` | 
`public void `[`swap_buffers`](#classmos_1_1io_1_1Window_1abfc576872b3224e65de58eba895ade89)`()` | 
`public bool `[`close`](#classmos_1_1io_1_1Window_1a68ca134df3fb11831f2f1e001b9586db)`() const` | 
`public void `[`close`](#classmos_1_1io_1_1Window_1aa8636f9faeb9ba67fd3d3f57a18212bc)`(const bool)` | 
`public void `[`cursor_mode`](#classmos_1_1io_1_1Window_1a835e9e203466bf307b1b099e51a09c66)`(const CursorMode & mode)` | 
`public void `[`cursor`](#classmos_1_1io_1_1Window_1a518d1ef9dac195c66ad0564d922c3ddd)`(const Cursor & cursor)` | 
`public glm::dvec2 `[`cursor_position`](#classmos_1_1io_1_1Window_1a36cc3c1d5704170647f2359ada026fdf)`() const` | 
`public float `[`dpi`](#classmos_1_1io_1_1Window_1adfcb8e290ab8e4d7d9f396a019778ebe)`() const` | 
`enum `[`CursorMode`](#classmos_1_1io_1_1Window_1ad93314b08d3c4185d6fb5dd49226ff7a) | 
`enum `[`Cursor`](#classmos_1_1io_1_1Window_1aeb49e407e4ff5156f2cd1f5937472075) | 
`typedef `[`ErrorFunc`](#classmos_1_1io_1_1Window_1a49e2f13f26a04231d94f597ed5ad3456) | 
`typedef `[`PosFunc`](#classmos_1_1io_1_1Window_1af5e814873efc870f6322d76a5ec24b59) | 
`typedef `[`SizeFunc`](#classmos_1_1io_1_1Window_1af547140a800cc29621761e3ae9f38753) | 
`typedef `[`ClickFunc`](#classmos_1_1io_1_1Window_1a4459ea450b2f277d2ffb6350c97480c9) | 
`typedef `[`MouseFunc`](#classmos_1_1io_1_1Window_1a1b68363243e52e2f56233ac1869042ff) | 
`typedef `[`ScrollFunc`](#classmos_1_1io_1_1Window_1ae809b5e5730698ff9a2785a8e44be90f) | 
`typedef `[`KeyFunc`](#classmos_1_1io_1_1Window_1a7cdcfcd576d5f36504e82d8dade0fa03) | 

## Members

#### `public  `[`Window`](#classmos_1_1io_1_1Window_1aa8acca28fa9aae07c877280d597c088a)`(const std::string & title,const glm::ivec2 & resolution,const int swap_interval)` 

#### `public  `[`~Window`](#classmos_1_1io_1_1Window_1ad0bafcb980d685ea25b6f8309caf17e5)`()` 

#### `public glm::ivec2 `[`framebuffer_size`](#classmos_1_1io_1_1Window_1a8c2cf3c33e675525ad2e343e989f414c)`() const` 

#### `public void `[`poll_events`](#classmos_1_1io_1_1Window_1a15b2538c9394bcb339ccd2c8ae9d49c3)`()` 

#### `public void `[`swap_buffers`](#classmos_1_1io_1_1Window_1abfc576872b3224e65de58eba895ade89)`()` 

#### `public bool `[`close`](#classmos_1_1io_1_1Window_1a68ca134df3fb11831f2f1e001b9586db)`() const` 

#### `public void `[`close`](#classmos_1_1io_1_1Window_1aa8636f9faeb9ba67fd3d3f57a18212bc)`(const bool)` 

#### `public void `[`cursor_mode`](#classmos_1_1io_1_1Window_1a835e9e203466bf307b1b099e51a09c66)`(const CursorMode & mode)` 

#### `public void `[`cursor`](#classmos_1_1io_1_1Window_1a518d1ef9dac195c66ad0564d922c3ddd)`(const Cursor & cursor)` 

#### `public glm::dvec2 `[`cursor_position`](#classmos_1_1io_1_1Window_1a36cc3c1d5704170647f2359ada026fdf)`() const` 

#### `public float `[`dpi`](#classmos_1_1io_1_1Window_1adfcb8e290ab8e4d7d9f396a019778ebe)`() const` 

#### `enum `[`CursorMode`](#classmos_1_1io_1_1Window_1ad93314b08d3c4185d6fb5dd49226ff7a) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
NORMAL            | 
HIDDDEN            | 
DISABLED            | 

#### `enum `[`Cursor`](#classmos_1_1io_1_1Window_1aeb49e407e4ff5156f2cd1f5937472075) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
HAND            | 
ARROW            | 
CROSSHAIR            | 

#### `typedef `[`ErrorFunc`](#classmos_1_1io_1_1Window_1a49e2f13f26a04231d94f597ed5ad3456) 

#### `typedef `[`PosFunc`](#classmos_1_1io_1_1Window_1af5e814873efc870f6322d76a5ec24b59) 

#### `typedef `[`SizeFunc`](#classmos_1_1io_1_1Window_1af547140a800cc29621761e3ae9f38753) 

#### `typedef `[`ClickFunc`](#classmos_1_1io_1_1Window_1a4459ea450b2f277d2ffb6350c97480c9) 

#### `typedef `[`MouseFunc`](#classmos_1_1io_1_1Window_1a1b68363243e52e2f56233ac1869042ff) 

#### `typedef `[`ScrollFunc`](#classmos_1_1io_1_1Window_1ae809b5e5730698ff9a2785a8e44be90f) 

#### `typedef `[`KeyFunc`](#classmos_1_1io_1_1Window_1a7cdcfcd576d5f36504e82d8dade0fa03) 

# namespace `mos::sim` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public std::ostream & `[`operator<<`](#sim_2box_8cpp_1a829c02a649e5ed16bc917cb8351cd00d)`(std::ostream & os,const `[`Box`](#classmos_1_1sim_1_1Box)` & box)`            | 
`class `[`mos::sim::Box`](#classmos_1_1sim_1_1Box) | Axis aligned bounding box.
`class `[`mos::sim::Face`](#classmos_1_1sim_1_1Face) | 
`class `[`mos::sim::Face2`](#classmos_1_1sim_1_1Face2) | 
`class `[`mos::sim::Intersection`](#classmos_1_1sim_1_1Intersection) | 
`class `[`mos::sim::Navmesh`](#classmos_1_1sim_1_1Navmesh) | 
`class `[`mos::sim::Navmesh2`](#classmos_1_1sim_1_1Navmesh2) | 
`class `[`mos::sim::Pid`](#classmos_1_1sim_1_1Pid) | 
`class `[`mos::sim::Ray`](#classmos_1_1sim_1_1Ray) | 

## Members

#### `public std::ostream & `[`operator<<`](#sim_2box_8cpp_1a829c02a649e5ed16bc917cb8351cd00d)`(std::ostream & os,const `[`Box`](#classmos_1_1sim_1_1Box)` & box)` 

# class `mos::sim::Box` 

Axis aligned bounding box.

Used for colission detection and sound obstruction.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`extent`](#classmos_1_1sim_1_1Box_1a1376b1c0963429659f2539f5b53d244f) | 
`public glm::vec3 `[`position`](#classmos_1_1sim_1_1Box_1aa91d054a66e7da8e0109fabfe128aa29) | 
`public template<>`  <br/>`inline  `[`Box`](#classmos_1_1sim_1_1Box_1a02bb1e53f388118d3f8fae6c9e37b55c)`(const T & positions,const glm::mat4 & transform)` | 
`public template<>`  <br/>`inline  `[`Box`](#classmos_1_1sim_1_1Box_1ad395e76ecdfa388701914fdaa24d8b82)`(VertexIt begin,VertexIt end,const glm::mat4 & transform)` | Create a box from vertices and a transform.
`public  `[`Box`](#classmos_1_1sim_1_1Box_1ab1ee7dea6d49b28c82d94ee23b9c18a1)`(const glm::vec3 & extent,const glm::vec3 & position)` | 
`public  `[`Box`](#classmos_1_1sim_1_1Box_1a4c98e274a3b1f3c13a79b9c75887a71a)`()` | 
`public glm::vec3 `[`min`](#classmos_1_1sim_1_1Box_1ab36567fac68b3333e456afc53cb3947f)`() const` | 
`public glm::vec3 `[`max`](#classmos_1_1sim_1_1Box_1a1e06bd1cd12e376b514c817ad70f009b)`() const` | 
`public bool `[`intersects`](#classmos_1_1sim_1_1Box_1ac496129b5136ef11a66d9ca6172ae885)`(const glm::vec3 & origin,const glm::vec3 & direction) const` | 
`public bool `[`intersects`](#classmos_1_1sim_1_1Box_1a27f84dbdc9ff57d6770950ab85b988b2)`(const `[`Ray`](#classmos_1_1sim_1_1Ray)` & ray) const` | 
`public inline bool `[`intersect2`](#classmos_1_1sim_1_1Box_1a2634c968581206f109dbc1ff01a29d4c)`(const `[`Box`](#classmos_1_1sim_1_1Box)` & other) const` | 
`public void `[`transform`](#classmos_1_1sim_1_1Box_1a8e273a6e4b2a4a2b4e174fb792222c77)`(const glm::mat4 & transform)` | 
`public float `[`volume`](#classmos_1_1sim_1_1Box_1a4271578a0130232697b3a365676b1bdb)`() const` | Get box volume.
`public glm::vec3 `[`size`](#classmos_1_1sim_1_1Box_1a705c9a942a8b41423c298f52d9970aea)`() const` | 
`public inline bool `[`operator==`](#classmos_1_1sim_1_1Box_1a75e34a8f89db4c547bbc5e7932ce8feb)`(const `[`Box`](#classmos_1_1sim_1_1Box)` & other) const` | 
`public inline bool `[`operator!=`](#classmos_1_1sim_1_1Box_1a20fdb50f4fd5d8743df009c70bf53959)`(const `[`Box`](#classmos_1_1sim_1_1Box)` & other) const` | 

## Members

#### `public glm::vec3 `[`extent`](#classmos_1_1sim_1_1Box_1a1376b1c0963429659f2539f5b53d244f) 

#### `public glm::vec3 `[`position`](#classmos_1_1sim_1_1Box_1aa91d054a66e7da8e0109fabfe128aa29) 

#### `public template<>`  <br/>`inline  `[`Box`](#classmos_1_1sim_1_1Box_1a02bb1e53f388118d3f8fae6c9e37b55c)`(const T & positions,const glm::mat4 & transform)` 

#### `public template<>`  <br/>`inline  `[`Box`](#classmos_1_1sim_1_1Box_1ad395e76ecdfa388701914fdaa24d8b82)`(VertexIt begin,VertexIt end,const glm::mat4 & transform)` 

Create a box from vertices and a transform.

#### `public  `[`Box`](#classmos_1_1sim_1_1Box_1ab1ee7dea6d49b28c82d94ee23b9c18a1)`(const glm::vec3 & extent,const glm::vec3 & position)` 

#### `public  `[`Box`](#classmos_1_1sim_1_1Box_1a4c98e274a3b1f3c13a79b9c75887a71a)`()` 

#### `public glm::vec3 `[`min`](#classmos_1_1sim_1_1Box_1ab36567fac68b3333e456afc53cb3947f)`() const` 

#### `public glm::vec3 `[`max`](#classmos_1_1sim_1_1Box_1a1e06bd1cd12e376b514c817ad70f009b)`() const` 

#### `public bool `[`intersects`](#classmos_1_1sim_1_1Box_1ac496129b5136ef11a66d9ca6172ae885)`(const glm::vec3 & origin,const glm::vec3 & direction) const` 

#### `public bool `[`intersects`](#classmos_1_1sim_1_1Box_1a27f84dbdc9ff57d6770950ab85b988b2)`(const `[`Ray`](#classmos_1_1sim_1_1Ray)` & ray) const` 

#### `public inline bool `[`intersect2`](#classmos_1_1sim_1_1Box_1a2634c968581206f109dbc1ff01a29d4c)`(const `[`Box`](#classmos_1_1sim_1_1Box)` & other) const` 

#### `public void `[`transform`](#classmos_1_1sim_1_1Box_1a8e273a6e4b2a4a2b4e174fb792222c77)`(const glm::mat4 & transform)` 

#### `public float `[`volume`](#classmos_1_1sim_1_1Box_1a4271578a0130232697b3a365676b1bdb)`() const` 

Get box volume.

#### `public glm::vec3 `[`size`](#classmos_1_1sim_1_1Box_1a705c9a942a8b41423c298f52d9970aea)`() const` 

#### `public inline bool `[`operator==`](#classmos_1_1sim_1_1Box_1a75e34a8f89db4c547bbc5e7932ce8feb)`(const `[`Box`](#classmos_1_1sim_1_1Box)` & other) const` 

#### `public inline bool `[`operator!=`](#classmos_1_1sim_1_1Box_1a20fdb50f4fd5d8743df009c70bf53959)`(const `[`Box`](#classmos_1_1sim_1_1Box)` & other) const` 

# class `mos::sim::Face` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Face`](#classmos_1_1sim_1_1Face_1a021ef46f088ee1aea3217e24ace003e1)`(const glm::vec3 & v0,const glm::vec3 & v1,const glm::vec3 & v2)` | 
`public std::optional< `[`Intersection`](#classmos_1_1sim_1_1Intersection)` > `[`intersects`](#classmos_1_1sim_1_1Face_1a2345b5eed74f8f023b5e455712f4cdf4)`(const glm::vec3 & origin,const glm::vec3 & direction)` | 

## Members

#### `public  `[`Face`](#classmos_1_1sim_1_1Face_1a021ef46f088ee1aea3217e24ace003e1)`(const glm::vec3 & v0,const glm::vec3 & v1,const glm::vec3 & v2)` 

#### `public std::optional< `[`Intersection`](#classmos_1_1sim_1_1Intersection)` > `[`intersects`](#classmos_1_1sim_1_1Face_1a2345b5eed74f8f023b5e455712f4cdf4)`(const glm::vec3 & origin,const glm::vec3 & direction)` 

# class `mos::sim::Face2` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` `[`v0_`](#classmos_1_1sim_1_1Face2_1a64e8c84869f9b6bbfe73768d82279d65) | 
`public `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` `[`v1_`](#classmos_1_1sim_1_1Face2_1a112635b7eb7157ef9d9110ad00d4952a) | 
`public `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` `[`v2_`](#classmos_1_1sim_1_1Face2_1a86f81d560cfa166121856ca6e451e04e) | 
`public  `[`Face2`](#classmos_1_1sim_1_1Face2_1aa5c47795e41d44da1eee3c709c469350)`(`[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` & v0,`[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` & v1,`[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` & v2)` | 
`public std::optional< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`intersects`](#classmos_1_1sim_1_1Face2_1a51f16ec4f4c007cadad9422725d488a7)`(const glm::vec3 & origin,const glm::vec3 & direction)` | 

## Members

#### `public `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` `[`v0_`](#classmos_1_1sim_1_1Face2_1a64e8c84869f9b6bbfe73768d82279d65) 

#### `public `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` `[`v1_`](#classmos_1_1sim_1_1Face2_1a112635b7eb7157ef9d9110ad00d4952a) 

#### `public `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` `[`v2_`](#classmos_1_1sim_1_1Face2_1a86f81d560cfa166121856ca6e451e04e) 

#### `public  `[`Face2`](#classmos_1_1sim_1_1Face2_1aa5c47795e41d44da1eee3c709c469350)`(`[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` & v0,`[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` & v1,`[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` & v2)` 

#### `public std::optional< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`intersects`](#classmos_1_1sim_1_1Face2_1a51f16ec4f4c007cadad9422725d488a7)`(const glm::vec3 & origin,const glm::vec3 & direction)` 

# class `mos::sim::Intersection` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`position`](#classmos_1_1sim_1_1Intersection_1a604b2162f274ca657ff5729d8032b880) | 
`public glm::vec3 `[`normal`](#classmos_1_1sim_1_1Intersection_1a880693b50b3254a22f8b5b070039689d) | 
`public  `[`Intersection`](#classmos_1_1sim_1_1Intersection_1ab394cc4d041134ce191da625618b1bba)`(const glm::vec3 & position,const glm::vec3 & normal)` | 
`public  `[`~Intersection`](#classmos_1_1sim_1_1Intersection_1a0ef5abf8df76787b8f24cdd13fcd3681)`()` | 

## Members

#### `public glm::vec3 `[`position`](#classmos_1_1sim_1_1Intersection_1a604b2162f274ca657ff5729d8032b880) 

#### `public glm::vec3 `[`normal`](#classmos_1_1sim_1_1Intersection_1a880693b50b3254a22f8b5b070039689d) 

#### `public  `[`Intersection`](#classmos_1_1sim_1_1Intersection_1ab394cc4d041134ce191da625618b1bba)`(const glm::vec3 & position,const glm::vec3 & normal)` 

#### `public  `[`~Intersection`](#classmos_1_1sim_1_1Intersection_1a0ef5abf8df76787b8f24cdd13fcd3681)`()` 

# class `mos::sim::Navmesh` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Navmesh`](#classmos_1_1sim_1_1Navmesh_1a494b663b4db496739bda1a2c621114cf)`()` | 
`public  `[`Navmesh`](#classmos_1_1sim_1_1Navmesh_1a4266fb90c5be40832260a51e4c15c69a)`(const `[`gfx::Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh,const glm::mat4 & transform)` | 
`public template<>`  <br/>`inline  `[`Navmesh`](#classmos_1_1sim_1_1Navmesh_1aa6e18c2d2509a22d1b9351069ad928ce)`(Tv vertices_begin,Tv vertices_end,Te elements_begin,Te elements_end,const glm::mat4 & transform)` | 
`public std::optional< `[`Intersection`](#classmos_1_1sim_1_1Intersection)` > `[`intersects`](#classmos_1_1sim_1_1Navmesh_1a7e8e48c72d0759d6fdcf4b4378d3bff5)`(const glm::vec3 & origin,const glm::vec3 & direction)` | 
`public std::optional< `[`Intersection`](#classmos_1_1sim_1_1Intersection)` > `[`closest_intersection`](#classmos_1_1sim_1_1Navmesh_1aa37afaf9b441d84c84fbca33d788626f)`(const glm::vec3 & origin,const glm::vec3 direction)` | 
`public  `[`~Navmesh`](#classmos_1_1sim_1_1Navmesh_1a84aa04b8b8aa375a4c89ca1bf26db5f4)`()` | 
`typedef `[`OptionalIntersection`](#classmos_1_1sim_1_1Navmesh_1a2349c0b83bf9dda8db43f14d830a5441) | 

## Members

#### `public  `[`Navmesh`](#classmos_1_1sim_1_1Navmesh_1a494b663b4db496739bda1a2c621114cf)`()` 

#### `public  `[`Navmesh`](#classmos_1_1sim_1_1Navmesh_1a4266fb90c5be40832260a51e4c15c69a)`(const `[`gfx::Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh,const glm::mat4 & transform)` 

#### `public template<>`  <br/>`inline  `[`Navmesh`](#classmos_1_1sim_1_1Navmesh_1aa6e18c2d2509a22d1b9351069ad928ce)`(Tv vertices_begin,Tv vertices_end,Te elements_begin,Te elements_end,const glm::mat4 & transform)` 

#### `public std::optional< `[`Intersection`](#classmos_1_1sim_1_1Intersection)` > `[`intersects`](#classmos_1_1sim_1_1Navmesh_1a7e8e48c72d0759d6fdcf4b4378d3bff5)`(const glm::vec3 & origin,const glm::vec3 & direction)` 

#### `public std::optional< `[`Intersection`](#classmos_1_1sim_1_1Intersection)` > `[`closest_intersection`](#classmos_1_1sim_1_1Navmesh_1aa37afaf9b441d84c84fbca33d788626f)`(const glm::vec3 & origin,const glm::vec3 direction)` 

#### `public  `[`~Navmesh`](#classmos_1_1sim_1_1Navmesh_1a84aa04b8b8aa375a4c89ca1bf26db5f4)`()` 

#### `typedef `[`OptionalIntersection`](#classmos_1_1sim_1_1Navmesh_1a2349c0b83bf9dda8db43f14d830a5441) 

# class `mos::sim::Navmesh2` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public std::vector< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`vertices`](#classmos_1_1sim_1_1Navmesh2_1a062b0bcd5e1351d24333a4695acd1cd7) | 
`public std::vector< std::array< int, 3 > > `[`triangles`](#classmos_1_1sim_1_1Navmesh2_1a72d7c8265f490ff819fb8f0fbf7d0992) | 
`public  `[`Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1a7dbf25a77827213a410fa2a5ab890ff6)`()` | 
`public  `[`Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1a13b17b9521d634fe8d67dcb8a35aa88e)`(const `[`gfx::Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh,const glm::mat4 & transform)` | 
`public template<>`  <br/>`inline  `[`Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1aa9cb977c41dd5244bd11dc788dd6b272)`(Tv vertices_begin,Tv vertices_end,Te elements_begin,Te elements_end,const glm::mat4 & transform)` | 
`public std::optional< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`intersects`](#classmos_1_1sim_1_1Navmesh2_1aa09bfba917fce97ac8119b9c27ed1ee8)`(const glm::vec3 & origin,const glm::vec3 & direction)` | 
`public std::optional< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`closest_intersection`](#classmos_1_1sim_1_1Navmesh2_1a15365c24a9b974b07bd7c7339247d4ad)`(const glm::vec3 & origin,const glm::vec3 & direction)` | 
`public void `[`calculate_normals`](#classmos_1_1sim_1_1Navmesh2_1a0ad226fc85c540bf8ce7516e78f02cad)`()` | 
`public  `[`~Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1a71580f90ebac8dc60e302dd34edaab2f)`()` | 
`typedef `[`OptionalIntersection`](#classmos_1_1sim_1_1Navmesh2_1ad66118f902bd32a9911eb922a2e1f400) | 

## Members

#### `public std::vector< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`vertices`](#classmos_1_1sim_1_1Navmesh2_1a062b0bcd5e1351d24333a4695acd1cd7) 

#### `public std::vector< std::array< int, 3 > > `[`triangles`](#classmos_1_1sim_1_1Navmesh2_1a72d7c8265f490ff819fb8f0fbf7d0992) 

#### `public  `[`Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1a7dbf25a77827213a410fa2a5ab890ff6)`()` 

#### `public  `[`Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1a13b17b9521d634fe8d67dcb8a35aa88e)`(const `[`gfx::Mesh`](#classmos_1_1gfx_1_1Mesh)` & mesh,const glm::mat4 & transform)` 

#### `public template<>`  <br/>`inline  `[`Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1aa9cb977c41dd5244bd11dc788dd6b272)`(Tv vertices_begin,Tv vertices_end,Te elements_begin,Te elements_end,const glm::mat4 & transform)` 

#### `public std::optional< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`intersects`](#classmos_1_1sim_1_1Navmesh2_1aa09bfba917fce97ac8119b9c27ed1ee8)`(const glm::vec3 & origin,const glm::vec3 & direction)` 

#### `public std::optional< `[`gfx::Vertex`](#classmos_1_1gfx_1_1Vertex)` > `[`closest_intersection`](#classmos_1_1sim_1_1Navmesh2_1a15365c24a9b974b07bd7c7339247d4ad)`(const glm::vec3 & origin,const glm::vec3 & direction)` 

#### `public void `[`calculate_normals`](#classmos_1_1sim_1_1Navmesh2_1a0ad226fc85c540bf8ce7516e78f02cad)`()` 

#### `public  `[`~Navmesh2`](#classmos_1_1sim_1_1Navmesh2_1a71580f90ebac8dc60e302dd34edaab2f)`()` 

#### `typedef `[`OptionalIntersection`](#classmos_1_1sim_1_1Navmesh2_1ad66118f902bd32a9911eb922a2e1f400) 

# class `mos::sim::Pid` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`Kp`](#classmos_1_1sim_1_1Pid_1a7ad268bb58087ecc1b91b24d1fd7071a) | 
`public float `[`Ki`](#classmos_1_1sim_1_1Pid_1a68dc4cb2b94a66e0dbd460daadf7cbc4) | 
`public float `[`Kd`](#classmos_1_1sim_1_1Pid_1a8b91f1c876fe8d9c3bc3e6d9fe19bb5c) | 
`public inline  `[`Pid`](#classmos_1_1sim_1_1Pid_1ac780d9c66b06db19e50e5a7fb259bc6a)`(const T & error,const float Kp,const float Ki,const float Kd)` | 
`public inline T `[`get`](#classmos_1_1sim_1_1Pid_1a2cd9507eba6f4ff138a8f37be1fd2ae8)`(const T error,float dt)` | 

## Members

#### `public float `[`Kp`](#classmos_1_1sim_1_1Pid_1a7ad268bb58087ecc1b91b24d1fd7071a) 

#### `public float `[`Ki`](#classmos_1_1sim_1_1Pid_1a68dc4cb2b94a66e0dbd460daadf7cbc4) 

#### `public float `[`Kd`](#classmos_1_1sim_1_1Pid_1a8b91f1c876fe8d9c3bc3e6d9fe19bb5c) 

#### `public inline  `[`Pid`](#classmos_1_1sim_1_1Pid_1ac780d9c66b06db19e50e5a7fb259bc6a)`(const T & error,const float Kp,const float Ki,const float Kd)` 

#### `public inline T `[`get`](#classmos_1_1sim_1_1Pid_1a2cd9507eba6f4ff138a8f37be1fd2ae8)`(const T error,float dt)` 

# class `mos::sim::Ray` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public glm::vec3 `[`origin`](#classmos_1_1sim_1_1Ray_1a2b1135a2ebc9953d54fcfac51707fcea) | 
`public  `[`Ray`](#classmos_1_1sim_1_1Ray_1ac29492730b63dea4554672becc582ae4)`(const glm::vec3 & origin,const glm::vec3 & direction)` | 
`public glm::vec3 `[`direction`](#classmos_1_1sim_1_1Ray_1aa1dcb9bcb900365c3240c7eb79559c77)`() const` | 
`public void `[`direction`](#classmos_1_1sim_1_1Ray_1ae89770ebb5e156274f3272f3179888e8)`(const glm::vec3 & direction)` | 

## Members

#### `public glm::vec3 `[`origin`](#classmos_1_1sim_1_1Ray_1a2b1135a2ebc9953d54fcfac51707fcea) 

#### `public  `[`Ray`](#classmos_1_1sim_1_1Ray_1ac29492730b63dea4554672becc582ae4)`(const glm::vec3 & origin,const glm::vec3 & direction)` 

#### `public glm::vec3 `[`direction`](#classmos_1_1sim_1_1Ray_1aa1dcb9bcb900365c3240c7eb79559c77)`() const` 

#### `public void `[`direction`](#classmos_1_1sim_1_1Ray_1ae89770ebb5e156274f3272f3179888e8)`(const glm::vec3 & direction)` 

# class `mos::gfx::Renderer::EnvironmentProgram` 

```
class mos::gfx::Renderer::EnvironmentProgram
  : public mos::gfx::Renderer::Program
```  

Uniforms for the environment shader.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`model_view_projection_matrix`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a19dbce42cdd2d21c4bb1abbc4243f31c) | 
`public GLint `[`model_matrix`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a7a9bc65452b8df92f97283df3def4bff) | 
`public GLint `[`normal_matrix`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1aca85aa9b8f315830185000f258192db2) | 
`public std::array< GLint, 2 > `[`depth_bias_mvps`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a899bd3892676d54fb347ae54ed237e9d) | 
`public std::array< `[`EnvironmentUniforms`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms)`, 2 > `[`environment_maps`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1ab71db290aed7bfc64672c45ae075caad) | 
`public GLint `[`material_albedo_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a78d8aef072aac635445bf5d93cc0e976) | 
`public GLint `[`material_emission_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a7e6c9fe8215c4bad53df83d7ed3bee09) | 
`public GLint `[`material_normal_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1ad5bf072682c2d52a9bc1e1dae4e62e56) | 
`public GLint `[`material_metallic_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a6cadd1b386664e396ce3e9ab54b2848e) | 
`public GLint `[`material_roughness_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a0880e6a7cf3c1099c135c8cc5c4bd097) | 
`public GLint `[`material_ambient_occlusion_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a0c6a8bfd40c36807f875014128062e20) | 
`public GLint `[`material_albedo`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a7567d3cd871ab621240317c487b29a62) | 
`public GLint `[`material_roughness`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a9a3611501e8d37ce5fd887314f370ce5) | 
`public GLint `[`material_metallic`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a29276a95d18358859e9738f353ca9ead) | 
`public GLint `[`material_opacity`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a072099e10bfc39253fba74aca8ba2b34) | 
`public GLint `[`material_emission`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a76f55fb32fccebc3163f95cc2e23c246) | 
`public GLint `[`material_ambient_occlusion`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1acd4cfcc22ef44a93832c558e2ea4ea41) | 
`public GLint `[`material_emission_strength`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a85901661872b54918e45a4701f3b2f93) | 
`public GLint `[`material_factor`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1af9be945fb4d2a357a73e5ed606bd57a9) | 
`public GLint `[`camera_resolution`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a52e093cdaaba6d462497b44e6d1e06b4) | 
`public GLint `[`camera_position`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a3f3323adc32ccec304ca3cf31bb8b493) | 
`public std::array< GLuint, 2 > `[`shadow_maps`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a538a81e2b65ac101ba57b5cbb4d3f95c) | 
`public std::array< `[`LightUniforms`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms)`, 2 > `[`lights`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1aa71535df545542203e66e52831eceedf) | 
`public GLint `[`fog_color_near`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a0f426a739ae1dc3ea1b6d8abdc66b5c0) | 
`public GLint `[`fog_color_far`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a9112b27990bea38cb52d981c9246af73) | 
`public GLint `[`fog_attenuation_factor`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a5213fface31ca52280204411f1e28058) | 
`public GLint `[`brdf_lut`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a8daae062e42ba676d7dc7350084c8fc3) | 
`public  `[`EnvironmentProgram`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1af168fca32561d56a1a60fa4891058989)`()` | 

## Members

#### `public GLint `[`model_view_projection_matrix`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a19dbce42cdd2d21c4bb1abbc4243f31c) 

#### `public GLint `[`model_matrix`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a7a9bc65452b8df92f97283df3def4bff) 

#### `public GLint `[`normal_matrix`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1aca85aa9b8f315830185000f258192db2) 

#### `public std::array< GLint, 2 > `[`depth_bias_mvps`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a899bd3892676d54fb347ae54ed237e9d) 

#### `public std::array< `[`EnvironmentUniforms`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms)`, 2 > `[`environment_maps`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1ab71db290aed7bfc64672c45ae075caad) 

#### `public GLint `[`material_albedo_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a78d8aef072aac635445bf5d93cc0e976) 

#### `public GLint `[`material_emission_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a7e6c9fe8215c4bad53df83d7ed3bee09) 

#### `public GLint `[`material_normal_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1ad5bf072682c2d52a9bc1e1dae4e62e56) 

#### `public GLint `[`material_metallic_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a6cadd1b386664e396ce3e9ab54b2848e) 

#### `public GLint `[`material_roughness_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a0880e6a7cf3c1099c135c8cc5c4bd097) 

#### `public GLint `[`material_ambient_occlusion_map`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a0c6a8bfd40c36807f875014128062e20) 

#### `public GLint `[`material_albedo`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a7567d3cd871ab621240317c487b29a62) 

#### `public GLint `[`material_roughness`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a9a3611501e8d37ce5fd887314f370ce5) 

#### `public GLint `[`material_metallic`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a29276a95d18358859e9738f353ca9ead) 

#### `public GLint `[`material_opacity`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a072099e10bfc39253fba74aca8ba2b34) 

#### `public GLint `[`material_emission`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a76f55fb32fccebc3163f95cc2e23c246) 

#### `public GLint `[`material_ambient_occlusion`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1acd4cfcc22ef44a93832c558e2ea4ea41) 

#### `public GLint `[`material_emission_strength`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a85901661872b54918e45a4701f3b2f93) 

#### `public GLint `[`material_factor`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1af9be945fb4d2a357a73e5ed606bd57a9) 

#### `public GLint `[`camera_resolution`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a52e093cdaaba6d462497b44e6d1e06b4) 

#### `public GLint `[`camera_position`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a3f3323adc32ccec304ca3cf31bb8b493) 

#### `public std::array< GLuint, 2 > `[`shadow_maps`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a538a81e2b65ac101ba57b5cbb4d3f95c) 

#### `public std::array< `[`LightUniforms`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms)`, 2 > `[`lights`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1aa71535df545542203e66e52831eceedf) 

#### `public GLint `[`fog_color_near`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a0f426a739ae1dc3ea1b6d8abdc66b5c0) 

#### `public GLint `[`fog_color_far`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a9112b27990bea38cb52d981c9246af73) 

#### `public GLint `[`fog_attenuation_factor`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a5213fface31ca52280204411f1e28058) 

#### `public GLint `[`brdf_lut`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1a8daae062e42ba676d7dc7350084c8fc3) 

#### `public  `[`EnvironmentProgram`](#classmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1af168fca32561d56a1a60fa4891058989)`()` 

# class `mos::gfx::Renderer::Shader` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`id`](#classmos_1_1gfx_1_1Renderer_1_1Shader_1ad4221f1ac9092c4e91c2483b83ea4fb4) | 
`public  `[`Shader`](#classmos_1_1gfx_1_1Renderer_1_1Shader_1acab8558429b6c33ff0886001d9bebb98)`(const std::string & source,const GLuint type,const std::string & name)` | 
`public  `[`~Shader`](#classmos_1_1gfx_1_1Renderer_1_1Shader_1a2c2b46b5896dd5e19dd2795913c98896)`()` | 

## Members

#### `public GLuint `[`id`](#classmos_1_1gfx_1_1Renderer_1_1Shader_1ad4221f1ac9092c4e91c2483b83ea4fb4) 

#### `public  `[`Shader`](#classmos_1_1gfx_1_1Renderer_1_1Shader_1acab8558429b6c33ff0886001d9bebb98)`(const std::string & source,const GLuint type,const std::string & name)` 

#### `public  `[`~Shader`](#classmos_1_1gfx_1_1Renderer_1_1Shader_1a2c2b46b5896dd5e19dd2795913c98896)`()` 

# class `mos::gfx::Renderer::StandardProgram` 

```
class mos::gfx::Renderer::StandardProgram
  : public mos::gfx::Renderer::Program
```  

Uniforms for the standard shader.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`model_view_projection_matrix`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ac95e9dffb29d575de98e32f929930319) | 
`public GLint `[`model_matrix`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a1271c3c29186b492db3d0789dc0c614b) | 
`public GLint `[`normal_matrix`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1aa47d97a96e2cadb986324b4ea58dcd22) | 
`public std::array< GLint, 2 > `[`depth_bias_mvps`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a623a1a0c88400520eb2a13c141166028) | 
`public std::array< `[`EnvironmentUniforms`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms)`, 2 > `[`environment_maps`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a5162f357a19557366875084ba529f49f) | 
`public GLint `[`material_albedo_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ae5010f9359ddaa1f8c9439027fbeb515) | 
`public GLint `[`material_emission_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ae284214361a62a4f092e00834ad4a99b) | 
`public GLint `[`material_normal_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a40449b77932821fbc112d059473e0c3d) | 
`public GLint `[`material_metallic_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a8cf084413b2b6cd3fbabd0d55da83942) | 
`public GLint `[`material_roughness_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1aca31968008900964147a8e1c94318d49) | 
`public GLint `[`material_ambient_occlusion_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ac8ec8b3bb7514299a68c51d34c416ca5) | 
`public GLint `[`material_albedo`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ad6fc52cf7f1e515aa86725132ed43146) | 
`public GLint `[`material_roughness`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a11962a06b463cc6134ce4e6ea365ddc9) | 
`public GLint `[`material_metallic`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a9fa042db9c17c208f9e0984209376b19) | 
`public GLint `[`material_opacity`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1abf13a8943a51b7c325db61f856962a30) | 
`public GLint `[`material_emission`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a03bce6df8a5ef7698a61b8c47f4ae03a) | 
`public GLint `[`material_ambient_occlusion`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ad0fc6e62370c7989a86c1e95309597fb) | 
`public GLint `[`material_emission_strength`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a837031951b67e056afa88d55efd033a0) | 
`public GLint `[`material_factor`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a0f5120c91a3d1c7ada00f34c99e91d4e) | 
`public GLint `[`camera_resolution`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1acece858a0b6a2f3f3e60bb4d894f061a) | 
`public GLint `[`camera_position`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1aeffd9491e0809ee2163c1b43d3b67f9a) | 
`public std::array< GLuint, 2 > `[`shadow_maps`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a80f2a120d6db96d3a161aa0bdd3ecf4f) | 
`public std::array< `[`LightUniforms`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms)`, 2 > `[`lights`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a96ff20339b199abbb235510a813846f7) | 
`public GLint `[`fog_color_near`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a9be84195a5ae039b8f501909866c78ff) | 
`public GLint `[`fog_color_far`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a303bca52e0642227d0600f9e89ab929c) | 
`public GLint `[`fog_attenuation_factor`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a370b745e3c65a8de817acc838307439c) | 
`public GLint `[`brdf_lut`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a79e90c69c0eea0b6fc7835ca1bbc7c81) | 
`public  `[`StandardProgram`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a0a235d4745dcdae311af3935adb7dfe0)`()` | 

## Members

#### `public GLint `[`model_view_projection_matrix`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ac95e9dffb29d575de98e32f929930319) 

#### `public GLint `[`model_matrix`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a1271c3c29186b492db3d0789dc0c614b) 

#### `public GLint `[`normal_matrix`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1aa47d97a96e2cadb986324b4ea58dcd22) 

#### `public std::array< GLint, 2 > `[`depth_bias_mvps`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a623a1a0c88400520eb2a13c141166028) 

#### `public std::array< `[`EnvironmentUniforms`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms)`, 2 > `[`environment_maps`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a5162f357a19557366875084ba529f49f) 

#### `public GLint `[`material_albedo_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ae5010f9359ddaa1f8c9439027fbeb515) 

#### `public GLint `[`material_emission_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ae284214361a62a4f092e00834ad4a99b) 

#### `public GLint `[`material_normal_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a40449b77932821fbc112d059473e0c3d) 

#### `public GLint `[`material_metallic_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a8cf084413b2b6cd3fbabd0d55da83942) 

#### `public GLint `[`material_roughness_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1aca31968008900964147a8e1c94318d49) 

#### `public GLint `[`material_ambient_occlusion_map`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ac8ec8b3bb7514299a68c51d34c416ca5) 

#### `public GLint `[`material_albedo`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ad6fc52cf7f1e515aa86725132ed43146) 

#### `public GLint `[`material_roughness`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a11962a06b463cc6134ce4e6ea365ddc9) 

#### `public GLint `[`material_metallic`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a9fa042db9c17c208f9e0984209376b19) 

#### `public GLint `[`material_opacity`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1abf13a8943a51b7c325db61f856962a30) 

#### `public GLint `[`material_emission`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a03bce6df8a5ef7698a61b8c47f4ae03a) 

#### `public GLint `[`material_ambient_occlusion`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1ad0fc6e62370c7989a86c1e95309597fb) 

#### `public GLint `[`material_emission_strength`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a837031951b67e056afa88d55efd033a0) 

#### `public GLint `[`material_factor`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a0f5120c91a3d1c7ada00f34c99e91d4e) 

#### `public GLint `[`camera_resolution`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1acece858a0b6a2f3f3e60bb4d894f061a) 

#### `public GLint `[`camera_position`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1aeffd9491e0809ee2163c1b43d3b67f9a) 

#### `public std::array< GLuint, 2 > `[`shadow_maps`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a80f2a120d6db96d3a161aa0bdd3ecf4f) 

#### `public std::array< `[`LightUniforms`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms)`, 2 > `[`lights`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a96ff20339b199abbb235510a813846f7) 

#### `public GLint `[`fog_color_near`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a9be84195a5ae039b8f501909866c78ff) 

#### `public GLint `[`fog_color_far`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a303bca52e0642227d0600f9e89ab929c) 

#### `public GLint `[`fog_attenuation_factor`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a370b745e3c65a8de817acc838307439c) 

#### `public GLint `[`brdf_lut`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a79e90c69c0eea0b6fc7835ca1bbc7c81) 

#### `public  `[`StandardProgram`](#classmos_1_1gfx_1_1Renderer_1_1StandardProgram_1a0a235d4745dcdae311af3935adb7dfe0)`()` 

# class `mos::gfx::Renderer::TextureBuffer2D` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`texture`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1a531978c83affcb94a106ee43b8330158) | 
`public TimePoint `[`modified`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1ac24d9d8edecf24292579e5db86b00474) | 
`public  explicit `[`TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1a1017ea2751ef41c8afa7435a37f15095)`(const `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D)` & texture_2d)` | 
`public  `[`TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1acc79e41981f87867f6b47d698617feda)`(const GLuint internal_format,const GLuint external_format,const int width,const int height,const GLuint wrap,const void * data,const bool mipmaps,const TimePoint & modified)` | 
`public  `[`~TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1a8361941b0d65f344fdece8fa79e1dbcc)`()` | 

## Members

#### `public GLuint `[`texture`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1a531978c83affcb94a106ee43b8330158) 

#### `public TimePoint `[`modified`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1ac24d9d8edecf24292579e5db86b00474) 

#### `public  explicit `[`TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1a1017ea2751ef41c8afa7435a37f15095)`(const `[`Texture2D`](#classmos_1_1gfx_1_1Texture2D)` & texture_2d)` 

#### `public  `[`TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1acc79e41981f87867f6b47d698617feda)`(const GLuint internal_format,const GLuint external_format,const int width,const int height,const GLuint wrap,const void * data,const bool mipmaps,const TimePoint & modified)` 

#### `public  `[`~TextureBuffer2D`](#classmos_1_1gfx_1_1Renderer_1_1TextureBuffer2D_1a8361941b0d65f344fdece8fa79e1dbcc)`()` 

# struct `mos::gfx::Renderer::BloomProgram` 

```
struct mos::gfx::Renderer::BloomProgram
  : public mos::gfx::Renderer::Program
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ada97159b7ea43c0c35e4cb13185125e9) | 
`public GLint `[`bright_color_texture`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ad871fe1ee5ee6f03b60887ac038de36f) | 
`public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ac38a0103be832da2508d41c32c791f1a) | 
`public  `[`BloomProgram`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ad82f175bbe7e5a7d3324ab5624a201f0)`()` | 

## Members

#### `public GLint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ada97159b7ea43c0c35e4cb13185125e9) 

#### `public GLint `[`bright_color_texture`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ad871fe1ee5ee6f03b60887ac038de36f) 

#### `public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ac38a0103be832da2508d41c32c791f1a) 

#### `public  `[`BloomProgram`](#structmos_1_1gfx_1_1Renderer_1_1BloomProgram_1ad82f175bbe7e5a7d3324ab5624a201f0)`()` 

# struct `mos::gfx::Renderer::BlurProgram` 

```
struct mos::gfx::Renderer::BlurProgram
  : public mos::gfx::Renderer::Program
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram_1aff275fee93a818fa1559160d1eec816c) | 
`public GLint `[`horizontal`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram_1ad673c88eb1d6c32e5d08a41f28c58de5) | 
`public  `[`BlurProgram`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram_1a6347e014d7515916cfccaf749be6ebfd)`()` | 

## Members

#### `public GLint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram_1aff275fee93a818fa1559160d1eec816c) 

#### `public GLint `[`horizontal`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram_1ad673c88eb1d6c32e5d08a41f28c58de5) 

#### `public  `[`BlurProgram`](#structmos_1_1gfx_1_1Renderer_1_1BlurProgram_1a6347e014d7515916cfccaf749be6ebfd)`()` 

# struct `mos::gfx::Renderer::BlurTarget` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1a986d15239b36ad1346a0196e73e61218) | 
`public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1a8bf8330768d0e062c0e19bfe5302f80e) | 
`public  `[`BlurTarget`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1a8bf1b1ceed1383b1d18745a31309ac44)`(const glm::ivec2 & resolution)` | 
`public  `[`~BlurTarget`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1ac5d57192caa7f70b0b5568b54dbd3ed1)`()` | 

## Members

#### `public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1a986d15239b36ad1346a0196e73e61218) 

#### `public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1a8bf8330768d0e062c0e19bfe5302f80e) 

#### `public  `[`BlurTarget`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1a8bf1b1ceed1383b1d18745a31309ac44)`(const glm::ivec2 & resolution)` 

#### `public  `[`~BlurTarget`](#structmos_1_1gfx_1_1Renderer_1_1BlurTarget_1ac5d57192caa7f70b0b5568b54dbd3ed1)`()` 

# struct `mos::gfx::Renderer::Box` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`buffer`](#structmos_1_1gfx_1_1Renderer_1_1Box_1adc8376bbdca5c822a6939eab45a54a83) | 
`public GLuint `[`element_buffer`](#structmos_1_1gfx_1_1Renderer_1_1Box_1a00df14c92c82d20a59302c0aa9a12560) | 
`public GLuint `[`vertex_array`](#structmos_1_1gfx_1_1Renderer_1_1Box_1afd4c441cc68bc2ced811d15b6c924dae) | 
`public  `[`Box`](#structmos_1_1gfx_1_1Renderer_1_1Box_1a02cf29987b03e2f0814933e7eab4cd56)`()` | 
`public  `[`~Box`](#structmos_1_1gfx_1_1Renderer_1_1Box_1a9fd3c212bec66af2e4f91738de6721fc)`()` | 

## Members

#### `public GLuint `[`buffer`](#structmos_1_1gfx_1_1Renderer_1_1Box_1adc8376bbdca5c822a6939eab45a54a83) 

#### `public GLuint `[`element_buffer`](#structmos_1_1gfx_1_1Renderer_1_1Box_1a00df14c92c82d20a59302c0aa9a12560) 

#### `public GLuint `[`vertex_array`](#structmos_1_1gfx_1_1Renderer_1_1Box_1afd4c441cc68bc2ced811d15b6c924dae) 

#### `public  `[`Box`](#structmos_1_1gfx_1_1Renderer_1_1Box_1a02cf29987b03e2f0814933e7eab4cd56)`()` 

#### `public  `[`~Box`](#structmos_1_1gfx_1_1Renderer_1_1Box_1a9fd3c212bec66af2e4f91738de6721fc)`()` 

# struct `mos::gfx::Renderer::BoxProgram` 

```
struct mos::gfx::Renderer::BoxProgram
  : public mos::gfx::Renderer::Program
```  

Uniforms for the bounding box shader program.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`mvp`](#structmos_1_1gfx_1_1Renderer_1_1BoxProgram_1a7c22c8927261e36ede19b0b3f3c94227) | 
`public  `[`BoxProgram`](#structmos_1_1gfx_1_1Renderer_1_1BoxProgram_1a08922e0efbbb3eb05b079d3bf91544e5)`()` | 

## Members

#### `public GLint `[`mvp`](#structmos_1_1gfx_1_1Renderer_1_1BoxProgram_1a7c22c8927261e36ede19b0b3f3c94227) 

#### `public  `[`BoxProgram`](#structmos_1_1gfx_1_1Renderer_1_1BoxProgram_1a08922e0efbbb3eb05b079d3bf91544e5)`()` 

# struct `mos::gfx::Renderer::Buffer` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`id`](#structmos_1_1gfx_1_1Renderer_1_1Buffer_1a66fce734497ce41d13fac60627fbbe8d) | 
`public TimePoint `[`modified`](#structmos_1_1gfx_1_1Renderer_1_1Buffer_1a9824df6bc68687b253c7f3280e84d7e9) | 

## Members

#### `public GLuint `[`id`](#structmos_1_1gfx_1_1Renderer_1_1Buffer_1a66fce734497ce41d13fac60627fbbe8d) 

#### `public TimePoint `[`modified`](#structmos_1_1gfx_1_1Renderer_1_1Buffer_1a9824df6bc68687b253c7f3280e84d7e9) 

# struct `mos::gfx::Renderer::DepthProgram` 

```
struct mos::gfx::Renderer::DepthProgram
  : public mos::gfx::Renderer::Program
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`model_view_projection_matrix`](#structmos_1_1gfx_1_1Renderer_1_1DepthProgram_1a8e556806b1557872aaa2e6b4d72d6239) | 
`public  `[`DepthProgram`](#structmos_1_1gfx_1_1Renderer_1_1DepthProgram_1a2db91738abae0532eb207fa5b4c09551)`()` | 

## Members

#### `public GLint `[`model_view_projection_matrix`](#structmos_1_1gfx_1_1Renderer_1_1DepthProgram_1a8e556806b1557872aaa2e6b4d72d6239) 

#### `public  `[`DepthProgram`](#structmos_1_1gfx_1_1Renderer_1_1DepthProgram_1a2db91738abae0532eb207fa5b4c09551)`()` 

# struct `mos::gfx::Renderer::EnvironmentMapTarget` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1a9c0700243fd21aa7e2e55eb37ffdc518) | 
`public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1ae4b3ecf96f52da224da1de15e2d517e3) | 
`public  `[`EnvironmentMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1a297429d2bfe4d0dd2f8b726e7f47d58f)`(const RenderBuffer & render_buffer)` | 
`public  `[`~EnvironmentMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1ab3b7238bb29eed269604eec4b8f0564d)`()` | 

## Members

#### `public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1a9c0700243fd21aa7e2e55eb37ffdc518) 

#### `public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1ae4b3ecf96f52da224da1de15e2d517e3) 

#### `public  `[`EnvironmentMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1a297429d2bfe4d0dd2f8b726e7f47d58f)`(const RenderBuffer & render_buffer)` 

#### `public  `[`~EnvironmentMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentMapTarget_1ab3b7238bb29eed269604eec4b8f0564d)`()` 

# struct `mos::gfx::Renderer::EnvironmentProgram::EnvironmentUniforms` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`map`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1a33049b6328e775de8edb5e2696234c3a) | 
`public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1a64d28a54e546275df6ab8d014efaa4d6) | 
`public GLint `[`extent`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1afdb6c61a102846b4e69c02930be41282) | 
`public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1a7b2830e3934897ac6a59991757fbe4d6) | 

## Members

#### `public GLint `[`map`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1a33049b6328e775de8edb5e2696234c3a) 

#### `public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1a64d28a54e546275df6ab8d014efaa4d6) 

#### `public GLint `[`extent`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1afdb6c61a102846b4e69c02930be41282) 

#### `public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1EnvironmentUniforms_1a7b2830e3934897ac6a59991757fbe4d6) 

# struct `mos::gfx::Renderer::StandardProgram::EnvironmentUniforms` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`map`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1aaca6e763b4a6b174afd7ccb168495cf8) | 
`public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1ab3df9af551dc3c9e9edbef9c75a25619) | 
`public GLint `[`extent`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1a6a63a9eb23635b07c847af651f1e6d7a) | 
`public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1aee12c38fef7d49003a222b739b8184e0) | 

## Members

#### `public GLint `[`map`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1aaca6e763b4a6b174afd7ccb168495cf8) 

#### `public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1ab3df9af551dc3c9e9edbef9c75a25619) 

#### `public GLint `[`extent`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1a6a63a9eb23635b07c847af651f1e6d7a) 

#### `public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1EnvironmentUniforms_1aee12c38fef7d49003a222b739b8184e0) 

# struct `mos::gfx::Renderer::EnvironmentProgram::LightUniforms` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a6932c7e03d3b552aefeae78a7d561892) | 
`public GLint `[`color`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a910768ed1e0d56cc7a5783a07e50b8f4) | 
`public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a845ee1b9a6c28f5df96d87fcca628572) | 
`public GLint `[`view`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1ad7cff41904758ede1eb0127fcd42c8a0) | 
`public GLint `[`projection`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a02f815b8bcd57dc5a19d98d3e479fc86) | 
`public GLint `[`angle`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a9c50bd4d3165bc0d5d97d2cdad377911) | 
`public GLint `[`direction`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1aa397c97cee8f9428f4b92f43499b8572) | 

## Members

#### `public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a6932c7e03d3b552aefeae78a7d561892) 

#### `public GLint `[`color`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a910768ed1e0d56cc7a5783a07e50b8f4) 

#### `public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a845ee1b9a6c28f5df96d87fcca628572) 

#### `public GLint `[`view`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1ad7cff41904758ede1eb0127fcd42c8a0) 

#### `public GLint `[`projection`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a02f815b8bcd57dc5a19d98d3e479fc86) 

#### `public GLint `[`angle`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1a9c50bd4d3165bc0d5d97d2cdad377911) 

#### `public GLint `[`direction`](#structmos_1_1gfx_1_1Renderer_1_1EnvironmentProgram_1_1LightUniforms_1aa397c97cee8f9428f4b92f43499b8572) 

# struct `mos::gfx::Renderer::StandardProgram::LightUniforms` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1adaf31a7cd0ba597c5035101b6847f011) | 
`public GLint `[`color`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1aff25b3e3a0e942a8df6045e8c7bd800a) | 
`public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a7d27df5b6651e7720fbf7ccb87f33f75) | 
`public GLint `[`view`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a898aefb4fdfc79dcb5eb24a12872c6e1) | 
`public GLint `[`projection`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a537f3e814d51692688739e199617d5e3) | 
`public GLint `[`angle`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a98a2e86afc7c98b8876988731c8b9c9f) | 
`public GLint `[`direction`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a40cc8dc10f232c3871e93627d7ea4f61) | 

## Members

#### `public GLint `[`position`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1adaf31a7cd0ba597c5035101b6847f011) 

#### `public GLint `[`color`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1aff25b3e3a0e942a8df6045e8c7bd800a) 

#### `public GLint `[`strength`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a7d27df5b6651e7720fbf7ccb87f33f75) 

#### `public GLint `[`view`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a898aefb4fdfc79dcb5eb24a12872c6e1) 

#### `public GLint `[`projection`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a537f3e814d51692688739e199617d5e3) 

#### `public GLint `[`angle`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a98a2e86afc7c98b8876988731c8b9c9f) 

#### `public GLint `[`direction`](#structmos_1_1gfx_1_1Renderer_1_1StandardProgram_1_1LightUniforms_1a40cc8dc10f232c3871e93627d7ea4f61) 

# struct `mos::gfx::Renderer::MultisampleProgram` 

```
struct mos::gfx::Renderer::MultisampleProgram
  : public mos::gfx::Renderer::Program
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram_1a574f7dad6fd33a550f96bc1ca3e0a0cc) | 
`public GLint `[`depth_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram_1ad942c0adec795f6a6f7c964601867369) | 
`public  `[`MultisampleProgram`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram_1a4a9a3433899da1572b41abfc30177d5c)`()` | 

## Members

#### `public GLint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram_1a574f7dad6fd33a550f96bc1ca3e0a0cc) 

#### `public GLint `[`depth_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram_1ad942c0adec795f6a6f7c964601867369) 

#### `public  `[`MultisampleProgram`](#structmos_1_1gfx_1_1Renderer_1_1MultisampleProgram_1a4a9a3433899da1572b41abfc30177d5c)`()` 

# struct `mos::gfx::Renderer::MultiTarget` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1a666bd4e6022bbb04a23a812e797df241) | 
`public GLuint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1a8b938d732378931b25cbabe130352210) | 
`public GLuint `[`bright_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1aabd2825773096f29a9ea00c5f11d413b) | 
`public  `[`MultiTarget`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1af6e1032c4655725f17c660d0a03fb11c)`(const glm::ivec2 & resolution)` | 
`public  `[`~MultiTarget`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1a953646aa83568322525ce6cc7929df6c)`()` | 

## Members

#### `public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1a666bd4e6022bbb04a23a812e797df241) 

#### `public GLuint `[`color_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1a8b938d732378931b25cbabe130352210) 

#### `public GLuint `[`bright_texture`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1aabd2825773096f29a9ea00c5f11d413b) 

#### `public  `[`MultiTarget`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1af6e1032c4655725f17c660d0a03fb11c)`(const glm::ivec2 & resolution)` 

#### `public  `[`~MultiTarget`](#structmos_1_1gfx_1_1Renderer_1_1MultiTarget_1a953646aa83568322525ce6cc7929df6c)`()` 

# struct `mos::gfx::Renderer::ParticleProgram` 

```
struct mos::gfx::Renderer::ParticleProgram
  : public mos::gfx::Renderer::Program
```  

Uniforms for the particle shader program.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLint `[`mvp`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a33c8d66d7ac7a37b37fe23b7973faf7c) | 
`public GLint `[`mv`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1ae3361615e7fc5bfd3687654a8fe0f294) | 
`public GLint `[`p`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a4246b04d182fc7ad2eec721b18883a59) | 
`public GLint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a43f250ab2ceb5d2448b801191ee7b4b3) | 
`public GLint `[`resolution`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a4fc02815fe5ed118af99044293600640) | 
`public  `[`ParticleProgram`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a7e983cf4a2d05c293fd5ed6ae70cd3c7)`()` | 

## Members

#### `public GLint `[`mvp`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a33c8d66d7ac7a37b37fe23b7973faf7c) 

#### `public GLint `[`mv`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1ae3361615e7fc5bfd3687654a8fe0f294) 

#### `public GLint `[`p`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a4246b04d182fc7ad2eec721b18883a59) 

#### `public GLint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a43f250ab2ceb5d2448b801191ee7b4b3) 

#### `public GLint `[`resolution`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a4fc02815fe5ed118af99044293600640) 

#### `public  `[`ParticleProgram`](#structmos_1_1gfx_1_1Renderer_1_1ParticleProgram_1a7e983cf4a2d05c293fd5ed6ae70cd3c7)`()` 

# struct `mos::gfx::Renderer::Program` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`program`](#structmos_1_1gfx_1_1Renderer_1_1Program_1a7deb6c3e9a6d40d1d965d9c87fda2750) | 
`public  `[`Program`](#structmos_1_1gfx_1_1Renderer_1_1Program_1a2e2eeda5dc5fcc03ef24629ff6f18ce3)`()` | 
`public  `[`~Program`](#structmos_1_1gfx_1_1Renderer_1_1Program_1a23852b2c9b0e927f06305fab09ed633b)`()` | 
`public void `[`check`](#structmos_1_1gfx_1_1Renderer_1_1Program_1ad05bc70deb4415d205ad3578672669d3)`(const std::string & name)` | 
`public void `[`link`](#structmos_1_1gfx_1_1Renderer_1_1Program_1ae51361004445f537ab2582d06874c1ef)`(const std::string & name)` | 

## Members

#### `public GLuint `[`program`](#structmos_1_1gfx_1_1Renderer_1_1Program_1a7deb6c3e9a6d40d1d965d9c87fda2750) 

#### `public  `[`Program`](#structmos_1_1gfx_1_1Renderer_1_1Program_1a2e2eeda5dc5fcc03ef24629ff6f18ce3)`()` 

#### `public  `[`~Program`](#structmos_1_1gfx_1_1Renderer_1_1Program_1a23852b2c9b0e927f06305fab09ed633b)`()` 

#### `public void `[`check`](#structmos_1_1gfx_1_1Renderer_1_1Program_1ad05bc70deb4415d205ad3578672669d3)`(const std::string & name)` 

#### `public void `[`link`](#structmos_1_1gfx_1_1Renderer_1_1Program_1ae51361004445f537ab2582d06874c1ef)`(const std::string & name)` 

# struct `mos::gfx::Renderer::Quad` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`vertex_array`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1a70a4ed064ad6779968db577920d39549) | 
`public GLuint `[`buffer`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1ae492785f7a82559de5a1a461d62280fa) | 
`public  `[`Quad`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1a35cad58476c937d301d6eba16e2e7124)`()` | 
`public  `[`~Quad`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1acd7da9e2430c3a35e89def5df9457870)`()` | 

## Members

#### `public GLuint `[`vertex_array`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1a70a4ed064ad6779968db577920d39549) 

#### `public GLuint `[`buffer`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1ae492785f7a82559de5a1a461d62280fa) 

#### `public  `[`Quad`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1a35cad58476c937d301d6eba16e2e7124)`()` 

#### `public  `[`~Quad`](#structmos_1_1gfx_1_1Renderer_1_1Quad_1acd7da9e2430c3a35e89def5df9457870)`()` 

# struct `mos::gfx::Renderer::RenderBuffer` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`render_buffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1aa5a88154031f710e24e50435c54595f2) | 
`public int `[`resolution`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1a42cdd5279636ef1cc565af94cf689a3a) | 
`public  explicit `[`RenderBuffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1a168e1195d84a57eebb697e88a842dd47)`(const int resolution)` | 
`public  `[`~RenderBuffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1ac1ffd79052e304b510b4aa289ac5eeda)`()` | 

## Members

#### `public GLuint `[`render_buffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1aa5a88154031f710e24e50435c54595f2) 

#### `public int `[`resolution`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1a42cdd5279636ef1cc565af94cf689a3a) 

#### `public  explicit `[`RenderBuffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1a168e1195d84a57eebb697e88a842dd47)`(const int resolution)` 

#### `public  `[`~RenderBuffer`](#structmos_1_1gfx_1_1Renderer_1_1RenderBuffer_1ac1ffd79052e304b510b4aa289ac5eeda)`()` 

# struct `mos::gfx::Renderer::ShadowMapTarget` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1a301d10411054d2b1ec1377c4628114b0) | 
`public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1abf7194f72125133ae61430d7ef5c79ce) | 
`public  `[`ShadowMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1ae34016ad1f7b585af1e78cf422107447)`(const RenderBuffer & render_buffer)` | 
`public  `[`~ShadowMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1a60544fc85f0aaf8dce49fa7e19a01d6f)`()` | 

## Members

#### `public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1a301d10411054d2b1ec1377c4628114b0) 

#### `public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1abf7194f72125133ae61430d7ef5c79ce) 

#### `public  `[`ShadowMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1ae34016ad1f7b585af1e78cf422107447)`(const RenderBuffer & render_buffer)` 

#### `public  `[`~ShadowMapTarget`](#structmos_1_1gfx_1_1Renderer_1_1ShadowMapTarget_1a60544fc85f0aaf8dce49fa7e19a01d6f)`()` 

# struct `mos::gfx::Renderer::StandardTarget` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a61b3720756ab615df89fa6974f5a05d2) | 
`public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a8f20deb6c68d99cebcda543887cd740d) | 
`public GLuint `[`depth_texture`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1ae14619b05379359ed884ada254b62513) | 
`public  `[`StandardTarget`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a6c63929707a6e4de377195b667b0a3d9)`(const glm::ivec2 & resolution)` | 
`public  `[`~StandardTarget`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a795ca4e9ff795e3abdef716baec48d74)`()` | 

## Members

#### `public GLuint `[`frame_buffer`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a61b3720756ab615df89fa6974f5a05d2) 

#### `public GLuint `[`texture`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a8f20deb6c68d99cebcda543887cd740d) 

#### `public GLuint `[`depth_texture`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1ae14619b05379359ed884ada254b62513) 

#### `public  `[`StandardTarget`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a6c63929707a6e4de377195b667b0a3d9)`(const glm::ivec2 & resolution)` 

#### `public  `[`~StandardTarget`](#structmos_1_1gfx_1_1Renderer_1_1StandardTarget_1a795ca4e9ff795e3abdef716baec48d74)`()` 

Generated by [Moxygen](https://sourcey.com/moxygen)