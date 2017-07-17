Ring-Buffer
===========

A simple ring buffer (circular buffer) designed for embedded systems.

注意，当环形缓冲区长度超过256时，要将u_int8 改为 u_int16或u_int32,不然ring_buffer_num_items会出问题，很多函数的返回值，超过255的也会被截掉。
