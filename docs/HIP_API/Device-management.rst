.. _Device-management:

   
Device management
==================

Device management types and functions.

hipDeviceSynchronize	
-----------------------

.. doxygenfunction:: hipError_t hipDeviceSynchronize(void)	



hipDeviceReset 
---------------

.. doxygenfunction:: hipError_t hipDeviceReset(void)	


hipSetDevice
-------------

.. doxygenfunction:: hipError_t hipSetDevice(int deviceId)	


hipGetDevice
----------------

.. doxygenfunction:: hipError_t hipGetDevice(int * deviceId)	


hipGetDeviceCount
-----------------

.. doxygenfunction:: hipError_t hipGetDeviceCount	(int * count)	


hipDeviceGetAttribute
----------------------

.. doxygenfunction:: hipDeviceGetAttribute


hipGetDeviceProperties
-----------------------
.. doxygenfunction:: hipGetDeviceProperties

hipDeviceSetCacheConfig
------------------------
.. doxygenfunction:: hipDeviceSetCacheConfig

hipDeviceGetCacheConfig
-------------------------
.. doxygenfunction:: hipDeviceGetCacheConfig

hipDeviceGetLimit
------------------
.. doxygenfunction:: hipDeviceGetLimit

hipFuncSetCacheConfig 
----------------------
.. doxygenfunction:: hipFuncSetCacheConfig 


hipDeviceGetSharedMemConfig 
---------------------------
.. doxygenfunction:: hipDeviceGetSharedMemConfig 

hipDeviceSetSharedMemConfig
----------------------------
.. doxygenfunction:: hipDeviceSetSharedMemConfig


hipSetDeviceFlags
-------------------
.. doxygenfunction:: hipSetDeviceFlags


hipChooseDevice 
----------------
.. doxygenfunction:: hipChooseDevice 




















