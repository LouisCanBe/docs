.. _cn_overview_paddle_device_cuda:

paddle.device.cuda
==========================

paddle.device.cuda 目录下包含与 CUDA 相关的 API。具体如下：

.. csv-table::
    :header: "API 名称", "API 功能"
    :widths: 10, 30

    " :ref:`memory_reserved <cn_api_paddle_device_cuda_memory_reserved>` ", "返回给定设备上当前由 Allocator 管理的显存大小。"
    " :ref:`memory_allocated <cn_api_paddle_device_cuda_memory_allocated>` ", "返回给定设备上当前分配给 Tensor 的显存大小。"
    " :ref:`max_memory_reserved <cn_api_paddle_device_cuda_max_memory_reserved>`","返回给定设备上由 Allocator 管理的显存峰值。"
    " :ref:`max_memory_allocated <cn_api_paddle_device_cuda_max_memory_allocated>`", "返回给定设备上分配给 Tensor 的显存峰值。"
    " :ref:`current_stream <cn_api_paddle_device_cuda_current_stream>`", "返回当前 CUDA 流。"
    " :ref:`device_count <cn_api_paddle_device_cuda_device_count>`", "当前程序可用的 GPU 数量(int)。"
    " :ref:`empty_cache <cn_api_paddle_device_cuda_empty_cache>`", "释放显存分配器中空闲的显存。"
    " :ref:`Event <cn_api_paddle_device_cuda_Event>`", "CUDA event 的句柄。"
    " :ref:`get_device_capability <cn_api_paddle_device_cuda_get_device_capability>`", "获取设备计算能力的主要和次要修订号。"  
    " :ref:`get_device_name <cn_api_paddle_device_cuda_get_device_name>`", "获取设备的名称。"
    " :ref:`get_device_properties <cn_api_paddle_device_cuda_get_device_properties>`", "返回给定的设备属性。"
    " :ref:`Stream <cn_api_paddle_device_cuda_Stream>`", "CUDA stream 的句柄。"
    " :ref:`stream_guard <cn_api_paddle_device_cuda_stream_guard>`", "指定stream以切换当前的 CUDA stream。"
    " :ref:`synchronize <cn_api_paddle_device_cuda_synchronize>`", "等待给定的 CUDA 设备上的计算完成。"
