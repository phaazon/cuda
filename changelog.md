0.6.6.0

  * Drop support for CUDA 3.0 and older.

  * Combine the definition of the 'Event' and 'Stream' data types. As of
    CUDA-3.1 these data structures are equivalent, and can be safely shared
    between runtime and driver API calls and libraries.

  * Mark FFI imports of potentially long-running API functions as safe. This
    allows them to be safely called from Haskell threads without blocking the
    entire HEC.

0.6.5.1

  * Build fix for Mac OS X 10.10 (Yosemite)

0.6.5.0

  * Add support for the CUDA-6.5 release

