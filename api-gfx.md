# group `gfx` {#group__gfx}

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Animation`](#group__gfx_1gab7b44b83886d2ef8e6b9acba2d3ec488)`() = default`            | 
`public  `[`~Animation`](#group__gfx_1ga50770d37663a0506fdaa0a2f68b28803)`() = default`            | 
`public  `[`Animation`](#group__gfx_1gaa3d08cc79b18fc40ccad349df431e4bb)`(const std::map< unsigned int, std::shared_ptr< Mesh const >> keyframes,const unsigned int frame_rate)`            | 
`public  `[`Animation`](#group__gfx_1ga29aba724ec28e24df118b8aaa15e4fe1)`(std::initializer_list< std::pair< unsigned int, std::shared_ptr< Mesh const >>> keyframes,const unsigned int frame_rate)`            | 
`public  `[`Animation`](#group__gfx_1ga30d9fce1bef9a67d9374ba1c3e13b850)`(const std::string & path)`            | 
`public  `[`Animation`](#group__gfx_1ga42e99cab0d618ce7628652b5288f37ec)`(Assets & assets,const std::string & path)`            | 
`public void `[`update`](#group__gfx_1ga9aca652764e1820efc32a286111367da)`(const float dt)`            | 
`public int `[`frame`](#group__gfx_1ga754b4c1a0390aa19f5e7bb0656fd30a8)`() const`            | Current frame.
`public void `[`reset`](#group__gfx_1ga6000a70e8e7987f6103555f42a79cf2c)`()`            | Restart the animation.
`public void `[`frame_rate`](#group__gfx_1ga0bd103ed4b9509d589fa7ecb83dd1b60)`(const unsigned int frame_rate)`            | Set frame rate.
`public unsigned int `[`frame_rate`](#group__gfx_1gaa075ed0576d8b072d27e105796b19e75)`() const`            | Frames per second.
`public std::shared_ptr< Mesh > `[`mesh`](#group__gfx_1ga2ef4cb3a4a9a85faae79e485c6c4a09b)`()`            | The mesh being animated.
`namespace `[`mos::gfx`](#namespacemos_1_1gfx) | 

## Members

#### `public  `[`Animation`](#group__gfx_1gab7b44b83886d2ef8e6b9acba2d3ec488)`() = default` {#group__gfx_1gab7b44b83886d2ef8e6b9acba2d3ec488}

#### `public  `[`~Animation`](#group__gfx_1ga50770d37663a0506fdaa0a2f68b28803)`() = default` {#group__gfx_1ga50770d37663a0506fdaa0a2f68b28803}

#### `public  `[`Animation`](#group__gfx_1gaa3d08cc79b18fc40ccad349df431e4bb)`(const std::map< unsigned int, std::shared_ptr< Mesh const >> keyframes,const unsigned int frame_rate)` {#group__gfx_1gaa3d08cc79b18fc40ccad349df431e4bb}

#### `public  `[`Animation`](#group__gfx_1ga29aba724ec28e24df118b8aaa15e4fe1)`(std::initializer_list< std::pair< unsigned int, std::shared_ptr< Mesh const >>> keyframes,const unsigned int frame_rate)` {#group__gfx_1ga29aba724ec28e24df118b8aaa15e4fe1}

#### `public  `[`Animation`](#group__gfx_1ga30d9fce1bef9a67d9374ba1c3e13b850)`(const std::string & path)` {#group__gfx_1ga30d9fce1bef9a67d9374ba1c3e13b850}

#### `public  `[`Animation`](#group__gfx_1ga42e99cab0d618ce7628652b5288f37ec)`(Assets & assets,const std::string & path)` {#group__gfx_1ga42e99cab0d618ce7628652b5288f37ec}

#### `public void `[`update`](#group__gfx_1ga9aca652764e1820efc32a286111367da)`(const float dt)` {#group__gfx_1ga9aca652764e1820efc32a286111367da}

#### `public int `[`frame`](#group__gfx_1ga754b4c1a0390aa19f5e7bb0656fd30a8)`() const` {#group__gfx_1ga754b4c1a0390aa19f5e7bb0656fd30a8}

Current frame.

#### `public void `[`reset`](#group__gfx_1ga6000a70e8e7987f6103555f42a79cf2c)`()` {#group__gfx_1ga6000a70e8e7987f6103555f42a79cf2c}

Restart the animation.

#### `public void `[`frame_rate`](#group__gfx_1ga0bd103ed4b9509d589fa7ecb83dd1b60)`(const unsigned int frame_rate)` {#group__gfx_1ga0bd103ed4b9509d589fa7ecb83dd1b60}

Set frame rate.

#### `public unsigned int `[`frame_rate`](#group__gfx_1gaa075ed0576d8b072d27e105796b19e75)`() const` {#group__gfx_1gaa075ed0576d8b072d27e105796b19e75}

Frames per second.

#### `public std::shared_ptr< Mesh > `[`mesh`](#group__gfx_1ga2ef4cb3a4a9a85faae79e485c6c4a09b)`()` {#group__gfx_1ga2ef4cb3a4a9a85faae79e485c6c4a09b}

The mesh being animated.

# namespace `mos::gfx` {#namespacemos_1_1gfx}

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`mos::gfx::Animation`](api-gfx.md#classmos_1_1gfx_1_1Animation) | Keyframe animation, interpolation between meshes.

# class `mos::gfx::Animation` {#classmos_1_1gfx_1_1Animation}

Keyframe animation, interpolation between meshes.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Animation`](#group__gfx_1gab7b44b83886d2ef8e6b9acba2d3ec488)`() = default` | 
`public  `[`~Animation`](#group__gfx_1ga50770d37663a0506fdaa0a2f68b28803)`() = default` | 
`public  `[`Animation`](#group__gfx_1gaa3d08cc79b18fc40ccad349df431e4bb)`(const std::map< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >> keyframes,const unsigned int frame_rate)` | 
`public  `[`Animation`](#group__gfx_1ga29aba724ec28e24df118b8aaa15e4fe1)`(std::initializer_list< std::pair< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >>> keyframes,const unsigned int frame_rate)` | 
`public  `[`Animation`](#group__gfx_1ga30d9fce1bef9a67d9374ba1c3e13b850)`(const std::string & path)` | 
`public  `[`Animation`](#group__gfx_1ga42e99cab0d618ce7628652b5288f37ec)`(`[`Assets`](#classmos_1_1gfx_1_1Assets)` & assets,const std::string & path)` | 
`public void `[`update`](#group__gfx_1ga9aca652764e1820efc32a286111367da)`(const float dt)` | 
`public int `[`frame`](#group__gfx_1ga754b4c1a0390aa19f5e7bb0656fd30a8)`() const` | Current frame.
`public void `[`reset`](#group__gfx_1ga6000a70e8e7987f6103555f42a79cf2c)`()` | Restart the animation.
`public void `[`frame_rate`](#group__gfx_1ga0bd103ed4b9509d589fa7ecb83dd1b60)`(const unsigned int frame_rate)` | Set frame rate.
`public unsigned int `[`frame_rate`](#group__gfx_1gaa075ed0576d8b072d27e105796b19e75)`() const` | Frames per second.
`public std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` > `[`mesh`](#group__gfx_1ga2ef4cb3a4a9a85faae79e485c6c4a09b)`()` | The mesh being animated.

## Members

#### `public  `[`Animation`](#group__gfx_1gab7b44b83886d2ef8e6b9acba2d3ec488)`() = default` {#group__gfx_1gab7b44b83886d2ef8e6b9acba2d3ec488}

#### `public  `[`~Animation`](#group__gfx_1ga50770d37663a0506fdaa0a2f68b28803)`() = default` {#group__gfx_1ga50770d37663a0506fdaa0a2f68b28803}

#### `public  `[`Animation`](#group__gfx_1gaa3d08cc79b18fc40ccad349df431e4bb)`(const std::map< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >> keyframes,const unsigned int frame_rate)` {#group__gfx_1gaa3d08cc79b18fc40ccad349df431e4bb}

#### `public  `[`Animation`](#group__gfx_1ga29aba724ec28e24df118b8aaa15e4fe1)`(std::initializer_list< std::pair< unsigned int, std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` const >>> keyframes,const unsigned int frame_rate)` {#group__gfx_1ga29aba724ec28e24df118b8aaa15e4fe1}

#### `public  `[`Animation`](#group__gfx_1ga30d9fce1bef9a67d9374ba1c3e13b850)`(const std::string & path)` {#group__gfx_1ga30d9fce1bef9a67d9374ba1c3e13b850}

#### `public  `[`Animation`](#group__gfx_1ga42e99cab0d618ce7628652b5288f37ec)`(`[`Assets`](#classmos_1_1gfx_1_1Assets)` & assets,const std::string & path)` {#group__gfx_1ga42e99cab0d618ce7628652b5288f37ec}

#### `public void `[`update`](#group__gfx_1ga9aca652764e1820efc32a286111367da)`(const float dt)` {#group__gfx_1ga9aca652764e1820efc32a286111367da}

#### `public int `[`frame`](#group__gfx_1ga754b4c1a0390aa19f5e7bb0656fd30a8)`() const` {#group__gfx_1ga754b4c1a0390aa19f5e7bb0656fd30a8}

Current frame.

#### `public void `[`reset`](#group__gfx_1ga6000a70e8e7987f6103555f42a79cf2c)`()` {#group__gfx_1ga6000a70e8e7987f6103555f42a79cf2c}

Restart the animation.

#### `public void `[`frame_rate`](#group__gfx_1ga0bd103ed4b9509d589fa7ecb83dd1b60)`(const unsigned int frame_rate)` {#group__gfx_1ga0bd103ed4b9509d589fa7ecb83dd1b60}

Set frame rate.

#### `public unsigned int `[`frame_rate`](#group__gfx_1gaa075ed0576d8b072d27e105796b19e75)`() const` {#group__gfx_1gaa075ed0576d8b072d27e105796b19e75}

Frames per second.

#### `public std::shared_ptr< `[`Mesh`](#classmos_1_1gfx_1_1Mesh)` > `[`mesh`](#group__gfx_1ga2ef4cb3a4a9a85faae79e485c6c4a09b)`()` {#group__gfx_1ga2ef4cb3a4a9a85faae79e485c6c4a09b}

The mesh being animated.

