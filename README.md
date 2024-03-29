## openCL-devQuery-vecAdd
OpenCL examples:
- Device Query
- Vector Addition

## console output for dev_query 
```
Number of available platforms: 3
[0] Intel(R) CPU Runtime for OpenCL(TM) Applications
[1] Intel(R) OpenCL HD Graphics
[2] NVIDIA CUDA

Number of devices available for each type in Intel(R) CPU Runtime for OpenCL(TM) Applications
CL_DEVICE_TYPE_CPU: 1

Detailed information for CL_DEVICE_TYPE_CPU

CL_DEVICE_TYPE_CPU[0]
CL_DEVICE_NAME: 11th Gen Intel(R) Core(TM) i9-11980HK @ 2.60GHz
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: Intel(R) Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 2.1 (Build 0)
CL_DRIVER_VERSION: 18.1.0.0920
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 2.0
CL_DEVICE_MAX_COMPUTE_UNITS: 16
CL_DEVICE_MAX_CLOCK_FREQUENCY: 2600
CL_DEVICE_MAX_WORK_GROUP_SIZE: 8192
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 1024
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 16768429056
CL_DEVICE_GLOBAL_MEM_SIZE: 67073716224
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 131072
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 262144
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 64
CL_DEVICE_LOCAL_MEM_SIZE: 32768
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 1
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 1
CL_DEVICE_EXTENSIONS: cl_khr_icd cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_khr_byte_addressable_store cl_khr_depth_images cl_khr_3d_image_writes cl_intel_exec_by_local_thread cl_khr_spir cl_khr_fp64 cl_khr_image2d_from_buffer cl_intel_vec_len_hint
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 8
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 4
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 8
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 4
CL_DEVICE_TYPE_GPU: 0

Detailed information for CL_DEVICE_TYPE_GPU
CL_DEVICE_TYPE_ACCELERATOR: 0

Detailed information for CL_DEVICE_TYPE_ACCELERATOR
CL_DEVICE_TYPE_DEFAULT: 1

Detailed information for CL_DEVICE_TYPE_DEFAULT

CL_DEVICE_TYPE_DEFAULT[0]
CL_DEVICE_NAME: 11th Gen Intel(R) Core(TM) i9-11980HK @ 2.60GHz
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: Intel(R) Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 2.1 (Build 0)
CL_DRIVER_VERSION: 18.1.0.0920
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 2.0
CL_DEVICE_MAX_COMPUTE_UNITS: 16
CL_DEVICE_MAX_CLOCK_FREQUENCY: 2600
CL_DEVICE_MAX_WORK_GROUP_SIZE: 8192
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 1024
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 16768429056
CL_DEVICE_GLOBAL_MEM_SIZE: 67073716224
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 131072
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 262144
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 64
CL_DEVICE_LOCAL_MEM_SIZE: 32768
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 1
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 1
CL_DEVICE_EXTENSIONS: cl_khr_icd cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_khr_byte_addressable_store cl_khr_depth_images cl_khr_3d_image_writes cl_intel_exec_by_local_thread cl_khr_spir cl_khr_fp64 cl_khr_image2d_from_buffer cl_intel_vec_len_hint
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 8
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 4
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 8
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 4
CL_DEVICE_TYPE_ALL: 1

Detailed information for CL_DEVICE_TYPE_ALL

CL_DEVICE_TYPE_ALL[0]
CL_DEVICE_NAME: 11th Gen Intel(R) Core(TM) i9-11980HK @ 2.60GHz
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: Intel(R) Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 2.1 (Build 0)
CL_DRIVER_VERSION: 18.1.0.0920
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 2.0
CL_DEVICE_MAX_COMPUTE_UNITS: 16
CL_DEVICE_MAX_CLOCK_FREQUENCY: 2600
CL_DEVICE_MAX_WORK_GROUP_SIZE: 8192
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 1024
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 16768429056
CL_DEVICE_GLOBAL_MEM_SIZE: 67073716224
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 131072
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 262144
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 64
CL_DEVICE_LOCAL_MEM_SIZE: 32768
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 1
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 1
CL_DEVICE_EXTENSIONS: cl_khr_icd cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_khr_byte_addressable_store cl_khr_depth_images cl_khr_3d_image_writes cl_intel_exec_by_local_thread cl_khr_spir cl_khr_fp64 cl_khr_image2d_from_buffer cl_intel_vec_len_hint
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 8
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 4
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 8
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 4

Number of devices available for each type in Intel(R) OpenCL HD Graphics
CL_DEVICE_TYPE_CPU: 0

Detailed information for CL_DEVICE_TYPE_CPU
CL_DEVICE_TYPE_GPU: 1

Detailed information for CL_DEVICE_TYPE_GPU

CL_DEVICE_TYPE_GPU[0]
CL_DEVICE_NAME: Intel(R) UHD Graphics [0x9a60]
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: Intel(R) Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 3.0 NEO
CL_DRIVER_VERSION: 22.01.22131
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 1.2
CL_DEVICE_MAX_COMPUTE_UNITS: 32
CL_DEVICE_MAX_CLOCK_FREQUENCY: 1450
CL_DEVICE_MAX_WORK_GROUP_SIZE: 512
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 1024
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 4294959104
CL_DEVICE_GLOBAL_MEM_SIZE: 53658972160
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 4294959104
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 524288
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 64
CL_DEVICE_LOCAL_MEM_SIZE: 65536
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 52
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 1
CL_DEVICE_EXTENSIONS: cl_khr_byte_addressable_store cl_khr_fp16 cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_icd cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_intel_command_queue_families cl_intel_subgroups cl_intel_required_subgroup_size cl_intel_subgroups_short cl_khr_spir cl_intel_accelerator cl_intel_driver_diagnostics cl_khr_priority_hints cl_khr_throttle_hints cl_khr_create_command_queue cl_intel_subgroups_char cl_intel_subgroups_long cl_khr_il_program cl_intel_mem_force_host_memory cl_khr_subgroup_extended_types cl_khr_subgroup_non_uniform_vote cl_khr_subgroup_ballot cl_khr_subgroup_non_uniform_arithmetic cl_khr_subgroup_shuffle cl_khr_subgroup_shuffle_relative cl_khr_subgroup_clustered_reduce cl_intel_device_attribute_query cl_khr_suggested_local_work_size cl_intel_spirv_media_block_io cl_intel_spirv_subgroups cl_khr_spirv_no_integer_wrap_decoration cl_intel_unified_shared_memory_preview cl_khr_mipmap_image cl_khr_mipmap_image_writes cl_intel_planar_yuv cl_intel_packed_yuv cl_khr_int64_base_atomics cl_khr_int64_extended_atomics cl_khr_image2d_from_buffer cl_khr_depth_images cl_khr_3d_image_writes cl_intel_media_block_io cl_intel_va_api_media_sharing cl_intel_sharing_format_query cl_khr_pci_bus_info cl_intel_subgroup_local_block_io
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 4
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 4
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_TYPE_ACCELERATOR: 0

Detailed information for CL_DEVICE_TYPE_ACCELERATOR
CL_DEVICE_TYPE_DEFAULT: 1

Detailed information for CL_DEVICE_TYPE_DEFAULT

CL_DEVICE_TYPE_DEFAULT[0]
CL_DEVICE_NAME: Intel(R) UHD Graphics [0x9a60]
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: Intel(R) Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 3.0 NEO
CL_DRIVER_VERSION: 22.01.22131
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 1.2
CL_DEVICE_MAX_COMPUTE_UNITS: 32
CL_DEVICE_MAX_CLOCK_FREQUENCY: 1450
CL_DEVICE_MAX_WORK_GROUP_SIZE: 512
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 1024
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 4294959104
CL_DEVICE_GLOBAL_MEM_SIZE: 53658972160
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 4294959104
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 524288
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 64
CL_DEVICE_LOCAL_MEM_SIZE: 65536
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 52
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 1
CL_DEVICE_EXTENSIONS: cl_khr_byte_addressable_store cl_khr_fp16 cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_icd cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_intel_command_queue_families cl_intel_subgroups cl_intel_required_subgroup_size cl_intel_subgroups_short cl_khr_spir cl_intel_accelerator cl_intel_driver_diagnostics cl_khr_priority_hints cl_khr_throttle_hints cl_khr_create_command_queue cl_intel_subgroups_char cl_intel_subgroups_long cl_khr_il_program cl_intel_mem_force_host_memory cl_khr_subgroup_extended_types cl_khr_subgroup_non_uniform_vote cl_khr_subgroup_ballot cl_khr_subgroup_non_uniform_arithmetic cl_khr_subgroup_shuffle cl_khr_subgroup_shuffle_relative cl_khr_subgroup_clustered_reduce cl_intel_device_attribute_query cl_khr_suggested_local_work_size cl_intel_spirv_media_block_io cl_intel_spirv_subgroups cl_khr_spirv_no_integer_wrap_decoration cl_intel_unified_shared_memory_preview cl_khr_mipmap_image cl_khr_mipmap_image_writes cl_intel_planar_yuv cl_intel_packed_yuv cl_khr_int64_base_atomics cl_khr_int64_extended_atomics cl_khr_image2d_from_buffer cl_khr_depth_images cl_khr_3d_image_writes cl_intel_media_block_io cl_intel_va_api_media_sharing cl_intel_sharing_format_query cl_khr_pci_bus_info cl_intel_subgroup_local_block_io
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 4
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 4
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_TYPE_ALL: 1

Detailed information for CL_DEVICE_TYPE_ALL

CL_DEVICE_TYPE_ALL[0]
CL_DEVICE_NAME: Intel(R) UHD Graphics [0x9a60]
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: Intel(R) Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 3.0 NEO
CL_DRIVER_VERSION: 22.01.22131
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 1.2
CL_DEVICE_MAX_COMPUTE_UNITS: 32
CL_DEVICE_MAX_CLOCK_FREQUENCY: 1450
CL_DEVICE_MAX_WORK_GROUP_SIZE: 512
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 1024
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 4294959104
CL_DEVICE_GLOBAL_MEM_SIZE: 53658972160
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 4294959104
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 524288
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 64
CL_DEVICE_LOCAL_MEM_SIZE: 65536
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 52
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 1
CL_DEVICE_EXTENSIONS: cl_khr_byte_addressable_store cl_khr_fp16 cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_icd cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_intel_command_queue_families cl_intel_subgroups cl_intel_required_subgroup_size cl_intel_subgroups_short cl_khr_spir cl_intel_accelerator cl_intel_driver_diagnostics cl_khr_priority_hints cl_khr_throttle_hints cl_khr_create_command_queue cl_intel_subgroups_char cl_intel_subgroups_long cl_khr_il_program cl_intel_mem_force_host_memory cl_khr_subgroup_extended_types cl_khr_subgroup_non_uniform_vote cl_khr_subgroup_ballot cl_khr_subgroup_non_uniform_arithmetic cl_khr_subgroup_shuffle cl_khr_subgroup_shuffle_relative cl_khr_subgroup_clustered_reduce cl_intel_device_attribute_query cl_khr_suggested_local_work_size cl_intel_spirv_media_block_io cl_intel_spirv_subgroups cl_khr_spirv_no_integer_wrap_decoration cl_intel_unified_shared_memory_preview cl_khr_mipmap_image cl_khr_mipmap_image_writes cl_intel_planar_yuv cl_intel_packed_yuv cl_khr_int64_base_atomics cl_khr_int64_extended_atomics cl_khr_image2d_from_buffer cl_khr_depth_images cl_khr_3d_image_writes cl_intel_media_block_io cl_intel_va_api_media_sharing cl_intel_sharing_format_query cl_khr_pci_bus_info cl_intel_subgroup_local_block_io
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 4
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 4
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 1

Number of devices available for each type in NVIDIA CUDA
CL_DEVICE_TYPE_CPU: 0

Detailed information for CL_DEVICE_TYPE_CPU
CL_DEVICE_TYPE_GPU: 1

Detailed information for CL_DEVICE_TYPE_GPU

CL_DEVICE_TYPE_GPU[0]
CL_DEVICE_NAME: NVIDIA GeForce RTX 3080 Laptop GPU
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: NVIDIA Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 3.0 CUDA
CL_DRIVER_VERSION: 470.103.01
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 1.2
CL_DEVICE_MAX_COMPUTE_UNITS: 48
CL_DEVICE_MAX_CLOCK_FREQUENCY: 1545
CL_DEVICE_MAX_WORK_GROUP_SIZE: 1024
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 4096
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 4227153920
CL_DEVICE_GLOBAL_MEM_SIZE: 16908615680
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 65536
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 1376256
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 128
CL_DEVICE_LOCAL_MEM_SIZE: 49152
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 1000
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 0
CL_DEVICE_EXTENSIONS: cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_khr_fp64 cl_khr_3d_image_writes cl_khr_byte_addressable_store cl_khr_icd cl_khr_gl_sharing cl_nv_compiler_options cl_nv_device_attribute_query cl_nv_pragma_unroll cl_nv_copy_opts cl_nv_create_buffer cl_khr_int64_base_atomics cl_khr_int64_extended_atomics cl_khr_device_uuid cl_khr_pci_bus_info
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_TYPE_ACCELERATOR: 0

Detailed information for CL_DEVICE_TYPE_ACCELERATOR
CL_DEVICE_TYPE_DEFAULT: 1

Detailed information for CL_DEVICE_TYPE_DEFAULT

CL_DEVICE_TYPE_DEFAULT[0]
CL_DEVICE_NAME: NVIDIA GeForce RTX 3080 Laptop GPU
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: NVIDIA Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 3.0 CUDA
CL_DRIVER_VERSION: 470.103.01
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 1.2
CL_DEVICE_MAX_COMPUTE_UNITS: 48
CL_DEVICE_MAX_CLOCK_FREQUENCY: 1545
CL_DEVICE_MAX_WORK_GROUP_SIZE: 1024
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 4096
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 4227153920
CL_DEVICE_GLOBAL_MEM_SIZE: 16908615680
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 65536
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 1376256
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 128
CL_DEVICE_LOCAL_MEM_SIZE: 49152
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 1000
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 0
CL_DEVICE_EXTENSIONS: cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_khr_fp64 cl_khr_3d_image_writes cl_khr_byte_addressable_store cl_khr_icd cl_khr_gl_sharing cl_nv_compiler_options cl_nv_device_attribute_query cl_nv_pragma_unroll cl_nv_copy_opts cl_nv_create_buffer cl_khr_int64_base_atomics cl_khr_int64_extended_atomics cl_khr_device_uuid cl_khr_pci_bus_info
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_TYPE_ALL: 1

Detailed information for CL_DEVICE_TYPE_ALL

CL_DEVICE_TYPE_ALL[0]
CL_DEVICE_NAME: NVIDIA GeForce RTX 3080 Laptop GPU
CL_DEVICE_AVAILABLE: 1
CL_DEVICE_VENDOR: NVIDIA Corporation
CL_DEVICE_PROFILE: FULL_PROFILE
CL_DEVICE_VERSION: OpenCL 3.0 CUDA
CL_DRIVER_VERSION: 470.103.01
CL_DEVICE_OPENCL_C_VERSION: OpenCL C 1.2
CL_DEVICE_MAX_COMPUTE_UNITS: 48
CL_DEVICE_MAX_CLOCK_FREQUENCY: 1545
CL_DEVICE_MAX_WORK_GROUP_SIZE: 1024
CL_DEVICE_ADDRESS_BITS: 64
CL_DEVICE_MEM_BASE_ADDR_ALIGN: 4096
CL_DEVICE_MAX_MEM_ALLOC_SIZE: 4227153920
CL_DEVICE_GLOBAL_MEM_SIZE: 16908615680
CL_DEVICE_MAX_CONSTANT_BUFFER_SIZE: 65536
CL_DEVICE_GLOBAL_MEM_CACHE_SIZE: 1376256
CL_DEVICE_GLOBAL_MEM_CACHELINE_SIZE: 128
CL_DEVICE_LOCAL_MEM_SIZE: 49152
CL_DEVICE_PROFILING_TIMER_RESOLUTION: 1000
CL_DEVICE_IMAGE_SUPPORT: 1
CL_DEVICE_ERROR_CORRECTION_SUPPORT: 0
CL_DEVICE_HOST_UNIFIED_MEMORY: 0
CL_DEVICE_EXTENSIONS: cl_khr_global_int32_base_atomics cl_khr_global_int32_extended_atomics cl_khr_local_int32_base_atomics cl_khr_local_int32_extended_atomics cl_khr_fp64 cl_khr_3d_image_writes cl_khr_byte_addressable_store cl_khr_icd cl_khr_gl_sharing cl_nv_compiler_options cl_nv_device_attribute_query cl_nv_pragma_unroll cl_nv_copy_opts cl_nv_create_buffer cl_khr_int64_base_atomics cl_khr_int64_extended_atomics cl_khr_device_uuid cl_khr_pci_bus_info
CL_DEVICE_PREFERRED_VECTOR_WIDTH_INT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_LONG: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_PREFERRED_VECTOR_WIDTH_DOUBLE: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_INT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_LONG: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_FLOAT: 1
CL_DEVICE_NATIVE_VECTOR_WIDTH_DOUBLE: 1

```

## console output for vec_add
```
Number of bytes in Giga: 0.12

[0] Intel(R) CPU Runtime for OpenCL(TM) Applications

[1] Intel(R) OpenCL HD Graphics

[2] NVIDIA CUDA


Result on Intel(R) CPU Runtime for OpenCL(TM) Applications: 1.01156e+07

TIMER:: Vector addition on Intel(R) CPU Runtime for OpenCL(TM) Applications took 280 milliseconds

Result on Intel(R) OpenCL HD Graphics: 1.01156e+07

TIMER:: Vector addition on Intel(R) OpenCL HD Graphics took 266 milliseconds

Result on NVIDIA CUDA: 1.01156e+07

TIMER:: Vector addition on NVIDIA CUDA took 161 milliseconds
```

